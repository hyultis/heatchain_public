# HEATCHAIN

Finden Sie schnell die nächste Glyphe, holen Sie sich die Boni, ohne Zeit zu verschwenden, und bilden Sie die längste Kette!

## Schnittstellenbeschreibung

![ui](../img/ui.png)

* In der Mitte befindet sich die Glyphe, die auf der Tafel gefunden werden muss.
* Die nächsten beiden Glyphen dienen zur Information auf der linken Seite.
* Rechts sehen Sie die verbleibende Zeit und Ihren tatsächlichen Punktestand.
* Unterhalb der Benutzeroberfläche befinden sich zwei ausgeblendete Balken, die die verbleibende Zeit bis zum Verschwinden des Bonusmultiplikators anzeigen.
* 3 Herzen repräsentieren Ihr Leben vor dem Verlieren.

## Regelbeschreibungen

* Seien Sie schnell, Ihr Multiplikator erhöht sich schneller, indem Sie schnell die nächste Glyphe finden. (maximaler Multiplikator „15,0“)
* Jede richtige Glyphe bringt 10 Punkte, abhängig von Ihrem Multiplikator.
* Wenn Sie 20 Glyphen erfolgreich verketten, lösen Sie den Rush-Modus aus.
* Ein Bonus verändert nicht die verbleibende Zeit, um die Glyphe zu finden. Verschwenden Sie keine Zeit damit, sie zu finden!
* Halten Sie Ihre Multiplikatorleiste aktiv, indem Sie auf die auf der Benutzeroberfläche angezeigte Glyphe klicken! Wenn es verschwindet, sinkt der Multiplikator um 0,5.
* Wenn Sie auf ein falsches Glyph klicken, wird die Kette unterbrochen. Außerdem sinkt Ihr Multiplikator auf 1 und Sie verlieren ein Leben.
* Sie haben 3 Minuten Zeit, um die höchste Punktzahl zu erzielen

## Bonusbeschreibungen

* ![point_lvl1](./img/point_lvl1.png) ![point_lvl2](./img/point_lvl2.png) ![point_lvl3](./img/point_lvl3.png): Verdienen Sie je nach Multiplikator 5/10/20 Punkte
* ![heart](./img/heart.png):  Ein Leben wiederherstellen. Wenn du volles Leben hast, erhältst du ![point_lvl2](./img/point_lvl2.png)
* ![freeze](./img/freeze.png): Zeit für 3 Sekunden einfrieren
* ![timeup](./img/timeup.png): Erhöhen Sie die maximal verbleibende Zeit um 10 Sekunden
* ![chain_lvl3](./img/chain_lvl3.png):  Löst sofort einen RUSH aus

## RUSH-Beschreibung

In diesem Modus bewegt sich das Brett nicht mehr. Sie haben ein paar Sekunden Zeit, um so viele Glyphen wie möglich anzuklicken.
Ihr Multiplikator ist auf den maximal möglichen Wert eingestellt: 20,0
Am Ende des Rush-Modus wird die Zeit zum Finden der nächsten Glyphe zurückgesetzt.

![heatchain_rush](./img/heatchain_rush.gif)
