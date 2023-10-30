# Projeto-Unity
Isabella Correia e Denis Rocha

Nosso projeto vai apresentar uma cena de um labirinto de terro, com "montros" e obistáculos 
# Colisores usados
Static Collider  
Este é um GameObject que contém um Collider, mas não possui um RigidBody. É utilizado em objetos que permanecem sempre na mesma posição e não se moverão. Geralmente, esses objetos não são afetados pela física e não aplicam força sobre outros objetos. São comumente utilizados em paredes, pisos, terrenos, etc.
usado para 



Rigidbody Collider 
Este é um GameObject com um Collider e um Rigidbody normal anexados. Eles são totalmente simulados pelas mecânicas da física e podem reagir a colisões e forças aplicadas por meio de um script.
usado para 



Kinematic Rigidbody Collider 
Este é um GameObject com um Collider e um Rigidbody cinemático ligado. É utilizado por meio de um script que modifica seu componente de transformação, mas não responderá a colisões e forças da mesma forma que um corpo rígido não cinemático. Geralmente, são usados para colisores que podem ser movidos, desativados ou ativados ocasionalmente, mas que devem comportar-se como colisores estáticos. Um exemplo disso é uma porta de correr que normalmente atua como um obstáculo físico imóvel, mas que pode ser aberta quando necessário. 
usado para 



Static Trigger Collider 
Este é um colisor que está associado a um objeto estático em um ambiente de jogo. Um objeto estático normalmente não se move durante o jogo. O colisor é marcado como "trigger," o que significa que ele não afeta a física do jogo, mas pode detectar quando outros objetos entram em sua área de colisão. Ele é frequentemente usado para criar áreas de ativação, como zonas de gatilho que disparam eventos quando um jogador ou outro objeto entra na área.
usado para 



Rigidbody Trigger Collider 
Este colisor é associado a um objeto que possui um componente Rigidbody, o que significa que ele pode ser afetado pela física do jogo, como gravidade e forças. Quando marcado como "trigger," ele também pode detectar colisões, mas, ao contrário do colisor estático, ele pode interagir com outros objetos fisicamente, como empurrá-los ou ser empurrado por eles, enquanto ainda dispara eventos de colisão. 
usado para 



Kinematic Rigidbody Trigger Collide 
Este é semelhante ao Rigidbody Trigger Collider, mas é usado com objetos Rigidbody que são marcados como "kinematic." Os objetos cinemáticos não são afetados pelas forças físicas padrão, mas podem ser controlados programaticamente. O colisor trigger neste caso permite a detecção de colisões, mesmo para objetos controlados manualmente, e é útil para situações em que você deseja saber quando um objeto kinematic interage com outros objetos sem que a física padrão os afete. 
usado para
 
