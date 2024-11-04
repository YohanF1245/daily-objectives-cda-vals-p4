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
    - [ ] Savoir utiliser IN
    - [x] Savoir utiliser LIKE et ses wildcards
    - [ ] Savoir gérer les NULL

- [ ] Organisation des résultats
  - [ ] Savoir trier avec ORDER BY
    - [ ] ASC / DESC
    - [ ] Tri multi-colonnes
  
  - [ ] Savoir utiliser DISTINCT
  - [ ] Savoir utiliser LIMIT et OFFSET