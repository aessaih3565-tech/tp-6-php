TP PHP – Initiation à PHP et MySQL

1. Présentation du TP

Ce TP a pour objectif de découvrir progressivement le langage PHP côté serveur et de comprendre son utilisation avec HTML et MySQL.

À travers les différentes activités, nous allons apprendre à utiliser les paramètres GET et POST, manipuler des formulaires, effectuer des traitements avec PHP et établir une connexion à une base de données MySQL en utilisant PDO.

2. Environnement de travail

Les outils utilisés :

XAMPP (Apache et MySQL)

PHP

HTML

MySQL

phpMyAdmin

Visual Studio Code

3. Structure du projet

tp-php/
│
├── database/
│   ├── 06-connexion.php
│   ├── 07-select.php
│   └── database.sql
│
├── 01-hello.php
├── 02-php-html.php
├── 03-get.php
├── 04-post.php
├── 05-formulaire.php
│
├── captures/
│


4. Réalisation des activités

Activité 1 : Premier script PHP

Fichier : 01-hello.php

Dans cette activité, nous avons découvert les premières instructions PHP en utilisant echo.

Travail réalisé :

Affichage de plusieurs messages.

Ajout du prénom.

Affichage de la date avec date("d/m/Y").

Affichage de l'heure du serveur.





Activité 2 : PHP et HTML

Fichier : 02-php-html.php

Cette activité consiste à utiliser les variables PHP dans une page HTML.

Travail réalisé :

Déclaration des variables $nom, $age et $ville.

Affichage des informations dans des paragraphes HTML.

Ajout d'un titre à la page.






Activité 3 : Utilisation de GET

Fichier : 03-get.php

Cette activité permet de récupérer des informations envoyées à travers l'URL avec la méthode GET.

Travail réalisé :

Récupération du nom avec $_GET.

Ajout du paramètre ville.

Affichage des informations reçues.

Exemple de test :

http://localhost/tp-php/03-get.php?nom=Mouad&ville=Marrakech




Activité 4 : Formulaire POST

Fichier : 04-post.php

Dans cette activité, nous avons créé un formulaire HTML et utilisé la méthode POST pour envoyer les informations.

Travail réalisé :

Création des champs du formulaire.

Récupération des données avec $_POST.

Ajout du champ ville.

Affichage des informations après l'envoi.





Activité 5 : Traitement d'un formulaire

Fichier : 05-formulaire.php

Cette activité permet de traiter les informations d'un produit à l'aide de PHP.

Travail réalisé :

Saisie du nom du produit.

Saisie du prix et de la quantité.

Calcul du total :

Total = Prix × Quantité

Ajout du champ catégorie.

Affichage des informations du produit.





5. MySQL et PDO

Activité 6 : Importation de la base de données

Fichier : database/database.sql

Dans cette activité, nous avons utilisé phpMyAdmin pour importer le fichier SQL.

Étapes réalisées :

Démarrage de MySQL dans XAMPP.

Ouverture de phpMyAdmin.

Importation du fichier database.sql.

Vérification de la base de données tp_php.

Vérification de la table products.





Activité 7 : Connexion à MySQL avec PDO

Fichier : database/06-connexion.php

Cette activité consiste à établir une connexion entre PHP et MySQL avec PDO.

Travail réalisé :

Définition du serveur MySQL.

Configuration du nom de la base de données tp_php.

Utilisation de la classe PDO.

Vérification de la connexion.





Activité 8 : Affichage des produits

Fichier : database/07-select.php

Cette activité permet de récupérer les produits enregistrés dans la base de données et de les afficher dans un tableau HTML.

Travail réalisé :

Exécution d'une requête SQL avec SELECT.

Récupération des produits depuis MySQL.

Affichage du nom, du prix et de la quantité.

Calcul du total du stock avec price * quantity.

Filtrage des produits dont le prix est supérieur à 300 DH.




6. Conclusion

Ce TP m'a permis de découvrir les bases du développement web côté serveur avec PHP.

J'ai appris à utiliser les variables, les paramètres GET et POST, les formulaires HTML et les traitements de données.

J'ai également appris à créer une connexion avec une base de données MySQL en utilisant PDO et à afficher les données récupérées dans une page web.

Ce travail représente une première étape dans l'apprentissage de PHP et de la gestion des bases de données.

Projet : TP PHP – Initiation à PHP et MySQL
Année universitaire : 2026/2027
