# Gestionnaire de Carnet d’Adresses CLI

## Description

Ce projet est une application PHP en ligne de commande permettant de gérer un carnet d’adresses.

L’utilisateur peut interagir avec le programme via le terminal pour :

* afficher la liste des contacts ;
* afficher le détail d’un contact ;
* créer un contact ;
* supprimer un contact ;
* afficher l’aide ;
* quitter l’application.

Ce projet a été réalisé en programmation orientée objet avec PHP et utilise une base de données MySQL via PDO.

---

## Technologies utilisées

* PHP (CLI)
* MySQL / MariaDB
* PDO
* Programmation Orientée Objet

---

## Structure du projet

* **main.php** : point d’entrée du programme
* **DBConnect.php** : gestion de la connexion à la base de données
* **Contact.php** : représentation d’un contact
* **ContactManager.php** : gestion des opérations CRUD
* **Command.php** : gestion des commandes utilisateur

---

## Installation

1. Créer la base de données MySQL
2. Importer la table `contact`
3. Configurer les identifiants de connexion dans `DBConnect.php`
4. Lancer le programme :

```bash
php main.php
```

---

## Commandes disponibles

* `help` → affiche l’aide
* `list` → affiche tous les contacts
* `detail [id]` → affiche un contact
* `create [name], [email], [phone]` → crée un contact
* `delete [id]` → supprime un contact
* `quit` → quitte le programme

---

## Objectif pédagogique

Ce projet permet de pratiquer :

* la programmation orientée objet ;
* la manipulation de bases de données avec PDO ;
* l’utilisation de PHP en ligne de commande ;
* l’organisation d’un projet en classes.
