# serveur-apache-rhel
installation et configuration d'un serveur Apache sur RHEL

# Mon Premier Site Web

## Description

Ce projet consiste en la création d'un site web simple hébergé sur un serveur Apache sur un système Red Hat Enterprise Linux (RHEL). Ce site présente des informations personnelles et test de fonctionnement d'Apache (avec du HTML) . Ce projet a été réalisé dans le cadre de mon apprentissage en administration système et cybersécurité.

## Objectifs

- Configurer un serveur Apache sur un système RHEL.
- Créer un site web simple en utilisant HTML 
- Apprendre à manipuler des fichiers web dans un environnement de serveur.
- Utiliser GitHub pour gérer et partager le code source.

## Technologies Utilisées

- **Serveur web**: Apache HTTP Server
- **Système d'exploitation**: Red Hat Enterprise Linux (RHEL)
- **Langages de programmation**: HTML
- **Gestion de version**: GitHub

## Installation

### 1. Installation d'Apache

```bash
sudo yum install httpd

### 2. Démarrer le serveur Apache

```bash

sudo systemctl start httpd

### 3. Placer le fichier index.html
Copiez votre fichier index.html dans le répertoire /var/www/html.

```bash

sudo cp index.html /var/www/html/

### 4. Vérification
Allez sur votre navigateur et entrez l'adresse IP de votre serveur pour vérifier si le site fonctionne correctement :

http://<adresse-ip-de-votre-serveur>
