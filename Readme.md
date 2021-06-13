# Desarrollo de videojuego sobre Warhammer Fantasy
## Preprojecto
Desarrollo de un videojuego sobre el mundo de Warhammer Fantasy, con una historia, personajes, características personalizadas para el personaje del jugador y sistema de combate.
### Lenguaje en el que desarrollar
* Por determinar, probablemente Python/Java o en caso de hacerlo mediante una página web PHP/JS usando editores como Visual Studio Code, software de edición de imágenes GIMP para la creación de los mapas y personajes, MySQL para la base de datos del videojuego.
### Idea sobre el videojuego
La idea principal del juego es usando el sistema del videojuego de rol de mesa de Warhammer Fantasy, será un videojuego de rol a la antigua, con toma de decisiones simulando una partida de rol de verdad, crear una campaña interactiva para un jugador, combatiendo contra enemigos usando el sistema de características del juego de rol adaptado para un solo jugador, para ello la aplicación tendrá las siguientes características: 
* Creación de personajes personalizados (raza, clase, características, habilidades, talentos, etc...)
* Pequeña wiki sobre las razas, clases, armas, usadas en el juego...
* Diario: Conforme el jugador avance la historia, se irá "apuntando" automáticamente sus descubrimientos sobre personajes y lugares que vaya conociendo en el juego.
* Historia principal con decisiones con fotos de los personajes que vayan apareciendo.
* Tiradas de dados: Para el daño y para acertar tus habilidades y ataques habrá que simular esa partida de rol, por lo que el jugador tendrá que hacer tiradas de dados conforme se le diga para ver si acierta la habilidad, los dados usados en este sistema son dados de 10 y dados de 100.

### Sistema de juego
Realmente sencillo para alguien no iniciado en el rol, el jugador irá teniendo conversaciones con personajes conforme vaya avanzando la partida, ellos le irán dando misiones o lugares a donde ir para avanzar su historia, cada vez que el jugador decida hacer un acción importante se le pedirá una tirada de habilidad que requerirá de una tirada de 1 dado de 100 que se comparará con su atributo de esa característica, es decir; al jugador se le pide hacer una tirada de percepción, la habilidad percepción corresponde al atributo base "inteligencia" y el jugador tiene un 55 en esa característica, en esa tirada le sale un 47 eso significa que ha superado la tirada de dificultad, ya que en los dados le ha salido menos que su característica básica, este será el sistema de ataques también, donde esa misma tirada servirá para averiguar donde le ha dado el golpe al enemigo (si ha acertado) y luego hará la tirada de daño, donde tendrá que tirar 1 dado de 10, por lo que si al jugador le sale un 7 y el atributo de su arma es +4 significará que su daño es 11 que golpeará al enemigo en la parte del cuerpo en la que haya acertado la tirada de ataque.
