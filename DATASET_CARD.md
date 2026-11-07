## DATASET CARD

**Version :** 1
**Date :** 06/11/2026

## 1. Présentation du dataset

**Nom :** Seoul Bike Sharing Demand
**Source :** UCI Machine Learning Repository
**URL :** [https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)
**DOI :** 10.24432/C5F62R
**Licence :** CC BY 4.0
**Format :** CSV
**Dimensions :** 8 760 lignes et 14 colonnes
**Période :** 01/12/2017 au 30/11/2018
**Localisation :** Séoul, Corée du Sud.

## 2. Description des variables

**Variable cible (Target) :**

`Rented Bike Count` : nombre de vélos loués par heure.

**Variables explicatives (Features) :**

`Date` : date.
`Hour` : heure.
`Temperature(°C)` : température.
`Humidity(%)` : humidité.
`Wind speed (m/s)` : vitesse du vent.
`Visibility (10m)` : visibilité.
`Dew point temperature(°C)` : température du point de rosée.
`Solar Radiation (MJ/m2)` : rayonnement solaire.
`Rainfall(mm)` : précipitations.
`Snowfall (cm)` : chutes de neige.
`Seasons` : saison.
`Holiday` : jour férié ou non.
`Functioning Day` : fonctionnement du service.

## 3. Contrôles qualité

**Nombre de lignes et colonnes :** 8 760 × 14.
**Types des variables :** int64, float64, object.
**Valeurs manquantes :** aucune.
**Doublons :** aucune.

## 4. Utilisation dans le projet

Ce dataset sera utilisé pour entraîner et évaluer des modèles de Machine Learning capables de prédire le nombre de vélos loués par heure à Séoul.
