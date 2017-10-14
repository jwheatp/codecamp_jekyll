---
title: 3. Réaliser un premier site statique et responsive
type: cours
duree: 4h
layout: page
jour: 1
img: https://picsum.photos/200/300
description: Développons le MVP de notre site
---

### C'est parti !
Comment on procède ? On verra d'abord les grandes étapes pour ensuite aller dans le détail ;)

- Ingrédients requis pour notre recette de site internet
- Les grandes étapes pour créer notre site
- De quels langages on aura besoin ?
- Pour aller plus loin !


### Les ingrédients

Pour réaliser notre recette de site internet nous aurons donc besoin :

- De notre éditeur de code préféré (Integrated Development Environment aka IDE). Ici [Atom](https://atom.io/)
- D'un compte sur Github, normalement, c'est bon ;)
- Et surtout, l'ingrédient principale, nous aurons besoin de toute notre bonmne humeur !

C'est parti !!!

### Les grandes étapes de création d'un site internet

> **Fred:** Alors Jamie, par quoi on commence ?

> **Jamie:** Et bien Fred, si demain je te demande d'écrire un article sur ta passion, tu commencerais par quoi ?

> **Fred:** Je commencerais par ouvrir Word !

> **Jamie:** C'est la même chose ! On va commencer par ouvrir notre Word à nous aka Atom ! Notre éditeur de code !


Ok c'est parti alors, on va donc :

1. Créer un dossier dans un endroit simple, comme par exemple votre bureau appelez-le /codeproject

