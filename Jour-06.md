# Objectifs journaliers

## Lundi 23/09/2021 :

### Git

- [x] Comprendre le fonctionnement des références et pointeurs dans Git
Les **références** sont des noms ou identifiants qui désigne un endroit de l'historique des commit.
Exemple:
- Nom de la branche
- Tag
- HEAD
- Origin / upstream / local
En somme c'est un moyen de se situer dans les commits
Les pointeurs dans Git sont des mécanismes qui permettent de suivre les commits spécifiques dans l’historique du projet. Ils jouent un rôle essentiel pour indiquer l'endroit où Git doit faire des modifications ou vers quel commit il doit se référer. Voici un examen détaillé des pointeurs dans Git :
**Exemple:**
Le HEAD (la tête) désigne le dernier commit d'une branche
- [x] Comprendre le merge dans Git
Le merge en Git fusionne deux branches et crée un commit de merge dans l'historique, regroupant les modifications sans altérer les commits précédents. Cela préserve l'historique des deux branches.
- [x] Comprendre le rebase dans Git (quelle différence avec le merge ?)
  - [x] Savoir utiliser le `git rebase`
Le rebase en Git déplace les commits d'une branche sur une autre en réécrivant l'historique. Contrairement au merge, il crée un historique linéaire, mais modifie les commits précédents pour refléter cette nouvelle base.
- [x] Comprendre la différence entre `git reset` et `git revert`
Le git revert annule un commit spécifique en créant un nouveau commit inverse, sans modifier l'historique existant. Contrairement à git reset, il préserve tous les commits précédents, maintenant ainsi un historique intact. Git reset deplace le HEAD et peut altèrer l'historique
- [x] Savoir annuler des `commits` et/ou `merge commits` (déplacer le HEAD, https://ohshitgit.com/)
- [x] Comprendre l'utilité et le fonctionnement de `git stash`
- [x] Comprendre et utiliser le `git diff` (quelle utilité)
Git diff permet de comparer les modifications des fichiers, branche  commits spécifiques. Il peut aussi servir a comparer les modifications indéxées ou non.
- [x] Comprendre la différence entre `git log` et `git show` + les flags principaux
- [x] Comprendre et utiliser le `git fetch`
Git fetch récupére les informations d'un repo distant.
A utiliser conjointement avec agec git log pour vérifier les changements apportés avant de de les merge avec le repo local. (Clé a molette de la comparaison git)


### Github

- [x] Finir les dailys précédents
- [x] Découverte de Github CLI (pour ceux qui ont travaillé sur autre chose la semaine précédente)
  - [x] Créer un cheat sheet sur Github CLI (individuel)
  - [x] Installation et connexion
  - [x] Faire le tour du propriétaire
  - [x] Intégration de `gh` dans son workflow
  - [x] Finalisation de son profile Github


### Setup Workflow Git

- [x] Découverte de LazyGit
  - [x] Installation et configuration
  - [x] Intégration dans son editeur / workflow
- [x] Configurer son git :
  - [x] Editeur par défaut (Nano, Vim, VsCode ou celui que vous voulez)
  - [x] Différenciateur (par ex : Delta)
  - [x] Aliases
  - [x] Comprendre la différence entre config locale, globale et système
- [x] Choix workflow : Alias ou Lazygit (obligatoire un des deux)
- [x] Savoir travailler avec `git fetch`

