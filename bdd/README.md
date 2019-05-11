# Les bases de données en Python 

## Introduction 
Une base de données est un conteneur dans lequel il est possible de stocker des données de façon structurée. Cette structure permet au programme informatique connectée à celle-ci de faire des recherches complexes. Ce que nous allons voir dans ce TP. 

Les logiciels de gestion de bases de données les plus utilisées aujourd'hui sont des *SGBDR, Système de gestion de base de données relationnelles*, c'est à dire que les données sont liées les unes aux autres. C'est l'objet de notre TP avec le module SQLite3 de python.

## Les bases de données relationnelles 
Une base de données relationnelle est une base de données où l'information est organisée dans des tableaux à deux dimensions appelés des relations ou tables. La plus part des systèmes relationnels utilisent le langage SQL pour interroger les bases de données. Ce langage permet de demander des opérations d'algèbre relationnelle telles que l'intersection, la sélection et la jointure.

### SQLite 
Afin de pratiquer le SQL, notre premier exemple concernera le module python SQLite. SQLite a été conçu pour être intégré dans le programme même. **Voir le repo SQLite et le notebook `BDD.ipynb` et faire le TP à la fin du notebook**. 

**Attention, il ne faut pas confondre une base de données qui est un conteneur et le SGBDR qui est un logiciel de gestion de bases de données.** 


## NoSQL
Il existe un **autre type de SGBD: les NoSQL, pour Not Only SQL** où la structure n'est plus pensée en tables. Ces SGBD permettent de travailler avec d'énormes données, sont utilisés par Google , Amazon , Ubuntu, etc. Dans ce type de système, pour augmenter les performances il faut augmenter le nombre de serveurs.

### PyMongo 
PyMongo est une distribution Python contenant des outils permettant de travailler avec [MongoDB](https://fr.wikipedia.org/wiki/MongoDB) pour la gestion de BDD orientées documents. **Voir le repo PyMongo et les notebook `PyMongoQuickStart.ipynb` et `PyMongoTP.ipynb`**

