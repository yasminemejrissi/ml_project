# Analyse e-commerce simulée avec MongoDB et Machine Learning

## Présentation

Ce projet simule une base de données e-commerce à l'aide de `Faker`, en générant des données réalistes sur des clients, des produits et des commandes. Ces données sont stockées dans MongoDB, puis analysées avec `pymongo`, `pandas` et `scikit-learn`.

L’objectif est triple :

1. Extraire des indicateurs clés de performance (KPIs) : chiffre d'affaires, panier moyen, taux d'utilisation de promotions, etc.
2. Segmenter les clients selon leur comportement d'achat (VIP, addict aux promos, régulier, occasionnel).
3. Prédire la probabilité de churn (perte de clients inactifs) à l’aide d’un modèle de classification supervisée.

## Pourquoi le modèle Random Forest ?

J’ai choisi Random Forest comme modèle de classification pour prédire le churn car :

- C’est un modèle robuste et non-linéaire, capable de capturer des interactions complexes entre variables.
- Il s’adapte bien aux données numériques sans nécessiter de normalisation.
- Il réduit le risque de surapprentissage grâce à l’agrégation de plusieurs arbres (bagging).
- Il offre une interprétation intuitive des résultats via l’importance des variables.
- Il est rapide à entraîner, ce qui est avantageux pour une phase exploratoire.

Ce choix s’inscrit dans une logique de rigueur analytique, tout en restant pragmatique pour un projet exploratoire basé sur des données synthétiques.

## Technologies utilisées

- Python : pandas, numpy, scikit-learn, seaborn, matplotlib
- Base de données NoSQL : MongoDB
- Génération de données : Faker
- Machine Learning : RandomForestClassifier

## Étapes du projet

1. Génération des données : 100 clients, 2000 commandes, 10 produits
2. Analyse des comportements : chiffre d'affaires par pays, panier moyen par mois, utilisation de promotions
3. Segmentation clients : attribution d’un profil en fonction du comportement d’achat
4. Détection du churn : identification des clients n’ayant pas commandé depuis plus de 4 jours
5. Modélisation : entraînement d’un modèle Random Forest
6. Visualisations : matrice de confusion, statistiques descriptives


---


### Simulated E-commerce Analysis with MongoDB and Machine Learning

This project simulates an e-commerce database using `Faker`, generating realistic customer, product, and order data. The data is stored in MongoDB and analyzed using `pymongo`, `pandas`, and `scikit-learn`.

The goals of the project are:

1. Extract key performance indicators (KPIs): total revenue, average basket, promo usage rate.
2. Segment customers by behavior (VIP, promo addict, regular, occasional).
3. Predict customer churn using supervised classification.

### Why Random Forest?

Random Forest was selected because it is:

- A robust, non-linear model that captures complex feature interactions.
- Well suited to numerical data, with no need for normalization.
- Less prone to overfitting due to ensemble learning (bagging).
- Interpretable via feature importance scores.
- Fast to train, making it ideal for exploratory projects on synthetic datasets.

This choice balances performance, interpretability, and ease of use in a realistic project context.

### Tech Stack

- Python: pandas, numpy, scikit-learn, seaborn, matplotlib
- NoSQL database: MongoDB
- Data generation: Faker
- Machine Learning: RandomForestClassifier

### Project Steps

1. Data simulation: 100 customers, 2000 orders, 10 products
2. KPI analysis: revenue by country, monthly trends, promo usage
3. Customer segmentation: based on order frequency and promo use
4. Churn labeling: inactive after 4 days
5. Modeling: training and evaluating a Random Forest classifier
6. Visualizations: confusion matrix, descriptive stats

## Author

Created by Mejrissi Yasmine — for learning and portfolio purposes.