2. Ouvrir notre editeur de code \([Atom](https://atom.io/ "Atom.io")), on l'appelle aussi "IDE" pour Integrated Development Environment
  - Ouvrez le dossier qu'on vient de créer

3. Créez un fichier index.html
  - clic droit sur le nom du dossier "codeproject" puis nouveau fichier ou new file

![creer un fichier sur atom](https://coding-days.com/wp-content/uploads/2017/02/ouvrir-un-fichier-sur-atom.png)

4. Dans ce fichier, vous pouvez maintenant écrire les balises HTML de votre page \(le squelette\)

5. Créer un fichier style.css pour que notre site ressemble à quelques chose !

6. Mettre notre site en ligne grace à Github Pages !

### De quels langages on aura besoin ?

On va faire un petit rappelle mais vous savez déjà comment ça marche normalement ;)

On aura donc besoin d'HTML pour écrire notre contenu et structurer les différents blocs de notre site.

Ensuite, on aura besoin du CSS pour rendre notre site joli.
On pourra donc :
- Mettre de la couleur
- Définir une taille pour chacun de nos éléments
- Les positionner
- Faire disparaitre des éléments ou non
  - Pour s'amuser en JS ou en responsive
- Faire de petite animations assez sympa !

### Pour aller plus loin !

#### Des tutos sympas :

- Le positionnement avec Flex :
  - [Flexy Froggy](http://flexboxfroggy.com/)
  - [Le positionnement à l'ancienne, encore majoritairement présent](http://learnlayout.com/)
  - [Comment devenir un killer avec les selecteurs en CSS](https://flukeout.github.io/)

#### Des tutos Homemade pour :

  - [Créer un menu en ligne à partir d'une liste à puce :](/Challenge_1/atelier_1.md)

  - [Créer un ecran d'acceuil avec une phrase centrée au milieu et une jolie photo en background](/Challenge_1/atelier_2.md)

  - [Créer 3 blocs positionnés les uns à coté des autres avec une petite image, un titre et un paragraphe](/Challenge_1/atelier_3.md)

  - [Créer une alternance de photo de de texte (photo à gauche texte à droite et inversement X fois).](/Challenge_1/atelier_5.md)

  - [Créer des blocs, séparés les uns des autres et responsive !](/Challenge_1/atelier_7.md)

#### Le responsive !

Nice, je sais ce que c'est mais de là à ce que ça marche ...

C'est hyper simple à partir du moment ou l'on est à l'aise avec le CSS.

Ici on vous conseille d'essayer de faire des colonnes qui se réagenceront toutes seules au format mobile ou tablette.

1. Pour rappel, la media queries s'écrit dans la feuille de style CSS.
2. Repérer un comportement non souhaité lorsque vous redimensionnez votre fenêtre et décidez de ce que vous allez en faire.
3. Ouvrez l'inspecteur d'élément et repérez le breakpoint sur lequel il va falloir agir.
   Pour ce faire regarder les pixels comme sur la photo ci-dessous.
   ![Pixel inspector image](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/images/Challenge%204/pixel-inspecteur.jpg)
4. Une fois votre breakpoint repéré, définissez votre media, elle peut avoir plusieurs formes:
   * @media screen and \(max-width: 640px\)
   * @media screen and \(min-width: 200px\) and \(max-width: 640px\)

> Si vous voulez une liste non exhaustive mais bien complète, c'est [ici](https://github.com/makersacademy/taster2.0/blob/master/challenge_4.md "Challenge 4") [https://css-tricks.com/snippets/css/media-queries-for-standard-devices/](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

Pour rappel, une media querie s'écrit comme suit :

```css
@media screen and (max-width: 640px) {
  .elements_de_reassurances article {
    width: 100%;
  }
  /* Mes autres déclarations */
}
```

### Section 2 : On check et double check ! \(15 min\)

On l'a déjà dit, mais l'inspecteur d'élément, c'est juste indispensable.. Il existe une fonction qui va vous permettre d'émuler le terminal sur lequel vous travaillez.  
Regardez la photo ci-dessous et cliquez sur l'icône.

![Pixel inspector image](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/images/Challenge%204/device-emulator.jpg)

Vous pouvez donc écrire et checker votre code en live afin d'aller à l'essentiel !

> N'oubliez pas la règle d'héritage, mettez vos media à la fin de votre code pour qu'elle s'exécute après le code desktop.

**Lorsque vous arrivez là, que vous avez écrit quelques media dites-le-nous pour que l'on passe au cours sur les librairies et framework! :\)**

### Aller un peu plus loin - le container ! \(15 min\)

> Exemple pour le header

Voici deux header légèrements différents:

**Sans container**  
![header no container](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/images/CSS%20Challenge/header__noContainer.png)  
**Avec container**  
![header container](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/images/CSS%20Challenge/header__container.png)

Imaginez votre site sur plusieurs supports...

Sur votre ordinateur portable 13 ou 15 pouces, pas vraiment de soucis à avoir un header qui prend toute la longueur..

Mais sur un 24, 27 pouces ou une télé?

* Si vous n'avez pas de container, votre header va prendre toute la longueur \(du block\), donc la longueur de l'écran sur lequel il est.

* Si vous avez un container qui a :

  * Soit une longueur en px,
  * Soit une longueur en %,
  * Voir une autre unité \(allez fouiner sur le web\).

  Vous allez pouvoir encapsuler votre contenu qui sera alors positionné relativement par rapport à celui-ci.

  Concrètement, il va prendre sa taille quoi...

  * Mon container width: 80%;

    * Mon header en display: block;

  * Si vous vous demandez pourquoi est-t-il positionné à gauche et pas au milieu comme sur la photo, je suis certain que vous allez trouver comment le centrer!

###  Aller un peu plus loin - les Google fonts ! \(15 min\)

Pour utiliser différentes polices d'écriture, google à developper un outil magique ..

&gt;&gt;&gt; [https://fonts.google.com/](https://fonts.google.com/)

**Choississez une police d'écriture  **

![](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/Screen Shot 2017-01-13 at 11.40.27.png)

**Cliquez sur "select this font"**

![](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/Screen Shot 2017-01-13 at 11.42.09.png)



**Cliquez sur "1 Family Selected"**



![](https://raw.githubusercontent.com/Coding-Days/gitbooks/master/htmlcss/assets/Screen Shot 2017-01-13 at 11.43.02.png)



Vous trouverez deux informations utiles ici :

* La balise link en HTML devra être mise dans le ...... ?

* La déclarations CSS devra être mise dans .... ?

Vous savez désormais rajouter une font avec google font ;\)
