Semaine 2 : Back to back-end
===

![center](/back.jpeg)

<h2>Lundi</h2>

**Veille sur Sql & SgbdR**

**Exercice 5 : Réalisation d'une Bdd + Requetes Sql**

5.1 Install du sgbd Mysql

5.2 Réaliser un script consistant à créer la BDD "ecom" par ex

5.3 Ajouter une table T_Products contenant : Id(Clé primaire), Name, Brand, Price, Quantity

5.4 Ajouter des produits d'abord via le script puis en ligne de commande

5.5 Afficher votre table des produits

5.6 Ne préciser pas l'id en ajoutant un produit, que se passe-t-il ?

5.7 Ne préciser pas le prix et la quantité, qu'observez-vous ? comment résoudre ces pb ?

5.8 Afficher uniquement les noms et marques de tous les produits

5.9 Changer les informations d'un ou plusieurs produits puis vérifier si cela a été pris en compte

5.10 Afficher tous les produits classés par prix du moins cher au plus cher

5.11 Afficher les 2 produits les plus chers

5.12 Afficher les produits de même marque (choisissez un produit adapté ici)

5.13 Supprimer un produit et vérifier, puis supprimer tous les produits et vérifier

**Exercice 6 : Clé primaire, étrangère, jointure**

*Nous souhaitons dorénavant gérer des catégories de produits (Pc, SmartPhone, Tablette)*

6.1 Sachant qu'un produit peut appartenir qu'à une seule catégorie et qu'une catégorie concerne plusieurs produits, apporter les modifications nécessaires respectant le schéma suivant :

- T_Products   : Id(Clé primaire), Name, Brand, Price, Quantity, IdCategorie(clé étrangère)

- T_Categories : Id(Clé primaire), Name, Description

6.2 Ajouter à T_Categories, les 3 catégories Ordinateur, SmartPhone, Tablette par ex puis afficher les

6.3 Ajouter plusieurs produits par catégories puis afficher tous les produits

6.4 Afficher tous les produits d'une catégorie, tester avec chacune

6.5 Nous souhaitons la liste des noms des produits + noms des catégories associées + price le tout classé du moins cher au plus cher

<h2>Mardi</h2>

**Veille sur NodeJs, ExpressJs et BodyParser**

**Veille sur Api Rest**

**Exercice 7 : prise en main de NodeJS**

7.1 Démarrer votre serveur puis tester le en affichant un message de bienvenu

7.2 Récupérer le nom de l'utilisateur (toto) en paramètre de l'url pour afficher : "Welcome toto" (Utiliser http, url, queryString)

7.3 A l'aide d'express, mettre en oeuvre une route par défaut qui affiche : "hello express" par ex

7.4 Ajouter une route qui récupère une valeur en paramètre tel un code et affiche votre nom + email + code

7.5 Configurer le debugger de VSC puis tester en ajoutant des points d'arrêt

**Appli fil rouge : étape 3/api**

- Mise en oeuvre d'un serveur

- Mise en oeuvre des routes correspondants aux services web :
      
      -> ajouter produit
      -> liste des produits
      -> retrouver un produit par son id
      -> mettre à jour un produit
      -> supprimer un produit
      -> supprimer tous les produits

- Mise en ouvre d'un controller

- Mise en oeuvre d'un model

- Mise en oeuvre de la connection à la bdd à l'aide d'un fichier de config

<h2>Mercredi</h2>

**Veille sur Http**

**Install d'un client Rest et test de l'api sur toutes les fonctionnalités (CRUD)**

- Ajouter un produit (Create)

- Renvoyer liste des produits (Read All)

- Retrouver un produit par son Id (Read One)

- Mettre à jour d'un produit (Update)

- Supprimer un produit (Delete One)

- Supprimer tous les produits (Delete All)

**Mercredi après midi**

Internet of things avec Aurelien

<h2>Jeudi</h2>

**Veille sur Ajax**

**Appli fil rouge : étape 4/fullstack**

Il s'agit ici de faire les appels à partir du front sur l'api côté back afin de récuperer les données en base et les afficher sur notre page web conformément aux besoins

<h2>Vendredi</h2>

**Veille sur Bootstrap/jQuery**

**MasterClass Laurent : Numérique responsable**

**Appli fil rouge : étape 5/prod**

Une fois que votre appli est fonctionnelle, vous pourrez apporter un confort visuel et ergonomique à l'aide de bootstrap et jQuery

*Contrainte : votre site doit tenir sur une seule page html (single page application)*

**Bonus**

- Ajouter une barre de navigation

- Afficher la liste des catégories

- En cliquant sur une catégorie, afficher uniquement les produits de la catégorie cliqué puis gérer une commande en conséquence

- Passer une commande doit être précédé par le remplissage d'un formulaire + validation côté back 

- Comment éviter les attaques par injection...

- Deployer votre appli

Ressources
===

[Cours et Tutoriels sur le Langage SQL](https://sql.sh/)

[Node.js](https://nodejs.org/en/)

[npm \| build amazing things](https://www.npmjs.com/)

[Express - Infrastructure d'application Web Node.js](https://expressjs.com/fr/)

[Tutoriel Vidéo REST](https://www.grafikart.fr/tutoriels/rest-503)

[Build Node.js Rest APIs with Express & MySQL - BezKoder](https://bezkoder.com/node-js-rest-api-express-mysql/)

[Les meilleurs cours et tutoriels pour apprendre l'AJAX](https://ajax.developpez.com/cours/)

[Tutoriel Vidéo Fetch](https://www.grafikart.fr/tutoriels/fetch-1017)

[2020's Bootstrap Tutorial for Beginners (Step-by-Step) \| websitesetup.org](https://websitesetup.org/bootstrap-tutorial-for-beginners/)
