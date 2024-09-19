# Objectifs journaliers

### Jeudi 19/09/2024 :

- [x] Finaliser les dailys précédents
- [?] Commencer à réfléchir à son projet Fil rouge

#### Github + Gitflow

- [x] Découverte de Github CLI `gh`

  - [x] Créer son premier repo Github (local + origin)

- [x] Découverte de Gitflow

### Markdown :

- [x] Comprendre l'intérêt du Markdown
      Rendre lisible le texte sur github via de la mise en page.
- [x] Découvrir les balises de bases :
  - [x] Titres
        - On utlisera le symbole \# pour declarer un titre. le nombre de \# joue sur la "profondeur du titre"
  - [x] Images
        - L'integration des images est semblable a une balise img en html. On peut d'afficher une image selon le theme
        exemple : 
        \<picture>
          \<source media="(prefers-color-scheme: dark)" srcset="url de l'image">
        \<source media="(prefers-color-scheme: light)" srcset="url de l'image">
        \<img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="url de l'image">
      \</picture>
        l'url de l'image peut être soit une adresse url, soit un chemin relatif par rapport au repos
  - [x] Listes
        - on peut creer des listes non triées avec les symboles  - * +, ou des nombres pour des listes triées.
        Possibilité de creer des listes imbriquées soit avec la touche tab pour les editeurs qui le permettent , soit en 
        ajoutant un nombre d'espace manuellement
  - [x] Formatage de texte (italique, souligné, gras)
    * \*\* \*\* ou \-\- \-\- texte en **gras**
    * \* \* ou \_ \_ texte en *italique*
    * \~\~ \~\~ ~texte ~barrré~
    * \*\* \*\* et \_ \_  **gras et _italique_ imbriqués**
    *  \*\*\* \*\*\* ***tout en gras et italique***
    * \<sub> \<\sub> <sub>indice</sub>
    * \<sup> \<\sup> <sup>exposant</sup>
  - [x] Code
    * pour citer du code, le placer entre deux triple backstick ``` ceci est du code```
  - [x] Citations
    * citation de texte avec : \>
  - [x] Tableaux
  - [x] Liens
      * Pour creer un lien inline on place le texte entre crochets\[\] et l'url du lien entre parenthèses \(\)
      * example: pour voir un exemple de tableux voir \[ ce lien \]\(https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github#ajout-dun-tableau\)
- [ ] Faire le parcours "how-to-markdown" (Nodeschool.io)
- [ ] Rédaction en Markdown du lexique de la promo ainsi que des cheat sheets (Terminal, Git, Github CLI, Gitflow), travail en groupe en respectant les bests practices et conventions par pull-request uniquement (2 reviews minimums avant merge)
