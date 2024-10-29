# Objectifs journaliers

## Jeudi 10/10/2024 :


- [ ] Recueil des besoins :
    - [x] Préparer le questionnaire du premier rendez-vous client (tech et non tech)
        - Quel type d'interface? Directement dans discord ? Dashboard externe? Les deux?
        - Les fonctions du bot :
            - fournir un moyen rapide et intuitif pour le coach de rappeler a un apprenant qu'il a omis de signer
            - fourir un moyen non intrusif pour les apprenants de signaler aux coach qu'ils ont ont oublié de lancer la procédure d'émargement.
            - Rien d'autre?
        - Penser  a gerer les rattrapages avec le bot? (ex une après-midi SWS est down, personne n'a pu signer on peut envoyer un lien de rattrapage directement avec le bot)
        - Qui va utiliser le bot? Est-ce que le staff peut par exemple utiliser le bot pour envoyer une notif pour signaler qu'un apprenant n'a pas justifié une absence?
        - Conserver des traces d'utilisation (combien de fois le bot a été utilisé, quels apprenants sont )
        - Comment gerer les canaux pour l'implementaion du bot? 
            - Case Coach: (Un canal général ou un canal dans chacune des promos, ou utilisation du bot vérouillée sur un canal spécial staff)
            - Case Apprenant: lancer la procédure de poll dans un chan deja existant ou crerr un chan spécial?
        - niveau d'automatisation du bot - est ce qu'il doit ce comporter comme une alarme de 
        téléphone( rappel automatique programmé jusqu'a la désactivation pour la demi-journée)?
        -  est ce que dans la base de données liée aux bots, une fonction de gestion des plannings est prévue (pour savoir quel coach est avec quel groupe a quel moment)
        - autres besoin?
    - [ ] Préparer la partie générique du mail récapitulatif après rendez-vous
    ```
    Objet : Compte rendu de réunion du [Date]

    Bonjour à tous,

    Je vous remercie pour votre participation active lors de notre réunion qui s'est tenue le   [Date]. Voici les participants présents :

    [Nom Participant 1]
    [Nom Participant 2]
    [Nom Participant 3]

    Nous avons abordé les thèmes suivants :

    [Thème 1]
    [Thème 2]
    [Thème 3]

    Vous trouverez en pièce jointe le compte rendu détaillé de notre réunion.cdcd

    N'hésitez pas à revenir vers moi si vous avez des questions ou des remarques.

    Cordialement,
    ```
    
    - [ ] Collecter les exigences fonctionnelles et non fonctionnelles
    - [ ] Prioriser les besoins en fonction de leur importance
- [ ] Identification des règles de gestion :
    - [ ] Préparer les règles métier et les processus existants
        - c'est quoi une règle métier?
        C'est la base des systèmes d'automatisation. Permet d'ajuster la réation a certaines actions selon certaines conditions. Exemple de règle métier:
            - Frais de port offert si le montant de la commande est supérieur a 50€
            - Pas de publicité si l'utilisateur a souscrit a une offre premium<br><br>
        
        Règle métiers:
        - (si la solution implémentation directe dans discord est retenue) Le bot check si le message contenant l'embed est deja créé, si aucun message n'est présent, il l'envoie.
        - (si la solution "alarme répétable est retenue"): Le bot envoie une notification toute les x minutes pour rappeler d'envoyer le formulaire.
        - si l'apprenant 
        <br>


        Processus existants :
        - Le coach se connecte a l'une des deux application qui régissent la gestion de l'émargement selon le type promo (NetYparéo ou SoWeSign).
        - Une fênetre de temps est généree permettant aux apprenants d'enregistrer leur signature afin d'attestant de leur présence au cours.
        - Le coach veiller à ce que tout le monde ait bien signé. Si quelqu'un  a omis de signer, il doit lui en faire la remarque. Pour cela il dispose de trois possibilités : 
            - Le signaler oralement, ce qui est suffisant dans le cadre des formations présentielles.
            - Utiliser la fonctionnalité intégrée a SWS ou NYP, ce qui n'est pas optimal. L'envoi de rappel se fait par mail, qui peut être loupé par l'apprenant.
            - Envoyer un message privé via discord, ce qui n'est pas optimal au vu de la gargantuesque liste de personnes cotoyant le serveur.
    - [ ] Déterminer les contraintes légales et réglementaires
        - prévoir les mentions légales
        - cgu
        
        Ne pas enfreindre les réglements généraux.
        - rapport règlement intérieur Simplon
        - cnil
        - code pénal?
    - [ ] Intégrer les standards et normes applicables 
    - [ ] Comprendre les politiques internes et les exigences spécifiques du client

