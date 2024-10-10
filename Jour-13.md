<<<<<<< HEAD
# Notes de la "Semaine la sécurité"

## Ressources
[Pdf Sécurité coté navigateur](https://cdn.discordapp.com/attachments/1282486230629613659/1290291794969493527/anssi-guide-recommandations_mise_en_oeuvre_site_web_maitriser_standards_securite_cote_navigateur-v2.0.pdf?ex=66fbed60&is=66fa9be0&hm=201d625de5637b846f358c82d15b71dbce0bdf462b8d08298044b363e56fed51&)
[Pdf Mot de passe](https://cdn.discordapp.com/attachments/1282486230629613659/1290291794679959642/anssi-guide-authentification_multifacteur_et_mots_de_passe-1.pdf?ex=66fbed60&is=66fa9be0&hm=ead8ad1ec3ad8a7851a5c55c287cd543954bd2b2233ab2a36f2ae87d52cb5c2a&)
### Notes

| **Bonnes Pratiques** | **Mauvaises Pratiques** |
|----------------------|-------------------------|
| **Défense en profondeur** : Implémenter plusieurs couches de sécurité pour limiter l'impact d'une faille. Chaque unité doit avoir ses propres mécanismes de sécurité. | **Concentrer la sécurité au point d'entrée** : Ne pas uniquement protéger les points d'entrée. Cela expose les fonctions internes en cas de vulnérabilité. |
| **Moindre privilège** : N'accorder que les permissions strictement nécessaires à chaque élément du système, pour limiter les impacts d'une compromission. | **Permissions excessives** : Accorder des permissions au-delà de ce qui est nécessaire peut augmenter les risques en cas de compromission. |
| **Réduction de la surface d'attaque** : Ne pas exposer de services, accès, ou composants inutiles. | **Exposer des services inutiles** : Utiliser des composants ou modules non indispensables augmente les chances de failles exploitables. |
| **Sécurisation des échanges via HTTPS** : Utiliser le protocole TLS (versions recommandées : 1.2 ou 1.3) pour assurer la confidentialité et l'intégrité des échanges. | **Utilisation d'HTTP non sécurisé** : L'absence de chiffrement permet des attaques de type "Man-in-the-Middle". |
| **Encodage des données d'entrée** : Contrôler l'encodage des données pour éviter les vulnérabilités XSS. | **Utilisation dangereuse de `innerHTML` ou `document.write()`** : Ces méthodes peuvent injecter du code non sécurisé si utilisées avec des données non contrôlées. |
| **Content Security Policy (CSP)** : Mettre en œuvre une politique CSP pour réduire les risques XSS et définir les sources de contenu autorisées. | **Absence de CSP** : Ne pas utiliser de CSP laisse des vulnérabilités exploitables par des attaques XSS. |
| **Audit régulier** : Effectuer des audits de sécurité pour détecter les vulnérabilités. | **Absence d'audits** : Ne pas auditer régulièrement le système expose aux failles non détectées. |
| **Gestion des erreurs contrôlée** : En production, masquer les détails techniques des erreurs aux utilisateurs pour éviter leur exploitation. | **Exposition d'erreurs techniques** : Fournir des messages d'erreur détaillés peut aider les attaquants à identifier des failles. |
=======
# Objectifs journaliers

## Mercredi 02/10/2024 :

- [ ] Travailler sur la stratégie de sécurisation d'une application web de formation en ligne (pire2pire.com)

>>>>>>> 1eda4d8f141303ce4b94035212d57d7f2a779930
