---
layout: page
title: JavaScript
permalink: index.html
---

**JavaScript** est un langage de programmation...

* **scripté** (interprété) - pas de compilateur à proprement parler.
* **côté client** - s’exécute dans un navigateur en général
(il existe des environnements côté serveur : NodeJS).
* **asynchrone** - plusieurs « morceaux » peuvent s’exécuter en parallèle.

Une meilleure définition: le rôle du JavaScript consiste typiquement à sélectionner des parties d'un document, et à décrire ce qui doit changer quand un certain événement se produit (selon [Paul Robert Lloyd](https://paulrobertlloyd.com/2018/05/javascript)).

Le langage JavaScript a été créé en 1995, pour Netscape Navigator, par Brendan Eich (en 10 jours, selon la légende, pour coïncider avec la sortie de Netscape 2, alors en forte concurrence avec Microsoft). En fin 1996, Netscape entreprend des démarches pour faire de JavaScript un standard (qui s'appellera ECMAScript). 

JavaScript n'a rien à voir avec **Java**, un autre language de programmation qui était à la mode en 1995. 

Que permet le JavaScript?
===

Le JavaScript, s'il a été utilisé initialement pour ajouter de "petites fonctionalités" aux navigateurs, comme p.ex. ouvrir des fenêtres pop-up, est néanmoins un langage de programmation à part entière. 

Dans un navigateur JavaScript, permet :

* de spécifier des changements sur le document :
* sur le contenu, la structure, le style
* en interceptant des événements (souris, clavier, doigts...)

Mais également (API HTML5) :

* d’échanger avec un serveur (AJAX)
* de dessiner (canvas - bitmap - ou svg - vectoriel)
* de se géolocaliser
* d’enregistrer localement du contenu (cache ou bdd)
* de jouer des fichiers audio ou video

<h3>Des applications en JavaScript</h3>

JavaScript est utilisé par des applications comme [Figma](https://www.figma.com/) (éditeur graphique, dont le code est [écrit en C++](https://medium.com/figma-design/building-a-professional-design-tool-on-the-web-6332ed4f1fcc#.8egblptg3) puis converti en JavaScript), ou pour simuler dans le navigateur des ordinateurs historiques (cf. [Internet Arcade](https://archive.org/details/internetarcade)).

JavaScript permet aussi de construire un éditeur 3D, comme ThreeJS:

![ThreeJS editor](img/threejs-editor.jpg)

Entre ces deux extrêmes, le JavaScript peut être utilisé pour développer des extensions de navigateur - par exemple l'extension Firefox [Add-Art](https://github.com/slambert/Add-Art) qui remplace les bannières publicitaires par des travaux d'artistes - ou pour étendre les fonctionalités de logiciels comme [Adobe InDesign](https://forums.adobe.com/community/indesign/indesign_scripting), [Max](https://docs.cycling74.com/max7/tutorials/javascriptchapter01) ou [Sketch](http://developer.sketchapp.com/introduction/plugin-scripts/). 

![La galaxie javascript, par Olivier Le Goaër](img/galaxie-javascript.jpg)

Le standard JavaScript est révisé régulièrement. La 6ème version (ES6 ou ES2015) a été finalisée en juin 2015 et la 7ème (ES7 ou ES2016) en juin 2016. Juriy Zaytev propose un [tableau récapitulatif](http://kangax.github.io/compat-table/) des fonctionnalités supportées par les différentes implémentations et navigateurs.

État du JavaScript en 2018
==

De nombreux utilitaires ont été construits sur la base du JavaScript:

- **jQuery** est une *bibliothèque* JavaScript (library) visant à faciliter l'écriture de scripts, créée en 2006 par John Resig.
- **Node.js** est une *plateforme serveur* JavaScript (runtime) - comme Apache, mais exécutant du code JavaScript plutôt que du PHP.
- **AngularJS** est un *framework* de programmation JavaScript front-end, créé par Google en 2010.
- **React** est également un *framework* JavaScript front-end, développée et rendue publique par Facebook depuis 2013.
- **Vue.js** est un framework créé en 2013 par Ewan You, et développé par une communauté d'utilisateurs. Avec React, c'est celui qui a la plus forte croissance.

![Frameworks JavaScript](img/js-frameworks.jpg)

Une application web contemporaine, au lieu d'utiliser **LAMP** (**L**inux, **A**pache, **M**ySQL, **P**HP), pourrait tourner sur **MEAN**, acronyme pour l'utilisation de **M**ongoDB (base de données), **E**xpress.js, **A**ngular.js, et **N**ode.js - une base logicielle entièrement codée en JavaScript.

La bibliothèque jQuery
==


Préprocesseurs:
===

On a vu l'apparition de préprocesseurs (comme SASS ou LESS) pour faciliter l'écriture du CSS. Cela existe aussi pour le JavaScript, ces langages sont convertis en JavaScript normal pouvant être compris par le navigateur.

- [**CoffeeScript**](http://coffeescript.org/) est un langage de programmation plus épuré que le JavaScript.
- [**TypeScript**](https://www.typescriptlang.org/) est un langage de programmation plus stricte que le JavaSript, permettant de gérer des types comme en Java. TypeScript est notamment utilisé par AngularJS 2 et sponsorisé par Microsoft.
- [**Dart**](https://www.dartlang.org/) est un langage de programmation proche de Java pouvant être compilé vers JavaScript. Il est utilisé par Google.

