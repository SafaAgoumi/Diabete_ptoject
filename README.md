#  Diabetes Analysis & Prediction Project

##  Description

Ce projet consiste en une **analyse complète du dataset Pima Indian Diabetes** suivie de la mise en place de **modèles de Machine Learning** pour prédire la présence du diabète chez les patients.

Le travail est structuré en plusieurs étapes allant de l’exploration des données jusqu’à la modélisation prédictive.

---

##  Dataset

* Dataset : *Pima Indian Diabetes*
* Contient des informations médicales (glucose, pression sanguine, IMC, âge, etc.)
* Objectif : prédire si un patient est diabétique ou non

---

##  Technologies utilisées

* Python 
* Pandas
* NumPy
* Matplotlib & Seaborn 
* SciPy
* Scikit-learn 

---

##  Étapes du projet

###  1. Chargement et exploration des données

* Importation du dataset CSV
* Affichage des premières lignes
* Analyse des dimensions et types de données

---

###  2. Analyse univariée

* Étude individuelle de chaque variable
* Visualisation des distributions
* Tests de normalité (Shapiro, Normaltest)

---

###  3. Analyse bivariée

* Corrélations entre variables
* Tests statistiques :

  * Pearson
  * Spearman
  * ANOVA
  * T-test
* Visualisations (heatmap, scatter plots)

---

###  4. Analyse en Composantes Principales (ACP)

* Standardisation des données
* Réduction de dimension
* Visualisation des composantes principales

---

###  5. Machine Learning - Classification

Modèles utilisés :

* Régression Logistique
* Arbre de Décision

Techniques appliquées :

* Train/Test split
* Cross-validation
* GridSearch (optimisation des hyperparamètres)

---

##  Installation et exécution

### 1. Cloner le projet

```bash
git clone https://github.com/username/Projet_Diabete_Analyse.git
cd Projet_Diabete_Analyse
```

### 2. Installer les dépendances

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

### 3. Lancer le notebook

```bash
jupyter notebook
```

---

##  Résultats attendus

* Visualisations claires des données médicales
* Identification des variables importantes
* Modèle capable de prédire le diabète

---

##  Structure du projet

```
Projet_Diabete_Analyse/
│── DiabeteNotebook.ipynb
│── diabetes.csv
│── diabetes_cleaned.csv
│── README.md
```

---

##  Auteur

**Safa Agoumi**
Étudiante en ingénierie informatique et réseaux option Data Science & AI

---


