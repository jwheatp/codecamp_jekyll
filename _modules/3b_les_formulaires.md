---
title: 2. Les formulaires
type: cours
duree: 1h
layout: page
jour: 3
img: https://picsum.photos/200/300
description:
---

### Chemin utilisateur

Voilà, on sait comment ajouter un nouvel élément à notre base de données via une API. Bon, bien-sûr, ce n'est pas très user friendly. Quand un utilisateur voudra ajouter une musique sur notre site, on ne va pas lui demander de faire un appel à notre API avec la méthode POST, ça risquerait de le faire fuir ! Il manque une pièce à notre puzzle : un formulaire. Vous le développerez cet après-midi, mais avant, comme il y a beaucoup d'étapes, assurons-nous que tout le processus soit bien clair.

Résumons un peu le chemin de l'utilisateur :
1. Je rempli le formulaire sur le site pour ajouter une nouvelle musique ;
2. Je clique sur un bouton "envoyer" ;
3. Cela lance un petit script qui va traiter notre formulaire, vérifier que tout est bien rempli.
4. Si tout est bien rempli, notre script va envoyer les données de notre formulaire à notre API.
5. Notre base de données (Airtable) reçoit bien les données et les enregistre

#### Détaillons ce chemin utilisateur
Reprenez les étapes ci-dessus dans un petit schéma dans votre journal de bord, et ajoutez les informations suivantes, **pour chaque étape** :
- les langages utilisés ;
- si HTML est utilisé, les balises présentes et dans quelle ordre ;
- si l'API est utilisée, les méthodes employées (`GET`/`POST`/`PUT` etc.) ;
- si JS/JQuery est utilisé, les événements/fonctions dont vous aurez besoin, et les étapes de votre code ;
