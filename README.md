# Projet Microservices pour la Gestion de Clients et Voitures 

## Introduction

Ce projet est une application basée sur des microservices pour la gestion des clients et des voitures. Une passerelle (gateway) est utilisée pour orchestrer les requêtes entre les microservices. Chaque microservice a sa propre base de données dédiée pour gérer les informations spécifiques.

## Microservices

### Microservice Client

Le microservice Client gère les informations relatives aux clients.

#### Technologies utilisées

- **Spring Boot**: Utilisé pour le développement du microservice.
- **MySQL**: Base de données relationnelle pour stocker les informations des clients.
- **Hibernate**: Utilisé pour la couche de persistance des données.

#### Microservice Voiture
Le microservice Voiture gère les informations relatives aux voitures.

#### Technologies utilisées
- ***Spring Boot** : Utilisé pour le développement du microservice.
- ***MySQL**: Base de données relationnelle pour stocker les informations sur les voitures.
- ***Hibernate**: Utilisé pour la couche de persistance des données.
### Fonctionnalités
**Microservice Client**

Création, mise à jour et suppression de clients.

Récupération des informations d'un client spécifique.

**Microservice Voiture**

Création, mise à jour et suppression de voitures.

Récupération des voitures d'un client spécifique.

### Comment exécuter le projet
1-Cloner le référentiel depuis GitHub.
2-Configurer les bases de données dans les fichiers application.yml de chaque microservice.
3-Exécuter les microservices et la getway en utilisant votre IDE ou la ligne de commande.
