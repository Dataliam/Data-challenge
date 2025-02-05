# Data-challenge
Projet pour le data challenge de l'ens sur le sujet Generali
Ce data challenge s'inscrit dans le cadre de la tarification des assurances non-vie. L'objectif était de prédire la probabilité qu'un bâtiment déclare au moins un sinistre sur une période donnée, en se basant sur ses caractéristiques.

Les participants devaient construire un modèle capable d’ordonner les bâtiments en fonction de leur risque de sinistre. La cible était binaire : 1 si un sinistre était déclaré, 0 sinon. Les données fournies comprenaient des variables catégorielles et numériques décrivant les bâtiments, notamment leur superficie, leur durée d’assurance et des caractéristiques anonymisées. L’enrichissement des données était encouragé, en intégrant des informations externes comme les conditions météorologiques ou le taux de chômage par zone géographique.

L’évaluation des modèles se faisait via le Normalized Gini Coefficient, une métrique permettant de mesurer la capacité du modèle à hiérarchiser correctement les bâtiments selon leur risque. Un benchmark rapide avec XGBoost a obtenu un score de 0.41, mettant en évidence l'importance de variables comme la superficie, la durée d’assurance et certaines caractéristiques catégorielles.

Ce challenge a offert une mise en pratique concrète des techniques de modélisation prédictive, de feature engineering et de machine learning appliqué à la finance et à l’assurance.
