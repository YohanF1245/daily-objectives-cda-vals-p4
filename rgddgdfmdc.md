# Activité 2 : Règles de Gestion, DD, GDF et MCD
Chaque département de l'Université Constantine 2 est identifié par un numéro (unique) et un nom. Il est dirigé par un directeur, identifié par son nom, et par un nombre d'enseignants qui y travaillent.

Un enseignant est identifié par son nom, son prénom et son grade. Il peut enseigner plusieurs modules, mais uniquement dans son département. Un module est caractérisé par un code unique et une désignation. Il peut être enseigné par plusieurs enseignants. Une équipe de recherche est identifiée par un numéro et un thème de recherche. Chaque enseignant doit appartenir à une équipe de recherche. Un projet est identifié par un numéro et une désignation. Chaque équipe peut prendre en charge au moins un projet de recherche.

1. Extraire les règles de gestion

2. Construire le Dictionnaire des Données (DD)

3. Donner le Graphe des Dépendances Fonctionnelles (GDF)

4. Déduire le MCD

### departement
nummero unique  
nom departement

### directeur
nom directeur

### enseignants
nom enseignants
prenom enseignant
grade enseignant

### modules
code unique
designation module

### equipe de recherche
numero equipe
theme recherche

### projet
numero de projet 
désignation projet

# Règles de gestion : 

## Départements
L'université se compose de 1 ou N départements.
Un département est identifié par un numero unique
Un depoartment est identifié par un nom
Un département est dirigé par un directeur
Un dépoartement regroupe 1 ou N enseignants qui y travaillent

## Enseignants
Un enseignant est identifié par un grade
Un enseignant est identifié par un nom
Un enseignant est identifié par un prénom
Un enseignant peut enseigner un ou plusieurs modules
Un enseignant est lié à 1 département
Un enseignant peut enseigner 1 ou N modules
Un enseignant est associé à une équipe de recherche

## Modules
Un module est identifié par un code unique
Un module est caractérisé par une désignation
Un module peut etre enseigné par 1 ou N enseignants

## Equipe de recherche
Une équipe de recherche est identifiée par un numéro
Une équipe de recherche est identifiée par un thème de recherche
Une équipe de recherche est composée de 1 ou N enseignants
Une équipe de recherche prend en charche 1 ou N projets de recherche

## Projet de recherche
Un projet de recherche est identifié par un numéro
Un projet est identifié par une désignation
Un projet est pris en charche par une équipe de recherche





