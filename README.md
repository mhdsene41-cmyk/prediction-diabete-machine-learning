# 🩺 Prédiction du diabète avec le Machine Learning

## 📌 Présentation du projet

Ce projet consiste à développer un modèle prédictif permettant d'identifier la probabilité de présence d'un diabète de type 2 à partir de différentes caractéristiques médicales.

L'objectif est d'explorer les données, de les préparer pour l'apprentissage automatique, puis de construire et comparer plusieurs modèles de Machine Learning.

## 🎯 Objectifs

* Explorer et comprendre les données médicales.
* Préparer et nettoyer les données.
* Construire plusieurs modèles prédictifs.
* Comparer les performances des modèles.
* Évaluer les prédictions obtenues.
* Identifier les variables importantes pour la prédiction.
* Visualiser les résultats.

## 📊 Données utilisées

Le projet utilise le **Pima Indians Diabetes Database**.

Le jeu de données contient des informations médicales permettant de déterminer si une personne présente ou non un diabète.

Les principales variables sont :

* `Pregnancies` : nombre de grossesses
* `Glucose` : taux de glucose
* `BloodPressure` : pression artérielle
* `SkinThickness` : épaisseur de la peau
* `Insulin` : taux d'insuline
* `BMI` : indice de masse corporelle
* `DiabetesPedigreeFunction` : fonction de pedigree du diabète
* `Age` : âge
* `Outcome` : résultat de la prédiction

`Outcome = 0` indique l'absence de diabète et `Outcome = 1` indique la présence d'un diabète.

## 🤖 Modèles de Machine Learning

Les modèles étudiés dans ce projet sont :

1. **Régression logistique**
2. **Arbre de décision**
3. **Random Forest**

Les performances des modèles seront comparées à l'aide de différentes métriques d'évaluation.

## 🛠️ Technologies utilisées

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## 📁 Organisation du projet

```text
prediction-diabete-machine-learning/
│
├── data/
│   └── diabetes.csv
│
├── notebooks/
│   └── analyse_diabete.ipynb
│
├── results/
│
├── rapport/
│
├── presentation/
│
└── README.md
```

## 📓 Notebook

Le notebook contient les différentes étapes du projet :

* importation des bibliothèques ;
* exploration des données ;
* nettoyage et préparation ;
* entraînement des modèles ;
* évaluation ;
* visualisation des résultats.

## 📈 Résultats

Les résultats des différents modèles seront présentés après l'entraînement et l'évaluation sur les données de test.

Cette section sera complétée avec les métriques, graphiques et matrices de confusion obtenus lors de l'expérimentation.

## 📄 Documents

Le rapport détaillé et la présentation du projet seront ajoutés dans les dossiers correspondants.

## 🎓 Contexte

Projet réalisé dans le cadre d'un travail universitaire en **Machine Learning / Intelligence Artificielle**.
