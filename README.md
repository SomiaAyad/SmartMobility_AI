# SmartMobility_AI

### Estimation de la demande horaire de vélos à Séoul par Machine Learning

## 1. Problématique du projet

La demande de vélos en libre-service varie en fonction de plusieurs facteurs, tels que l'heure, la date et les conditions météorologiques.

Cette variation rend difficile l'estimation du nombre de vélos nécessaires à chaque période.

**Problématique :** Comment exploiter les données temporelles et météorologiques ainsi que les techniques de Machine Learning pour estimer le nombre de vélos loués pendant une heure donnée à Séoul, en Corée du Sud ?

Le projet s'appuie sur le jeu de données *Seoul Bike Sharing Demand* fourni par UCI.

## 2. Objectifs du projet

L'objectif principal est de développer une application capable d'estimer le nombre de locations de vélos par heure à partir de données historiques et de caractéristiques temporelles et météorologiques.

Les objectifs spécifiques sont :

* Maîtriser les outils et les bibliothèques nécessaires au développement du projet.
* Explorer et analyser les données de location de vélos.
* Identifier les facteurs qui influencent la demande horaire.
* Développer et comparer plusieurs modèles de Machine Learning.
* Évaluer les performances des modèles à l'aide de métriques adaptées.
* Intégrer le modèle sélectionné dans une application interactive avec Streamlit.

## 3. Commandes d'installation

### Prérequis

* Python 3.11 ou 3.12
* Visual Studio Code
* Git

### Création du dossier du projet

```bash
mkdir SmartMobility_AI
cd SmartMobility_AI
```

### Création de l'environnement virtuel

```bash
python -m venv .venv
```

### Activation de l'environnement virtuel (Windows)

```powershell
.\.venv\Scripts\Activate.ps1
```

### Mise à jour de pip

```bash
python -m pip install --upgrade pip
```

### Installation des bibliothèques

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib streamlit pytest
```

### Installation de Jupyter Notebook

```bash
pip install notebook
```

### Initialisation de Git

```bash
git init
```

## 4. Organisation du projet

```text
SmartMobility_AI/
│
├── .venv/                  # Environnement virtuel
│
├── exercises/
│   └── week01/             # Exercices de la première semaine
│
├── README.md               # Documentation du projet
│
└── .gitignore              # Fichiers exclus du versionnement
```

## 5. Project Status

**Statut actuel : Semaine 01 – En cours**

Travaux prévus pour cette étape :

* Prise en main du langage Python.
* Découverte des variables, types, listes et dictionnaires.
* Utilisation des conditions, boucles et fonctions.
* Familiarisation avec le terminal et les chemins d'accès.
* Installation et configuration de l'environnement de développement.
* Initialisation du dépôt Git.
