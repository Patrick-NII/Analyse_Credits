# Analyse et Prédiction des Prêts Immobiliers

Ce projet vise à prédire si un client est en capacité de contracter un prêt immobilier en utilisant un ensemble de données divisé en deux parties : `test.csv` et `train.csv`. Le dataset est pertinent pour analyser les facteurs influençant l'approbation des prêts, modéliser le risque de crédit, et développer des stratégies de prêt plus efficaces. Le projet comprend l'analyse exploratoire des données, la gestion des outliers, la visualisation des taux de prêt, l'analyse de corrélation, ainsi que le déploiement de l'application de prédiction avec Streamlit et la création d'un tableau de bord interactif avec Power BI.

## Table des Matières

1. [Introduction](#introduction)
2. [Étapes du Projet](#étapes-du-projet)
3. [Analyse Exploratoire des Données (EDA)](#analyse-exploratoire-des-données-eda)
4. [Gestion des Outliers](#gestion-des-outliers)
5. [Visualisation](#visualisation)
6. [Analyse de Corrélation](#analyse-de-corrélation)
7. [Prétraitement des Données](#prétraitement-des-données)
8. [Modélisation](#modélisation)
9. [Choix de l'Algorithme de Machine Learning](#choix-de-lalgorithme-de-machine-learning)
10. [Déploiement avec Streamlit](#déploiement-avec-streamlit)
11. [Tableau de Bord Power BI](#tableau-de-bord-power-bi)
12. [Conclusion](#conclusion)

## Introduction

L'objectif principal de ce projet est de développer un modèle de machine learning capable de prédire la capacité d'un client à obtenir un prêt immobilier. Le projet inclut également des visualisations pour mieux comprendre les données et les tendances associées aux prêts immobiliers.

## Étapes du Projet

1. **Importation des données** : Chargement des fichiers `train.csv` et `test.csv`.
2. **Nettoyage des données** : Gestion des valeurs manquantes et des doublons.
3. **Analyse Exploratoire des Données (EDA)** :
    - Analyse univariée
    - Analyse bivariée
    - Analyse multivariée
4. **Gestion des Outliers** : Détection et traitement des valeurs aberrantes.
5. **Visualisation des Données** : Création de graphiques et de visualisations pour mieux comprendre les tendances.
6. **Analyse de Corrélation** : Création et visualisation de la matrice de corrélation.
7. **Prétraitement des Données** :
    - Encodage des variables catégorielles
    - Normalisation des données
8. **Modélisation** : Construction et évaluation du modèle de prédiction.
9. **Choix de l'Algorithme de Machine Learning** :
    - Sélection de l'algorithme adapté aux données et à l'objectif 
10. **Déploiement** :
    - Déploiement de l'application avec Streamlit
    - Création d'un tableau de bord interactif avec Power BI

## Analyse Exploratoire des Données (EDA)

### Analyse Univariée
L'analyse univariée consiste à examiner une variable à la fois. Nous analyserons les distributions des variables individuelles à l'aide d'histogrammes et de boîtes à moustaches (boxplots).

### Analyse Bivariée
L'analyse bivariée examine la relation entre deux variables. Nous utiliserons `sns.countplot` pour visualiser ces relations.

### Analyse Multivariée
L'analyse multivariée examine les relations entre plusieurs variables simultanément. Nous utiliserons des graphiques en paires (pair plots) et des techniques de réduction de dimensionnalité comme l'ACP (Analyse en Composantes Principales).

## Gestion des Outliers

Les outliers ou valeurs aberrantes peuvent fausser les résultats de notre analyse et de notre modèle. Nous utiliserons des techniques comme l'IQR (Interquartile Range) et les scores Z pour détecter et traiter ces valeurs.

## Visualisation

Nous créerons diverses visualisations pour mieux comprendre les données, telles que :

- Histogrammes
- Boxplot
- Countplot
- Heatmaps
- Pairplots

## Analyse de Corrélation

Nous calculerons et visualiserons la matrice de corrélation pour identifier les relations entre les variables. Une heatmap de la matrice de corrélation nous permettra de voir facilement quelles variables sont fortement corrélées.

## Prétraitement des Données

La préparation des données comprendra l'encodage des variables catégorielles et la normalisation des données pour garantir des résultats optimaux du modèle.

## Modélisation

Pour ce projet, nous utiliserons la Régression Logistique comme algorithme de machine learning. La Régression Logistique est choisie pour sa capacité à modéliser des problèmes de classification binaire comme celui-ci, tout en étant interprétable et offrant de bonnes performances pour prédire la probabilité d'approbation d'un prêt immobilier.

## Déploiement avec Streamlit

Streamlit sera utilisé pour créer une application web interactive où les utilisateurs pourront :

- Charger de nouvelles données
- Voir les prédictions du modèle
- Visualiser les principales statistiques et graphiques

## Tableau de Bord Power BI

Nous utiliserons Power BI pour créer un tableau de bord interactif qui permettra aux utilisateurs de visualiser et d'explorer les données de manière intuitive. Ce tableau de bord comprendra :

- Des graphiques interactifs
- Des filtres dynamiques
- Des visualisations des prédictions du modèle

## Conclusion

Ce projet combine des techniques d'analyse de données, de visualisation et de machine learning pour prédire la capacité d'un client à obtenir un prêt immobilier. Le déploiement de l'application avec Streamlit et la création d'un tableau de bord Power BI offrent des outils puissants pour l'exploration et la visualisation des données.

---

Pour toute question ou suggestion, n'hésitez pas à me contacter.
