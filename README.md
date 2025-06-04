# Réseau-neurones
# Prédiction de la Consommation Électrique avec un Réseau de Neurones

##  Présentation

Ce projet vise à concevoir une **architecture de réseau de neurones artificiels** pour prédire la consommation d’électricité à partir de différentes variables explicatives. Le modèle est entraîné sur un jeu de données temporel incluant des variables telles que la température, des retards de charge et des indicateurs calendaires.

##  Données utilisées

Chaque ligne du fichier de données contient les colonnes suivantes :

- `year`, `month`, `day` : variables calendaires
- `load` : charge électrique (cible à prédire)
- `temp` : température au moment t
- `load_lag_1` à `load_lag_7` : charges électriques des jours précédents
- `temp_lag_1` à `temp_lag_7` : températures des jours précédents

## Objectif

Prédire la **valeur de charge électrique (load)** à partir des autres variables.

## Fonctionnalités

- Création et entraînement d'un réseau de neurones
- Suivi des performances sur les ensembles d'entraînement et de validation
- Comparaison d’algorithmes d’optimisation
- Analyse de l’effet de la taille des batchs
- Prédiction sur de nouvelles données

##  Technologies utilisées

- Python 3
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Scikit-learn

