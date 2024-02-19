# Databricks-Accidents-Project

Résumé du Projet
Projet : Il s'agit de la prédiction de la gravité des accidents de la route en France.
Sources des Données :
Les données utilisées dans ce projet ont été fournies par Ilyes Talbi et comprennent des informations sur les caractéristiques des accidents de la route en France. Les données sont issues de plusieurs sources, y compris les caractéristiques des véhicules, les circonstances des accidents, les informations sur les lieux, et les données sur les victimes.

Éléments du Répertoire
Notebook : Ce notebook contient le code Python utilisé pour explorer, prétraiter les données, entraîner les modèles de prédiction et évaluer leurs performances.

Fichiers CSV : Les fichiers CSV contenant les données brutes utilisées dans le projet sont également inclus dans le répertoire.

MLflow Tracking : Les informations sur les différents modèles entraînés et leurs performances sont suivies à l'aide de MLflow, ce qui permet une gestion efficace des expériences et des modèles.

Modèle Retenu et Performances
Le modèle retenu pour prédire la gravité des accidents de la route est un RandomForestClassifier. Le modèle a été entraîné en utilisant les caractéristiques telles que la présence de voies spéciales, le type de plan de circulation, etc. Les performances du modèle sont les suivantes :

Accuracy : 0.65
F1-score : 0.63
Le modèle a été évalué en utilisant un ensemble de test distinct pour évaluer sa capacité à généraliser à de nouvelles données.

Lien de l'Endpoint du Modèle
L'endpoint du modèle est accessible via le lien suivant : marche pas



