# Deep_Learning_ENSAE_2022

Ce github repository contient une implémentation de l'article de Y. Song et al. : [Score-based generative modeling through stochastic differential equations](https://arxiv.org/abs/2011.13456), 2020. Cette implémentation reprend le code des auteurs dont les notebooks sont disponibles [ici](https://yang-song.github.io/blog/2021/score/). Nous l’avons appliquée à la base de données [Cars](https://ai.stanford.edu/~jkrause/cars/car_dataset.html), qui recense plus de 16 000 images de voitures. Notre objectif est de générer des images de voitures de taille 60x60 px en noir et blanc.

Notre repository contient les fichiers suivants :
- un pdf qui résume l'article de base, ainsi que le travail que nous avons fourni dans le cadre du projet.
- le notebook qui implémente les méthodes de l'article sur la base de données Cars.
- des fichiers checkpoints qui stockent les paramètres de notre modèle pour générer des images en taille 60x60 px.
- un dossier qui contient des fichiers checkpoints, qui sont ceux obtenus lors de la phase de grid-search.

Auteurs : Rémi VIDAL et Yann DE COSTER.
