# Objectifs journaliers

## Mercredi 30/10/2024 :

### Introduction à PostgreSQL et DCL

- [ ] Découverte de PostgreSQL
  - [ ] Identifier les différences entre MySQL et PostgreSQL
    OLAP VS OLTP
    online transaction et analytic processing
    OLTP permet d'interragir avec des entrées précises (expemle transfert d'argent d'un compte a un compte b)
    OLAP interragi avec un grand nombre de donnes (voire toute les entrées) pour les analyser.
    Postgre est plus adapté pour l'OLTP
    Les deux supportent les types de données relationnels, mais postgresql supporte le type de données orienté objet.
    Postgre permet de stocker des objets, des arrays, etc.
    Postgre permet aux utilisateurs de créer leurs plugin en C.
    postgre est mieux pour la sécurité
    - transport level encryption : securise les communication client-server avec ssl/tls.
    - data-at-rest-protection: chiffre les données stockées pour se prémunir des vols de données physique.
    - data-in-use encrytion: sécurisation des données en cours d'utilisation interne (dans la mémoire)
    - rls row-level security: permet d'éditer des règles afin de permettre l'accès a certaines lignes pour un groupe d'utilisateur
    - mysql single-threaded postgre mylti-threaded (mvcc)
    en résumé:
    postgre:
    -plus flexible
    - plus customizable
    - plus sécurisé
    mysql:
    - plus facile et rapide a utiliser
    - moins gourmand en ressource matérielle
  - [x] Savoir Choisir les cas d'usage adaptés à PostgreSQL
    - mysql: petite application web (projet amateur)
    - postgre: grosse application d'entreprise qui va traiter beaucoup de données et avoir des plus gros besoin en sécurité.
    - a noter: qui peut le plus peut le moins, postgre peut etre utilisé dans n'importe quel projet là ou les limitations de mysql l'empechent d'etre utilisé partout.

- [ ] Installation et Configuration
  - [ ] Installation de PostgreSQL sur la machine
  - [ ] Installation de pgAdmin 4
  - [ ] Installation de pgcli
  - [ ] Configuration initiale
    - [ ] Ports
    - [ ] Mot de passe postgres
    - [ ] Création du premier utilisateur
  - [ ] Test de la connexion

- [ ] Data Control Language (DCL)
  - [ ] Gestion des utilisateurs
    - [ ] Savoir construire des requêtes CREATE USER
    - [ ] Savoir modifier des utilisateurs avec ALTER USER
    - [ ] Savoir supprimer des utilisateurs avec DROP USER
    - [ ] Savoir utiliser les rôles PostgreSQL
  
  - [ ] Gestion des droits
    - [ ] Savoir attribuer des privilèges avec GRANT
      - [ ] Droits sur les bases de données
      - [ ] Droits sur les tables
      - [ ] Droits sur les colonnes
    - [ ] Gérer la révocation avec REVOKE
      - [ ] Comment retirer des droits sur une base de données, une table ou une colonne ?
      - [ ] Quel est l'impact d'une révocation en cascade ?

  - [ ] Les bonnes pratiques de sécurité
    - [ ] Comment appliquer le principe du moindre privilège dans PostgreSQL ?
    - [ ] Quand utiliser des rôles plutôt que des utilisateurs individuels ?
    - [ ] Comment auditer efficacement les droits d'accès ?