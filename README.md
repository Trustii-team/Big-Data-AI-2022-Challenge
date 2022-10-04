![trustii logo](/HeroImage.png)

Vous trouverez sur ce repo les notebooks des meilleurs candidats du data challenge Big Data AI Paris 2022.

Ce challenge a été organisé en collaboration avec Big Data AI Paris 2022  (https://www.bigdataparis.com) et MyDataModels (https://www.mydatamodels.com), hosté par la plateforme trustii.io (https://www.trustii.io)

# Contexte de ce data challenge

Dans le cadre du salon Big Data AI Paris 2022, Trustii.io a proposé un Data Challenge en collaboration avec MyDataModels, qui vise à explorer des algorithmes de machine learning pour prédire le Coût d'une Assurance Santé.

La prévision des dépenses de santé des consommateurs est devenue une technique importante pour renforcer la responsabilité des soins de santé. Afin de hiérarchiser l'allocation de leurs ressources limitées de gestion des soins et de préparer l'avenir, les assureurs-maladie et les organismes de prestation de soins de santé peuvent bénéficier d'estimations de coûts précises. De plus, être conscient de leurs coûts futurs prévus pourrait aider les patients à sélectionner des régimes d'assurance avec les franchises et les tarifs appropriés.

Dans ce défi, nous avons voulu repousser les limites des méthodes d'apprentissage automatique supervisé pour créer un modèle qui prédit le coût d'une assurance santé sur la base d'un ensemble de données ouvert.

# Source des datasets :
* Article de recherche "A Computational Intelligence Approach for Predicting Medical Insurance Cost" : https://downloads.hindawi.com/journals/mpe/2021/1162553.pdf
* Dataset Kaggle : https://www.kaggle.com/datasets/mirichoi0218/insurance?datasetId=13720&sortBy=voteCount&select=insurance.csv&search=dataset


# Résultats 

Pendant 7 jours, il y a eu 102 participants et 884 prédictions soumises, plusieurs participants ont participé en équipe.

Les participants sont des étudiants issus des universités et écoles, chercheurs, et professionnels en data science, en France et à l'étranger.

La meilleure équipe a construit un modéle qui a eu un score de 0.8599 "R2" (calculé à partir d'un dataset de validation)

le leaderboard complet est disponible sur https://app.trustii.io (section data scientist)

# Jupterhub Trustii.io :
Trustii.io a fournit gratuitement à chaque concurrent un environnement Jupyter Notebook géré, doté de 4 vCPU, 16 Go de RAM et de 20 Go de stockage.

# AutoML de MyDataModels :
Dans le cadre de ce challenge MyDataModels a fournit un modèle autoML comme baseline, ainsi que le pipeline de celui ci dans l'environnement Jupyterhub.


# Évaluation :
L'évaluation des modèles a été basée sur le classement dans le leaderboard privé en utilisant le score R2 et la qualité du code source de du modèle (vérifié par l'équipe Trustii.io).

