# Optimisation du Dimensionnement de Stockage Embarqué dans un Tramway 

## Description du Projet

Ce projet vise à optimiser le dimensionnement du système de stockage embarqué (batterie) pour un tramway, en prenant en compte les contraintes énergétiques et les besoins de puissance. Le but est de minimiser la capacité de la batterie pour réduire les coûts et le poids, tout en garantissant une alimentation stable et fiable pour le tramway.

Le projet inclut les aspects suivants :

* Modélisation sans batterie (évaluation des besoins en puissance).
* Modélisation avec batterie (gestion de l'énergie de freinage et d'accélération).
* Résolution du problème d'optimisation bi-objectif à l'aide des méthodes Monte Carlo et NSGA-II.


## Fonctionnalités Principales

* **Modélisation sans batterie :** Calcul des tensions et courants en l'absence de batterie.
* **Modélisation avec batterie :** Gestion des flux de puissance entre la batterie, les sous-stations et le train.
* **Optimisation bi-objectif :** Minimisation de la capacité de la batterie et des chutes de tension.

## Utilisation du Notebook

Le notebook **projet\_opt.ipynb** est conçu pour explorer rapidement les résultats du projet. Il inclut :

* Calcul des forces motrices et résistives.
* Simulation de la consommation énergétique du tramway.
* Visualisation des résultats avec des graphiques interactifs.


