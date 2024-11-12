# Objectifs journaliers

## Mardi 12/11/2024 :

### Introduction à la méthode MERISE et au MCD

- [x] Découverte de MERISE
  - [x] Comprendre l'historique et le contexte <br>
  La méthode Merise est née vers 1978-1979 à la suite d'une vaste consultation lancée en 1977 par le Ministre de l'Industrie Français auprès de plusieurs sociétés de service et de conseil en informatique afin de mettre au point une méthode de conception et de réalisation des systèmes d'information. Les deux sociétés ayant mis au point la méthode merise sont le CTI (Centre Technique d'Informatique) et le CETE (Centre d'Etudes Techniques de l'Equipement).

  différence entre conception systemique et analytique.Avec l'approche systèmique on prend en compte les interactions avefc d'autre domaines ou projets.
  - [x] Identifier les différents niveaux de MERISE<br>
  Le niveau conceptuel, il s'agit du MCD (Modèle Conceptuel des Données)<br>
Le niveau logique, il s'agit du MLD (Modèle Logique des Données)<br>
Le niveau physique, il s'agit du MPD (Modèle Physique des Données)<br>*
niveaux (correction):
|                | données | traitement | communication |
| -------------- | ------- | ---------- | ------------- |
| conceptuel     | MCD     | MCT        | MCC           |
| organisationel | MLD     | MOT        |               |
| technique      | MPD     | MOpT       |               |

  - [ ] Comprendre le vocabulaire de base

- [x] Les concepts de base du MCD
  - [x] Les entités
    - [x] Savoir définir les entités<br>l'entité: elle regroupe l'information statique et durable.
    - [x] Savoir nommer les entités<br>Une entité est représentée par un nom commun écrit en minuscules et au pluriel.
    - [x] Savoir identifier les occurrences<br>Une occurence est une ligne dans une table. Par exemple un utilisateur est une occurence de la table UTILISATEUR.
  
  - [x] Le dictionnaire de données
    - [x] Savoir créer un dictionnaire de données <br>
    | nom du champ | type de données | description | contraintes (pas primary key) | usage et contexte d'utilisation |
    - [x] Savoir définir les propriétés
    - [x] Savoir typer les propriétés
    - [x] Savoir documenter les propriétés
  
  - [ ] Les associations
    - [x] Savoir définir les associations <br>
    verbe a l'infinitif lisible dans les deux sens<br>


    Une association est un lien sémantique entre plusieurs entités
    - [x] Savoir nommer les associations
    Une association est souvent nommée par un verbe qui exprime le sens du lien entre les
entités.
    - [x] Savoir identifier les cardinalités
     nombres minimum et maximum de participations de
chaque occurrence d’entité à l’association.

- [ ] Les règles de gestion
  - [ ] Savoir extraire les règles d'un cahier des charges
  - [ ] Savoir formaliser les règles de gestion
  - [ ] Savoir valider la cohérence des règles
