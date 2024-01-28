# Projet ESB Talend - Architecture de Services
## Description
Ce projet implémente une solution d'intégration de données basée sur Talend ESB. Il comprend trois flux principaux pour la gestion des données utilisateur :

- Flux CSV : Intègre les données des utilisateurs depuis des fichiers CSV vers la base de données PostgreSQL.
- API REST POST : Permet l'intégration des données utilisateur via une API REST en utilisant des requêtes POST avec des données au format JSON.
- Service Web SOAP : Permet la consultation des données utilisateur dans la base de données à travers une API SOAP, permettant de récupérer les informations des utilisateurs par ID ou nom.
  
## Schéma de la Base de Données
La base de données Users contient une table User avec les champs suivants :

- Id (Integer, Clé Primaire)
- Nom (varchar)
- Prenom (varchar)
- login (varchar)
- password (varchar)

## Configuration
Avant de déployer le projet, assurez-vous de configurer correctement votre SGBD PostgreSQL et de créer le schéma de la base de données en accord avec le schéma ci-dessus.

