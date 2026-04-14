# Projet de Data Science : Exploration, Classification, Clustering et Règles d'Association

Ce dépôt contient une série de notebooks Jupyter démontrant l'application de diverses techniques d'analyse de données et d'apprentissage automatique (Machine Learning). Le projet couvre l'ensemble du cycle de vie de la donnée : de l'analyse exploratoire à la modélisation prédictive (supervisée et non supervisée), en passant par la découverte de patterns.

##  Jeux de données (Datasets)

Les analyses s'appuient sur deux jeux de données distincts inclus dans ce dépôt :
* **`Mall_Customers.csv`** : Contient des informations sur les clients d'un centre commercial (Âge, Genre, Revenu annuel, Score de dépense). Ce dataset est principalement utilisé pour les tâches de segmentation client (Clustering) et l'analyse exploratoire.
* **`heart.csv`** : Contient des données médicales de patients (âge, pression artérielle, cholestérol, etc.) et une variable cible indiquant la présence d'une maladie cardiaque. Utilisé pour les tâches de classification supervisée.

##  Contenu des Notebooks

1. **`Analyse exploratoire des données et visualisation avancée.ipynb`**
   * Nettoyage et préparation des données.
   * Analyse statistique descriptive.
   * Visualisations graphiques avancées pour comprendre la distribution des données et les corrélations entre les variables.

2. **`Comparaison des Modèles de Classification Supervisée et Non Supervisée partie1.ipynb`**
   * Focus sur l'apprentissage supervisé avec le dataset `heart.csv`.
   * Entraînement de modèles de classification (ex: Régression Logistique).
   * Évaluation des performances à l'aide de matrices de confusion et d'autres métriques.

3. **`Comparaison des Modèles de Classification Supervisée et Non Supervisée partie.ipynb`**
   * Focus sur l'apprentissage non supervisé avec le dataset `Mall_Customers.csv`.
   * Application d'algorithmes de clustering (notamment l'algorithme **BIRCH**).
   * Visualisation des clusters pour identifier des segments de clients (ex: Revenu vs Score de dépense).

4. **`Découverte de patterns et règles d’association.ipynb`**
   * Application de techniques de fouille de données (Data Mining).
   * Recherche d'itemsets fréquents et extraction de règles d'association pour comprendre les comportements sous-jacents.

##  Technologies et Bibliothèques utilisées

Pour exécuter ces notebooks, vous aurez besoin de l'environnement Python standard pour la Data Science. Les principales bibliothèques utilisées sont :
* `pandas` & `numpy`  (Manipulation des données)
* `matplotlib` & `seaborn`  (Visualisation des données)
* `scikit-learn`  (Modélisation Machine Learning et métriques d'évaluation)
