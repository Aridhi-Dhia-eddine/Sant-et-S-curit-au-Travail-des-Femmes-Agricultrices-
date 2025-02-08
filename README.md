# Santé et Sécurité au Travail des Femmes Agricultrices : Décrypter les Déterminants et Prédire les Risques 
**Description du projet**

Ce projet vise à analyser et à modéliser des données collectées auprès de femmes agricultrices pour mieux comprendre les déterminants de santé et les risques liés à leur activité. En utilisant des techniques d'exploration de données, de prétraitement et de machine learning, l'objectif est de développer un modèle prédictif performant pour anticiper les risques et contribuer à l'amélioration de la prévention et de la sécurité dans ce domaine.

**Objectifs principaux**

🎯 Identifier les principaux déterminants de santé influençant les maladies professionnelles dans le milieu agricole.

🔹 Analyser les corrélations entre les habitudes alimentaires, les conditions de santé et les accidents de travail.

🔧 Développer un modèle prédictif ou des visualisations de données pour anticiper les risques et améliorer la prévention.

**Workflow du projet**

**1. Importation et préparation des données**

Suppression des colonnes inutiles (ex. informations personnelles comme les numéros de téléphone).

Remplacement des valeurs manquantes pour les variables numériques. (Veuillez consulter le fichier "prétraitement de la dataset.ipynb")

**2. Analyse exploratoire des données (EDA)**

Visualisation de la distribution des variables numériques.
![image](https://github.com/user-attachments/assets/6e9c3223-4cfd-4aea-8bdb-21ac502e14c1)

Analyse des outliers avec des boîtes à moustaches.
![image](https://github.com/user-attachments/assets/a514ec84-b1ee-4ac0-8012-4a4ff481550b)

Étude de la corrélation entre les différentes variables (matrice de corrélation).
![image](https://github.com/user-attachments/assets/1bb3ff5a-c304-46b1-a8cf-cd721398afb3)


Répartition de la variable cible : Étude des accidents de travail (« AT en milieu agricole »).
(Veuillez consulter le fichier "implémentation de modèle et application sur dataset.ipynb")

**4. Entraînement d'un modèle de classification**

Utilisation d'un Random Forest Classifier pour construire un modèle robuste.

Évaluation du modèle sur un ensemble de test via des métriques comme :

Matrice de confusion.

Courbe ROC et score AUC.

Validation croisée (5-fold CV).

**6. Sauvegarde du modèle**

Le modèle final est sauvegardé sous le format joblib pour un déploiement futur.
