# ml_project
# 🛒 Analyse E-commerce simulée avec MongoDB et Machine Learning

## 🇫🇷 Présentation

Ce projet simule une base de données e-commerce avec des données clients, des commandes, et des produits générés à l’aide de la librairie `Faker`. Les données sont stockées dans MongoDB, analysées avec `pymongo` et `pandas`, puis utilisées pour :

- Calculer des **indicateurs clés** (chiffre d’affaires, panier moyen, etc.)
- Réaliser une **segmentation clients** (VIP, promo addict, régulier, etc.)
- Prédire le **churn** (perte de clients) via un modèle **Random Forest**

L’objectif est de démontrer des compétences en manipulation de données, analyse client, et machine learning supervisé sur un jeu de données réaliste mais simulé.

## 📦 Technologies utilisées

- `Python` (pandas, scikit-learn, seaborn, matplotlib)
- `MongoDB` + `pymongo`
- `Faker` pour générer les données
- `scikit-learn` pour le machine learning

## 🔍 Étapes principales

1. **Génération de données** : 100 clients, 2000 commandes, 10 produits
2. **Calculs de KPIs** : chiffre d’affaires par pays, panier moyen par mois, etc.
3. **Segmentation clients** : classification des profils d’acheteurs
4. **Détection du churn** : étiquetage des clients n’ayant pas commandé depuis 4 jours
5. **Modélisation** : Random Forest, évaluation par matrice de confusion et `classification_report`
6. **Visualisations** : courbes, heatmap, statistiques descriptives

---

## 🇬🇧 Project Overview

This project simulates an e-commerce database with customers, orders, and products using the `Faker` library. Data is stored in MongoDB, analyzed using `pymongo` and `pandas`, and used to:

- Compute **key performance indicators** (total revenue, average basket, etc.)
- Perform **customer segmentation** (VIP, promo addict, regular, etc.)
- Predict **churn** using a **Random Forest** classifier

The goal is to showcase skills in data manipulation, customer analysis, and supervised machine learning on realistic synthetic data.

## 📦 Tech Stack

- `Python` (pandas, scikit-learn, seaborn, matplotlib)
- `MongoDB` + `pymongo`
- `Faker` for data generation
- `scikit-learn` for modeling

## 🔍 Main Steps

1. **Data generation**: 100 customers, 2000 orders, 10 products
2. **KPI calculation**: revenue per country, monthly average basket, etc.
3. **Customer segmentation**: identify buyer profiles
4. **Churn labeling**: mark clients with no purchase in the last 4 days
5. **Modeling**: train and evaluate a Random Forest classifier
6. **Visualizations**: plots, confusion matrix, and summary stats

---

## 📁 Fichiers principaux / Key Files

- `notebook.ipynb` : code complet, étapes de traitement, analyse, et modèle
- `README.md` : ce fichier
- (Optionnel) `requirements.txt` : dépendances Python

---

## ✨ Auteurs / Authors

Projet réalisé par [Ton Nom ou Pseudo].

---

