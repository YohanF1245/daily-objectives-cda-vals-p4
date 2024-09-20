# Objectifs journaliers

### Vendredi 20/09/2024 :

- [ ] Rattrapage de la semaine / Finalisation des daily objectives de la semaine / Travailler sur les notions mal comprises

### Git

- [x] Comprendre le principe de "Pull Request"
    * Le pull request est un principe qui va au *delà de la demande de fusion de code*. Il permet de 
      1. d'avoir une relecture par ses pairs du code proposé
      2. de discuter de potentielles améliorations du code
      3. détécter s'il comporte des erreurs
- [x] Comprendre le rebase dans Git (quelle différence avec le merge ?)
      Le rebase va réunir deux branches, en recopiant les commit d'une branche sur la branche principale.
      L'interet est de garder un historique des commits propre et linéaire
      La différence avec le merge est que le merge créé un nouveau commit qui réuni les deux branches
      et préserve l'historique des deux branches.
- [x] Ajouter ce repo en upstream dans les remotes sur son local après l'avoir forké et cloné
- [x] Comprendre l'utilité et le fonctionnement de `git stash`
      -permet de stocker les modifications non commit si l'on doit changer de branche. \
      1. Mettre les modifications de côté :\
      ```git stash```\
      2. Basculer sur une autre branche, faire vos changements et les commiter :\
      ```git checkout autre_branche ```\
      ```git commit -m "Correction du bug"```\
      3. Revenir sur votre branche de travail et récupérer vos modifications :\
      ```git checkout ma_branche```\
      ```git stash pop```\
- [ ] Créer un cheat sheet sur Git (en groupe en respectant les bests practices et Gitflow)
- [x] Découverte de LazyGit
  - [x] Installation et configuration
  - [x] Intégration dans son editeur / workflow
  - [x] Faire le tour du propriétaire
- [x] `.gitignore` global ou pas ?
    *Les deux en fait. Pour comprendre les differences:\
      1. **<ins>Local</ins>** .gitignore : spécifique à un projet, versionné, partagé entre tous les contributeurs.\
      2. **<ins>Global</ins>** .gitignore : spécifique à l'utilisateur, s'applique à tous les dépôts sur une machine, non versionné.
- [x] Comprendre quelle est la différence entre `git pull` et `git fetch`\
    La différence entre `git pull` et git `fetch` est que le pull fait plus de choses que le fetch.\
    Un git fetch ne recupere que les commits et les objets git du dépot distant sans modifier le working directory. Il faut ensuite utiliser un rebase ou un merge pour avoir le depot completment "a jour"\
    Un git pull fait le travaille de git fetch en l'additionnant avec un git merge
  - [ ] À quoi sert la commande `git fetch —prune`
  - [ ] Comment configurer mon git pour que ce soit fait automatiquement ?
- [ ] Configurer son git :
  - [ ] Editeur
  - [ ] Différenciateur (par ex : Delta)
  - [ ] Aliases
  - [ ] Comprendre la différence entre config locale, globale et système

### IA

- [ ] Découvrir le prompt engineering sur ChatGPT (https://learnprompting.org/fr/)
- [ ] Partager ses trucs et astuces sur l'utilisation des IAs