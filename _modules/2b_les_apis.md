---
title: 2. Les APIs (partie 1)
type: cours
duree: 1h
layout: page
jour: 2
img: https://picsum.photos/200/300
description:
---

### Qu'est-ce qu'une API ?
API signifie Application Programming Interface. Une API est une interface utilisée par les applications/programmes pour interagir entre eux.

Voici une petite vidéo qui vous montrera ce qu'est une API et à quoi cela sert : https://www.youtube.com/watch?v=s7wmiS2mSXY

### Notre première API
Pour commencer, nous allons jouer avec une API de démo, disponible librement sur internet, qui s'appelle https://reqres.in .

Si vous allez sur la page de Reqres, vous verrez à gauche les différentes ressources de l'API disponibles. Pour l'instant, on ne va s'intéresser qu'aux ressources de la catégorie `GET`.

Si vous cliquez sur la ressource "`GET` List Users", vous verrez un exemple de requête et de réponse. On voit que quand on fait appel à la ressource `/api/users?page=2`, il nous renvoie une réponse en JSON. Essayez de comprendre cette réponse et écrivez dans votre journal de bord ce que vous y lisez ! (quelles données, leur sens etc.)

Dans la suite de ce chapitre, on va tenter de reproduire ces réponses en faisant des appels à l'API nous-mêmes.

#### Comment faire appel à une ressource ?
Vous allez voir, c'est assez simple. Une ressource d'API se trouve à une URL. Par exemple ici, l'URL de notre API est `https://reqres.in/api`.
Quand on fera appel à une ressource, par exemple des informations sur des utilisateurs, on ajoutera le nom de cette ressource à l'URL de l'API, un peu comme pour une page d'un site web.

Où trouver les différents chemins ? Dans la documentation (https://reqres.in) ! Par exemple, pour récupérer la liste des utilisateurs, la documentation nous dit que l'URL est :
`https://reqres.in/api/users`

#### Appels à l'API via le navigateur
La façon la plus simple de faire un appel à une API en méthode GET, c'est simplement avec notre navigateur (Chrome, Firefox etc.).

Pour ce faire, copiez l'URL de la ressource que vous souhaitez dans la barre URL de votre navigateur, et regardez la réponse en JSON ;)

A vous de jouer ! Essayez de :
1. Récupérer la liste des utilisateurs
2. Récupérer la liste des utilisateurs de la page 2
3. Récupérer la liste des utilisateurs avec 10 éléments par page
4. Récupérer l'utilisateur avec l'`id` 3

#### Appels à l'API avec JQuery
Faire appel à l'API via le navigateur fonctionne, mais ça ne suffit pas dans notre cas. En fait, ce que l'on veut, ce n'est pas d'afficher de manière brute (en JSON) les données de l'API, mais de l'afficher de manière ergonomique avec du HTML et du CSS.

Pour ça, on va faire appel à JS et JQuery qui feront appel pour nous à cette API, et afficheront ensuite les données dans notre page HTML.

A vous de jouer ! Cherchez sur internet comment récupérer les données d'une API avec JQuery ;)

Si vous être bloqués, demandez à votre voisin ou appelez un mentor !

Une fois que vous aurez trouvé comment faire, vous pouvez essayer d'écrire le code dans un document JS en local ou directement dans un éditeur HTML/CSS/JS en ligne comme https://jsfiddle.net/ (sans doute plus rapide).

Une fois les données récupérer en JSON avec l'API, vous pouvez :
1. Commencer par afficher les données récupérer en brute dans la console JS, pour vérifier que tout fonctionne bien ;
2. Itérer sur ces données et les afficher dans le HTML.

Note : ce challenge n'est sans doute pas évident, mais courage, vous pourrez réutiliser ce code ensuite pour votre projet ! ;)

**Pensez à inclure vos requêtes dans votre rapport !**
