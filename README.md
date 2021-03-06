![Pantalla de tablero del juego](design/img/Tablero.svg)


### ¿Qué es Owl Rush?

<p>Owl Rush es un juego de mesa en línea en el que un jugador accede como anfitrión e invita a sus amigos a jugar bajo las reglas de Hoot Owl Hoot!, con unas cuantas [modificaciones](#Modifications) hechas con el fin de darle un nuevo giro al juego. Este juego es completamente colaborativo, los jugadores cooperan entre sí para llevar a todos los búhos al nido antes de que el sol llegue al final de su trayectoria. </p>

<p>Este juego fue creado como el proyecto grupal para el curso de [Desarollo de Aplicaciones Web de la Universidad de Costa Rica](http://jeisson.ecci.ucr.ac.cr/appweb/2021a/), en el cual los [desarrolladores](#Developers) de Owl Rush están matriculados. Aclaramos que **este proyecto no tiene fin de lucro alguno** ni pretende representar competencia alguna al juego en el que se basa</p>

### Modificaciones al juego de los búhos (en orden de prioridad): <a name="Modifications"></a>

1. Sun-Counter: El sistema sun counter consiste en una barra que permite al jugador anular un avance del sol cada vez que se llena. La barra sun counter se llena por medio del pensar rápido de los participantes: Al comienzo de cada turno, justo después de que se toma una carta, una barra medida en segundos comienza a vaciarse. Esta barra representa el porcentaje de avance que hace el sun counter mientras el jugador decide su movimiento, si la barra se vacía, el jugador pierde la oportunidad de ganar avance en el sun counter, si por el contrario, el jugador realiza su movimiento rápidamente, entonces podrá llenar su sun counter con la cantidad que quede en la barra que se vacía. 

2. Simón dice: Para poder mover su búho de posición, el jugador tiene que repetir una secuencia de colores como en el juego de Simón dice. Si el jugador acierta la secuencia, el búho podrá realizar el desplazamiento a la casilla nueva. Sino, el jugador pierde el turno, y se mueve el sol, aunque se considera la posibilidad de permitir al jugador ajustar los castigos como desee. Las secuencias pueden ir avanzando de dificultad conforme el juego vaya avanzando. 

3. Sistema de comodines: Las cartas de colores y las cartas de sol no serían las únicas que aparecerían en el juego. Distintos tipos de modificadores (comodines) aparecerían en la baraja. Algunos de las ideas contempladas para comodines son:
- Comodín que permitiera al jugador elegir color de casilla al cual desea mover su búho.
- Comodín que permitiera al jugador mover 2 búho al mismo tiempo.
- Comodín que otorgue recarga para sun counter.

### Para ejecutar el servidor de Owl Rush!: 
Tu máquina requiere:
- Nodejs, versión 14 o superior
- Express.
Localiza la carpeta src/js_server/server y ejecuta node game_server.js. A partir de ese punto, el servidor aceptará conexiones. 
RECOMENDABLE: Accede al menú principal incluyendo home.page.xhtml en el buscador de tu preferencia.
AVISO: El juego sólo está funcional para navegador Firefox

### Desarrolladores: <a name="Developers"></a>
- Eddy Ruiz
- Lucía Elizondo
- Juan Torres

