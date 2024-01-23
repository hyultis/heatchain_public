# HEATCHAIN

Encontre rapidamente o próximo glifo, pegue os bônus sem perder tempo e faça a cadeia mais longa!

## Descrição da interface

![ui](../img/ui.png)

* Você tem o glifo no centro que deve ser encontrado a bordo.
* Os próximos dois glifos estão presentes para informações à esquerda.
* À direita você tem o tempo restante e sua pontuação real.
* Abaixo da interface do usuário, há 2 barras que desaparecem, indicando o tempo restante antes que o multiplicador de bônus desapareça.
* 3 corações representam suas vidas antes de perder.

## Descrições das regras

* Seja rápido, seu multiplicador aumenta mais rapidamente ao encontrar rapidamente o próximo glifo. (multiplicador máximo "15,0")
* Cada glifo correto ganha 10 pontos dependendo do seu multiplicador.
* Se você encadear 20 glifos com sucesso, você ativará o modo rush.
* Um bônus não modifica o tempo restante para encontrar o glifo, não perca tempo encontrando-os!
* Mantenha sua barra multiplicadora ativa, clicando no glifo mostrado na interface! Se desaparecer, o multiplicador cai 0,5.
* Se você clicar em um glifo incorreto, a cadeia será quebrada. Além disso, seu multiplicador cai para 1 e você perde uma vida.
* Você tem 3 minutos para fazer a pontuação mais alta

## Descrições de bônus

* ![point_lvl1](../img/point_lvl1.png) ![point_lvl2](../img/point_lvl2.png) ![point_lvl3](../img/point_lvl3.png): Ganhe 5/10/20 pontos dependendo do seu multiplicador
* ![heart](../img/heart.png): Recuperar uma vida. Se você tem vida plena, você ganha ![point_lvl2](../img/point_lvl2.png)
* ![freeze](../img/freeze.png): Tempo de congelamento por 3 segundos
* ![timeup](../img/timeup.png): Aumente o tempo restante máximo em 10 segundos
* ![chain_lvl3](../img/chain_lvl3.png): Aciona imediatamente um RUSH

## Descrição do RUSH


Neste modo, o tabuleiro não se move mais. Você tem alguns segundos para clicar em tantos glifos quanto possível.
Seu multiplicador está definido para o máximo possível: 20,0
No final do modo rush, o tempo para encontrar o próximo glifo é zerado.

![heatchain_rush](../img/heatchain_rush.gif)
