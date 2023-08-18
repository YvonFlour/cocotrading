# Ceci est un projet de machine learning pour l'apprentissage automatique des paternes sur le marché des prix (trading/forex) et puis sur la prédiction des prix futures,

Nous allons évoluer dans le projet avec différentes versions selon les différentes hypothèses que nous allons formuler sur le problème.

Mais avant de commencer, nous allons poser quelques prérequis technique et préparation.

# 1. Le stockage des données
Pour le stockage, nous allons utiliser une base de données Postgres, avec un autre container qui fera tourner une image de pgAdmin qui nous permettra de visualiser les données facilement sur une navigateur web.

# 2. Les données 
Nous ne pouvons pas travailler sur un projet d'apprentissage sans les données qui seront utilisées pour entrainer nos modèles.

### *Histique du Marché*
La première étape consiste à avoir un historique du marché qui va etre utiliser pour les différentes transformations et apprentissage des modèles.

Pour ça, nous allons télécharger les données dépuis un site : 
- https://data.eatradingacademy.com/
