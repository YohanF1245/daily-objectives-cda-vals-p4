# Objectifs journaliers

## Lundi 04/11/2024 :

### SQL - Data Query Language (DQL)

- [x] Structure d'une requête SELECT
  - [x] Savoir écrire une requête SELECT de base
  SELECT * FROM table;
  - [x] Savoir sélectionner des colonnes spécifiques
  SELECT nom_colonne FROM nom_table
  - [x] Savoir utiliser les alias avec AS
    SELET * FROM nom_table as T where t.nom_champ = "xxxx"
  - [x] Savoir utiliser la sélection complète (*)
    SELECT * FROM nom_table

- [x] Filtrage des données
  - [x] Savoir utiliser la clause WHERE
    - [x] Savoir utiliser les opérateurs de comparaison
    - [x] Savoir utiliser les opérateurs logiques
    - [x] Savoir utiliser BETWEEN
    - [x] Savoir utiliser IN
    - [x] Savoir utiliser LIKE et ses wildcards
    - [x] Savoir gérer les NULL

- [x] Organisation des résultats
  - [x] Savoir trier avec ORDER BY
    - [x] ASC / DESC
    - [x] Tri multi-colonnes
  
  - [x] Savoir utiliser DISTINCT
    éviter les doublons
  - [x] Savoir utiliser LIMIT et OFFSET