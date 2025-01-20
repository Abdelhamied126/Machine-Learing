# Travaux Pratiques de Machine Learning

Bienvenue dans ce dépôt GitHub dédié aux travaux pratiques réalisés en **Machine Learning**. Ces exercices couvrent divers aspects de l'apprentissage automatique, allant des concepts de base aux techniques avancées.

## 🎯 Objectifs
Ces travaux ont pour but de :
- Approfondir les principes fondamentaux et avancés du Machine Learning.
- Appliquer des méthodes de modélisation, d'analyse et d'évaluation.
- Renforcer les compétences en manipulation de données et en programmation.

---

## 📁 Structure du Dépôt

### 1. Réseaux Bayésiens
- **Résumé** : Étude des réseaux bayésiens pour la modélisation des relations probabilistes entre variables.
- **Points clés** :
  - Probabilités conditionnelles : calcul et propagation des incertitudes.
  - Graphes dirigés acycliques : représentation graphique des relations entre variables.
  - Inférence probabiliste : techniques exactes et approchées pour déduire des informations.
- **Exercices pratiques** : Construction d'un réseau bayésien simple, inférence par échantillonnage de Monte-Carlo.
- 📄 [Notebook](./Bayesian_Networks.ipynb)

### 2. Clustering
- **Résumé** : Analyse des techniques de clustering pour la classification non supervisée.
- **Points clés** :
  - Algorithme K-means : segmentation des données en groupes homogènes.
  - Clustering hiérarchique : création d'une hiérarchie de clusters.
  - Indicateurs d'évaluation : utilisation des métriques silhouette et Davies-Bouldin.
- **Exercices pratiques** : Implémentation de K-means, comparaison avec clustering hiérarchique.
- 📄 [Notebook](./Clustering.ipynb)

### 3. Méthodes d'Ensemble et Sélection de Caractéristiques
- **Résumé** : Utilisation des méthodes d'ensemble pour améliorer les performances des modèles et sélection des variables pertinentes.
- **Points clés** :
  - Bagging (Random Forest) : réduction de la variance par agrégation de modèles.
  - Boosting (Gradient Boosting) : amélioration des performances en combinant des modèles faibles.
  - Techniques de sélection : sélection récursive des features (RFE), importance des variables.
- **Exercices pratiques** : Comparaison de performances entre Random Forest et Gradient Boosting.
- 📄 [Notebook](./Ensemble%20Methods%20and%20Feature%20Selection.ipynb)

### 4. Apprentissage par Renforcement
- **Résumé** : Implémentation de méthodes d'apprentissage par renforcement pour la prise de décision automatique.
- **Points clés** :
  - Q-Learning : algorithme d'apprentissage basé sur les valeurs d'action.
  - Politiques d'apprentissage : stratégie optimale de prise de décision.
  - Arbitrage exploration/exploitation : équilibre entre découverte et exploitation des connaissances acquises.
- **Exercices pratiques** : Implémentation d'un agent apprenant à jouer à un jeu simple.
- 📄 [Notebook](./Reinforcement_Learning.ipynb)

---

## 🛠️ Outils et Technologies
- **Langage** : Python (3.x)
- **Bibliothèques utilisées** :
  - `scikit-learn`
  - `numpy`, `pandas`
  - `matplotlib`, `seaborn`
  - `tensorflow` ou `pytorch` selon les besoins

