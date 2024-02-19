# Databricks Accidents Project

## Présentation du Projet
Ce projet vise à analyser les données sur les accidents de la route pour construire et héberger un modèle prédictif utilisant Azure Databricks. L'objectif est de prédire la gravité des accidents avec une précision élevée, en utilisant des techniques de machine learning avancées.

## Sources des Données
Les données utilisées pour ce projet proviennent de la base de données publique sur les accidents de la route, analysée et décrite dans le tutoriel d'Ilyes Talbi de la revue IA. Ce tutoriel offre un aperçu détaillé des étapes de prétraitement et de modélisation appliquées aux données pour prévoir la gravité des accidents.

Lien vers le tutoriel: https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/

## Éléments du Repository
Ce repository contient les éléments suivants :

* Modelisation.dbc : Un notebook Databricks qui décrit tout le processus de modélisation, incluant le prétraitement des données, la construction des modèles de machine learning, et l'optimisation des paramètres.
* Test API.dbc : Un notebook Databricks qui montre comment consommer l'API du modèle pour tester des prédictions sur de nouveaux exemples d'accidents.

Liens EndPoint du modèle : https://adb-8677599887369280.0.azuredatabricks.net/serving-endpoints/accidents-endpoint/invocations

