# Présentation du projet
Pour ce projet, nous avons du suivre les étapes suivantes :
- crée un nouvel environnement sur Azure (resource groups, databricks)
- importer les données des accidents et les convertir en pandas car elle sont au format spark
- faire 3 classifieurs sur ces données afin de prédire l'arrivé d'un accident
Cela nous a donc servis d'évaluer nos compétences sur Azure, sur Github mais aussi en data mining car nous avons réalisé 3 modèles sur les données des accidents.

# les sources des données
Concernant les données, les fichiers étaient les suivants : 
- carac
- lieux
- veh
- vict
Ensuite concerant les clusters et toute la démarche sur Azure, je me suis aidé du tutoriel d'Ilyes Talbi et des cours de data minning que nous avons eu dans notre formation de BUT SD cette année.

# les éléments de votre repository
mon repository comprend 3 fichiers :
- le readme
- le notebook
- le notebook

# le modèle retenu et ses performances
 le meilleur classifieur est celui basé sur le modèle RandomForestClassifier avec un accuracy score à environ 0.63
 
# le lien de l'endpoint du modèle
https://adb-1626033546787848.8.azuredatabricks.net/serving-endpoints/endpoint/invocations
