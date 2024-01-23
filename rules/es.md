# HEATCHAIN

¡Encuentra rápidamente el siguiente glifo, toma las bonificaciones sin perder tiempo y crea la cadena más larga!

## Descripción de la interfaz

![ui](../img/ui.png)

* Tienes el glifo en el centro que se debe encontrar en el tablero.
* Los siguientes dos glifos están presentes para información a la izquierda.
* A la derecha tienes el tiempo restante y tu puntuación real.
* Debajo de la interfaz de usuario, hay 2 barras que se desvanecen, lo que indica el tiempo restante antes de que desaparezca el multiplicador de bonificación.
* 3 corazones representan tus vidas antes de perder.

## Descripciones de reglas

* Sea rápido, su multiplicador aumenta más rápido al encontrar rápidamente el siguiente glifo. (multiplicador máximo "15,0")
* Cada glifo correcto gana 10 puntos dependiendo de tu multiplicador.
* Si encadenas con éxito 20 glifos, activas el modo rápido.
* Un bono no modifica el tiempo restante para encontrar el glifo, ¡no pierdas tiempo buscándolos!
* ¡Mantén activa tu barra multiplicadora haciendo clic en el glifo que se muestra en la interfaz! Si desaparece, el multiplicador baja en 0,5.
* Si haces clic en un glifo incorrecto, la cadena se rompe. Además, tu multiplicador cae a 1 y pierdes una vida.
* Tienes 3 minutos para lograr la puntuación más alta

## Descripciones de bonificación[

* ![point_lvl1](../img/point_lvl1.png) ![point_lvl2](../img/point_lvl2.png) ![point_lvl3](../img/point_lvl3.png): Gana 5/10/20 puntos dependiendo de tu multiplicador
* ![heart](../img/heart.png): Recupera una vida. Si tienes vida completa, ganas ![point_lvl2](../img/point_lvl2.png)
* ![freeze](../img/freeze.png): Tiempo de congelación durante 3 segundos
* ![timeup](../img/timeup.png): Aumenta el tiempo máximo restante en 10 segundos
* ![chain_lvl3](../img/chain_lvl3.png): Activa inmediatamente un RUSH

## Descripción de RUSH

En este modo, el tablero ya no se mueve. Tienes unos segundos para hacer clic en tantos glifos como sea posible.
Su multiplicador está configurado al máximo posible: 20,0
Al final del modo rápido, se restablece el tiempo para encontrar el siguiente glifo.

![heatchain_rush](../img/heatchain_rush.gif)
