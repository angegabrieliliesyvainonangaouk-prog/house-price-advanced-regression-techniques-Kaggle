# house-price-advanced-regression-techniques-Kaggle
This project is a Kaggle competition whose goal is to predict house prices based on several factors listed in 80 columns.
As with my other projects, it will be presented in English first, followed by French.

Ce projet est une compétition Kaggle dont le but est de déterminer le prix des maisons selon plusieurs facteurs répertoriés dans 80 colonnes.
Comme pour mes autres projets, il sera présenté en anglais d’abord, suivi du français

1)Analysis, understanding, and determination of the main theme of my dataset
Analyse, compréhension et détermination du thème principal de mon jeu de données

2)Visualization of the target using Seaborn to determine whether it needs a transformation to facilitate the understanding by the models I will use.

Visualisation de la cible avec Seaborn afin de déterminer si elle doit subir une transformation pour faciliter la compréhension par les modèles que j’utiliserai


3)Assigning the correct data type to each column
Attribution du type de données correct à chaque colonne

4)Creation of feature engineering based on redundancies between them and their importance relative to the target
Création des features engineering en se basant sur les redondances entre elles et leur importance par rapport à la cible

5)Application of appropriate transformations on the columns that help predict the target, after determining whether a column is symmetric or not
Application de transformations appropriées sur les colonnes qui aident à prédire la cible, après avoir déterminé si une colonne était symétrique ou non

6)Specific encoding: using ordinal encoding for columns where the order matters, followed by one-hot encoding for columns with few categories, and finally a target encoding split by KFold for columns with many categories, all while avoiding data leakage
Encodage spécifique : en utilisant un encodage ordinal pour les colonnes dont l’ordre compte, suivi d’un one-hot encoding pour les colonnes ayant peu de catégories, et enfin un target encoding coupé par un KFold pour les colonnes ayant beaucoup de catégories, tout en évitant la fuite de données

7)Use of Optuna to find the parameters that will generalize the best for the models I will choose
Utilisation d’Optuna pour trouver les paramètres qui généraliseront le mieux les modèles que je choisirai
8)Training of the models and calculation of the metric locally, followed by a model ensemble based on the results of cross-validation and performed tests
Entraînement des modèles et calcul de la métrique en local, suivi d’un assemblage de modèles basé sur les résultats de la cross-validation et des tests effectués

#The all code is the   Untitled-1.ipynb file
#Mon code en entier se trouve dans le fichier nommé Untitled-1.ipynb







