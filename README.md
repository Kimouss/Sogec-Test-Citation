# Sujet test Symfony

Le but du test est de créer un site regroupant des utilisateurs qui puissent poster des
citations ainsi de pouvoir les commenter.
* L’utilisation de la version de Symfony est libre (de préférence Symfony 4.x ou 5.x).
* La partie de design du site peut être mise de côté (utilisation de librairie autorisée).
* Le choix du type de la base de donnée est également libre.

Voici les spécifications demandées:

## Inscription et connexion:

Un utilisateur se rendant sur le site doit être redirigé sur la page de connexion.

S’il n’a pas de compte, un bouton de redirection sur la page de création de compte doit être
présent.

### Inscription:

Le formulaire d’inscription doit comporter:
* email
* pseudo
* mot de passe

Une validation par email n’est pas nécessaire.

### Connexion:

L’utilisateur doit pouvoir se connecter avec:
* email ou pseudo
* mot de passe

Une fois connecté, l’utilisateur sera redirigé vers la liste de toutes les citations

## Citations:

Un utilisateur connecté doit pouvoir accéder à un formulaire pour pouvoir poster des
citations. Bien entendu, il pourra éditer ou supprimer ses citations.

La page “index” des citations devra lister toutes les citations. Chacun des utilisateurs pourra
cliquer sur la citation “voir la citation” pour accéder à sa page.

Une partie “commentaire” doit être présent en dessous de la citation lorsqu’on est sur la
page “voir la citation” de celle-ci.


## ​Commentaires:

Lorsque l’on est sur la page de citation, un champ devra être présent pour pouvoir poster un
commentaire. Celui-ci comportera au maximum 240 caractères.

Une fois posté, celui-ci s’affichera en dessous avec l’heure et l’utilisateur qui aura envoyé le
commentaire.

L’édition du commentaire est optionnel, mais la suppression doit être présente.

### Nice to have :

* Commande de remplissage de la base de donnée (utilisateur et citation)
* Commande d’installation du projet

## Bonus:

* Test unitaire
* Soyez créatif :)
