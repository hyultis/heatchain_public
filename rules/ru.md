# HEATCHAIN

Быстро найдите следующий глиф, заберите бонусы, не теряя времени, и составьте самую длинную цепочку!

## Описание интерфейса

![ui](../img/ui.png)

* В центре у вас есть глиф, который нужно найти на доске.
* Следующие два символа представлены для информации слева.
* Справа указано оставшееся время и фактический результат.
* Под пользовательским интерфейсом есть две исчезающие полосы, обозначающие оставшееся время до исчезновения бонусного множителя.
* 3 сердца представляют ваши жизни до поражения.

## Описания правил

* Будьте быстры, ваш множитель увеличивается быстрее, если быстро найти следующий глиф. (максимальный множитель «15,0»)
* Каждый правильный глиф приносит 10 очков в зависимости от вашего множителя.
* Если вы успешно объедините 20 символов, вы активируете режим спешки.
* Бонус не изменяет оставшееся время на поиск глифа, не тратьте время на их поиск!
* Держите панель множителя активной, щелкнув значок, показанный в интерфейсе! Если он исчезает, множитель падает на 0,5.
* При нажатии на неправильный глиф цепочка разрывается. Кроме того, ваш множитель падает до 1, и вы теряете одну жизнь.
* У вас есть 3 минуты, чтобы набрать наибольшее количество очков.

## Описания бонусов

* ![point_lvl1](../img/point_lvl1.png) ![point_lvl2](../img/point_lvl2.png) ![point_lvl3](../img/point_lvl3.png): заработайте 5/10/20 очков в зависимости от вашего множителя.
* ![heart](../img/heart.png): Восстановите одну жизнь. Если у вас полная жизнь, вы получаете  ![point_lvl2](../img/point_lvl2.png)
* ![freeze](../img/freeze.png):  Время заморозки на 3 секунды
* ![timeup](../img/timeup.png): Увеличить максимальное оставшееся время на 10 секунд.
* ![chain_lvl3](../img/chain_lvl3.png): немедленно запускает RUSH

## Описание RUSH

В этом режиме доска больше не движется. У вас есть несколько секунд, чтобы щелкнуть как можно больше символов.
Ваш множитель установлен на максимально возможный: 20,0.
По окончании режима спешки время поиска следующего глифа сбрасывается.

![heatchain_rush](../img/heatchain_rush.gif)
