# Prédiction des Résultats des Élections Législatives Françaises (À vous de jouer)
Version brouillon : Union Populaire (27,6 %), Bloc Centriste (21,3 %), Bloc de Droite (5 %), Bloc d'Extrême Droite (46,1 %).
- Nota bene : Durant les phases d'entraînement et de test, le modèle identifie correctement le bloc gagnant dans chaque circonscription à hauteur de 85 % et 70 % respectivement.


Version propre : Union Populaire (27.972%), Bloc Centriste (45.979%) Bloc de Droite (13.986%), Bloc d'Extrême Droite (12.062%).
- Resultats un peu décevant vis-à-vis des récents sondages, il faudrait mieux selectionner les variables et ajouter des variables économiques, sociales et spatiales

Version propre 2 : Union Populaire (25.174%), Bloc Centriste (45.104%) Bloc de Droite (6.8181%), Bloc d'Extrême Droite (22.902).
- Résultats un peu plus réalistes pour les blocs UP et ED que le précédent, néanmoins toujours un problème avec une forte proportion des circonscriptions gagnées par le centre alors que les sondages montrent des intentions de vote un peu plus que 2 fois inférieures.


## Contexte
Ce projet a été développé dans le contexte de la dissolution anticipée de l'Assemblée nationale française suivant les élections européennes de 2024. Le but est de prédire les résultats des élections législatives anticipées à partir des données des scrutins précédents, y compris les élections européennes, présidentielles et législatives précédentes.

## Objectifs
L'objectif principal est de créer un modèle prédictif capable d'estimer les issues potentielles des élections législatives en fonction des tendances et résultats électoraux passés. Cette analyse vise à fournir des insights sur les dynamiques politiques et les changements potentiels dans le paysage politique français.

## Méthodologie
### Données : 
Les données utilisées pour développer ce modèle proviennent des résultats de scrutins antérieurs disponibles sur la plateforme www.data.gouv.fr. Cette source officielle regroupe les issues des élections européennes, présidentielles, et législatives précédentes, offrant une base de données complète pour l'analyse prédictive des tendances électorales en France.
### Traitement et Nettoyage des Données : 
Avant toute analyse, les données sont traitées et nettoyées en utilisant Excel pour garantir la qualité et la précision des données entrantes.
### Exploration et Visualisation : 
Une fois nettoyées, les données sont explorées et visualisées à l'aide des bibliothèques Python telles que numpy et pandas pour la manipulation des données, et matplotlib ainsi que seaborn pour la visualisation graphique. Cette étape permet de comprendre les tendances et les patterns qui émergent des données historiques.
### Modélisation : 
Les modèles de régression logistique et d'arbres de décision aléatoires (Random Forest) de la bibliothèque sklearn sont utilisés pour construire les modèles prédictifs. Le choix de ces modèles est dû à leur efficacité dans la gestion des classifications et de leurs capacités à traiter des caractéristiques non-linéaires.
Résultats
Les modèles développés permettent d'estimer quel groupe politique est susceptible d'être élu dans chaque circonscription. Cette analyse prédictive fournit des prévisions précieuses sur la répartition des sièges à l'Assemblée nationale, basées sur les performances historiques des partis dans les scrutins précédents. Ces résultats sont essentiels pour anticiper les dynamiques politiques futures et pour évaluer les impacts potentiels des tendances électorales sur la politique française.

## Conclusion
Ce projet souligne l'importance et les défis liés à la prédiction des résultats électoraux dans un contexte politique en constante évolution. Bien que les insights générés par ce modèle soient déjà d'une grande utilité pour les analystes politiques, les partis politiques, et les électeurs, en améliorant la compréhension des changements potentiels à l'Assemblée nationale, cette approche pourrait être enrichie par l'intégration de données socioéconomiques et l'utilisation d'un système d'information géographique (SIG). Cela permettrait une meilleure appréhension de la dynamique spatiale et enrichirait l'analyse des facteurs influençant les résultats électoraux à travers les différentes régions.

## Technologies Utilisées
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
