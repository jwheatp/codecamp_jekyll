---
title: 3. Projet - Itération 2
type: cours
duree: 3h30
layout: page
jour: 2
img: https://picsum.photos/200/300
description: Continuons sur nos projets !
---

### Les données de ce projet
Dans ce projet, nos données sont stockées chez Airtable, qui est un peu comme un fichier Excel hébergé en ligne : c'est notre base de données.

La base de données est accessible à ce lien :
`https://airtable.com/shrgy3KpM2umlLHfK`

.. Mais il s'agit de "ma" base de données. Pour que vous ayez chacun la vôtre et pour que tout le monde n'utilise pas la même base de données, cliquez en haut à droite sur "Copy base", pour dupliquer cette base de données, et créez votre propre compte Airtable, que vous utiliserez pour ce projet.

### L'API de ce projet
Pour communiquer avec Airtable, il va nous falloir utiliser ici une API. Vous verrez, son utilisation est très similaire à celle de démo Reqres !

#### Pour bien comprendre l'API de Airtable
Commencez simplement par jouer un peu avec l'API de Airtable.

Par exemple, avec votre navigateur ou JQuery/JQ, essayez de :

- Sélectionner toutes les musiques de notre base ;
- Sélectionner toutes les musiques de notre base et les trier par nombre de votes, de manière descendante ;
- Sélectionner la musique avec l'ID '2' ;
- Sélectionner la musique avec le titre `Over Everything` ;

Pensez à garder dans votre rapport le code utilisé ! ;)

### Inclure les musiques de la base de données sur votre page
A vous de jouer ! L'objectif de cette journée est d'inclure les données de la base de données sur votre page HTML/CSS. Et que si demain on ajoute d'autres musiques dans votre base de données (via Airtable par exemple), elles s'affichent directement sur votre page.

#### Utilisez le player de Spotify
Vous verrez que chaque musique dans la base de données a un champs `spotify-url`, qui est un identifiant Spotify pour utiliser leur player HTML. Cherchez sur google comment intégrer le player de Spotify dans une page web et vous comprendrez vite comment utiliser ce champs `sportify-url` ;)
