# Data Refinement Project

## Objectif
Ce projet a pour objectif d’appliquer les notions de data quality et de data refinement à partir d’un dataset brut.
Les données sont nettoyées, transformées et vérifiées afin de produire un jeu de données exploitable et cohérent.

## Dataset
- Source : Kaggle – Cafe Sales Dirty Data for Cleaning Training
- Format : CSV
- Données volontairement dégradées (valeurs manquantes, doublons, erreurs de format, incohérences)

## Structure du projet
- DATA/RAW : données brutes
- DATA/PROCESSED : données nettoyées finales
- NOTEBOOKS :
  - 01_EXPLORATION : compréhension des données
  - 02_CLEANING : nettoyage et correction des problèmes de qualité
  - 03_TRANSFORMATION : transformation et enrichissement
- REPORTS : rapport final du projet

## Technologies utilisées
- Python
- Pandas
- Jupyter Notebook

## Résultat
Le projet produit un dataset final nettoyé (`cafe_sales_clean.csv`) prêt à être utilisé pour des analyses fiables.
Les choix de nettoyage et de transformation sont justifiés dans les notebooks et le rapport.
