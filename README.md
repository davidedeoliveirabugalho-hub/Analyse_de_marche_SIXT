# 📊 [Analyse de marché SIXT] cas pratique en cours de formation BOOTCAMP DATA ANALYST Databird

## 🎯 Objectif
Sixt est un acteur majeur de la location de véhicules en France, proposant une
large gamme de voitures allant des modèles économiques aux voitures de luxe.
L’entreprise cherche en permanence à optimiser sa stratégie de tarification et à
mieux comprendre ses clients afin d’améliorer ses offres et maximiser ses
revenus.
L’équipe Data de Sixt dispose d’un vaste ensemble de données issues des
locations de véhicules : profils clients, paiements, historique des locations, avis
clients… mais ces données sont peu exploitées alors qu’elles pourraient permettre
d’affiner la stratégie commerciale de l’entreprise.
La mission :
1. Déterminer les principaux facteurs influençant le prix total payé par les
clients.
2. Identifier les périodes de forte et faible activité pour optimiser la gestion des
véhicules.
3. Segmenter les clients pour comprendre quels profils génèrent le plus de
revenus.
4. Analyser la satisfaction client et identifier les axes d’amélioration du service.

## 📋 Dataset
- **Source** : Databird
- **Taille** : clients (5000 lignes, 11 colonnes), locations ( 10000 lignes, 12 colonnes), paiements (10000 lignes, 18 colonnes), Avis clients (4509 lignes, 6 colonnes)
- **Période** : 01/2024 à 05/2025

## 🛠️ Outils utilisés
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## 📈 Méthodologie
1. **Collecte des données** : Import des csv fournis
2. **Nettoyage** : Dates, doublons, valeurs manquantes création d'une seule table "Master Database"
3. **EDA** : Statistiques descriptives, variables catégorielles, valeurs aberrantes/extrêmes, ecart interquartile, corrélation
4. **Modélisation** : Identification des clés de jointure
5. **Visualisation** : Boxplot, matrice de corrélation, histplot, plot, barplot, pieplot

## 🔍 Résultats clés
### Activité
- ✅ Malgré un volume de locations plus important au départ des aéroports, celles-ci ne génère pas plus de revenus que les autres sites
- ✅ Les utilitaires et les berlines représentent le plus faible volume mais génèrent autant de revenus que les catégories citadines et SUV.
      Une reflexion sur la communication ou des opérations marketing sur ces catégories pourraient accroitre les revenus générés
### Avis clients
- ✅ La note globale se situe entre 4 et 5. ce qui révèle une satisfaction client élevée
- ✅ 4,5% d'avis négatifs contre 95,5% positifs
- ✅ 35% des avis négatifs concernent l'état des véhicules. Une reflexion sur l'entretien des véhicule serait à mener pour encore améliorer l'expérience client
