# Projeto-Unity
Isabella Correia e Denis Rocha

Nosso projeto vai apresentar uma cena de um labirinto de terror, com "montros" e obstáculos. O personagem tem que seguir pelo caminho tendo que desviar dos obstáculos, subindo escadas, passando pela porta e logo após ganhando o jogo. 
# Colisores usados
Static Collider - 
Este é um GameObject que contém um Collider, mas não possui um RigidBody. É utilizado em objetos que permanecem sempre na mesma posição e não se moverão. Geralmente, esses objetos não são afetados pela física e não aplicam força sobre outros objetos. São comumente utilizados em paredes, pisos, terrenos, etc.

usado nas paredes, chão e obstáculos.





Rigidbody Collider - 
Este é um GameObject com um Collider e um Rigidbody normal anexados. Eles são totalmente simulados pelas mecânicas da física e podem reagir a colisões e forças aplicadas por meio de um script.

usado no personagem.





Kinematic Rigidbody Collider - 
Este é um GameObject com um Collider e um Rigidbody cinemático ligado. É utilizado por meio de um script que modifica seu componente de transformação, mas não responderá a colisões e forças da mesma forma que um corpo rígido não cinemático. Geralmente, são usados para colisores que podem ser movidos, desativados ou ativados ocasionalmente, mas que devem comportar-se como colisores estáticos. Um exemplo disso é uma porta de correr que normalmente atua como um obstáculo físico imóvel, mas que pode ser aberta quando necessário. 

usado na porta ( quando o jogador colidir com a porta ela abre. )





Static Trigger Collider - 
Este é um colisor que está associado a um objeto estático em um ambiente de jogo. Um objeto estático normalmente não se move durante o jogo. O colisor é marcado como "trigger," o que significa que ele não afeta a física do jogo, mas pode detectar quando outros objetos entram em sua área de colisão. Ele é frequentemente usado para criar áreas de ativação, como zonas de gatilho que disparam eventos quando um jogador ou outro objeto entra na área.

usado no trofel ao fim do jogo ( quando você colide com o trofel aparece uma mensagem dizendo "Você chegou ao fim". )





Rigidbody Trigger Collider - 
Este colisor é associado a um objeto que possui um componente Rigidbody, o que significa que ele pode ser afetado pela física do jogo, como gravidade e forças. Quando marcado como "trigger," ele também pode detectar colisões, mas, ao contrário do colisor estático, ele pode interagir com outros objetos fisicamente, como empurrá-los ou ser empurrado por eles, enquanto ainda dispara eventos de colisão. 

usado na  boneca ( ela fica depois da porta, anda em circulos automaticamente, quando acontece a colisão aparece a mensagem " Cuidado comigo". )





Kinematic Rigidbody Trigger Collide - 
Este é semelhante ao Rigidbody Trigger Collider, mas é usado com objetos Rigidbody que são marcados como "kinematic." Os objetos cinemáticos não são afetados pelas forças físicas padrão, mas podem ser controlados programaticamente. O colisor trigger neste caso permite a detecção de colisões, mesmo para objetos controlados manualmente, e é útil para situações em que você deseja saber quando um objeto kinematic interage com outros objetos sem que a física padrão os afete. 

usado em um dos primeiros obstaculos ( passando por ele aparece um aviso "BOO!" na tela. )
 

# Fotos 

Static collider

![static collider](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/c6213b67-c202-4043-82ea-8ba3899da97a) 





Rigidbody collider

![rididbody collider](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/c40904e3-529f-4408-96d6-57743951174c)





Kinematic collider

![kinematic collider](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/99d1de84-eeba-41b5-b9d5-bb5812664982)




Static trigger

![static trigger](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/f5089cf5-2bf0-48f7-b5bd-52439f06fa18)

![static trigger2](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/60626e61-05cf-4ecc-a632-32a4c6e8e713)





Rigidbody trigger

![rigidbody trigger](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/e3189a01-c0ac-4e10-852e-420b09738097)

![rigidbody trigger2](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/8738ee17-43a3-4e38-90f1-75c4f2023e63)





Kinematic trigger

![kinematic trigger](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/42dab6ce-954e-4fda-b69c-8b702035efd9)

![kinematic trigger2](https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/93d0875c-f92b-4938-8527-3f4435476fab)



# Vídeo


https://github.com/Denis-Rocha/Projeto-Unity/assets/128486492/16bfdf52-9dd8-4112-8cbd-ca821b2b4ba1














