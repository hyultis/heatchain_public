# HEATCHAIN

Trouvez rapidement la prochaine glyphe, prenez les bonus sans perdre de temps et réalisez la plus longue chaîne !

## Description de l'interface

![ui](../img/ui.png)

* Vous avez le glyphe au centre qu'il faut retrouver sur le plateau.
* Les deux glyphes suivants sont présents à titre d'information sur la gauche.
* A droite vous avez le temps restant et votre score actuel.
* Sous l'interface utilisateur, il y a 2 barres qui s'estompent, indiquant le temps restant avant que le multiplicateur de bonus ne disparaisse.
* 3 cœurs représentent vos vies avant de perdre.

## Descriptions des règles

* Soyez rapide, votre multiplicateur augmente plus vite en trouvant rapidement le glyphe suivant. (multiplicateur maximum "15,0")
* Chaque glyphe correct rapporte 10 points en fonction de votre multiplicateur.
* Si vous réussissez à enchaîner 20 glyphes, vous déclenchez le mode rush.
* Un bonus ne modifie pas le temps restant pour trouver les glyphes, ne perdez pas de temps à les trouver !
* Gardez votre barre multiplicatrice active, en cliquant sur la glyphe affiché sur l'interface ! S'il disparaît, le multiplicateur diminue de 0,5.
* Si vous cliquez sur une glyphe incorrect, la chaîne se brise. De plus, votre multiplicateur tombe à 1 et vous perdez une vie.
* Vous avez 3 minutes pour faire le meilleur score

## Descriptions des bonus

* ![point_lvl1](../img/point_lvl1.png) ![point_lvl2](../img/point_lvl2.png) ![point_lvl3](../img/point_lvl3.png): Gagnez 5/10/20 points en fonction de votre multiplicateur
* ![heart](../img/heart.png): Récupérez une vie. Si vous êtes pleinement dans la vie, vous gagnez ![point_lvl2](../img/point_lvl2.png)
* ![freeze](../img/freeze.png): Gèle le temps pendant 3 secondes
* ![timeup](../img/timeup.png): Augmentez le temps restant de 10 secondes
* ![chain_lvl3](../img/chain_lvl3.png): Déclenche immédiatement un RUSH

## Description du RUSH 

Dans ce mode, le plateau ne bouge plus. Vous disposez de quelques secondes pour cliquer sur autant de glyphes que possible.
Votre multiplicateur est réglé au maximum possible : 20.0
A la fin du mode rush, le temps nécessaire pour trouver le prochain glyphe est réinitialisé.

![heatchain_rush](../img/heatchain_rush.gif)
