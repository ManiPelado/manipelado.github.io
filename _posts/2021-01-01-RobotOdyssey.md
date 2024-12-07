---
layout: post
title:  "Robot Odyssey"
date:   2020-12-30 21:37:28 -0300
image:  robotOdyssey_splash.png
tags:   Aprendizaje
---
¿El juego más difícil de todos los tiempos? Así lo definió un programador que [afirma que su carrera fue determinada por su relación con este juego][Slate]. 


Todo depende de que tan difícil resulte imaginar como conectar sensores y actuadores con compuertas lógicas en tres robots para programar sus tareas.
El protagonista carga una caja de herramientas y un soldador para cablear el contenido de su caja de herramientas: compuertas discretas AND, OR, NOR y XOR, y componentes como flip-flops.
Y la complejidad solo comienza ahí: se dispone luego de contadores de 4 bits, generadores de reloj y varios chips de 8 pines cuyo cableado interno es un misterio y hay que poner a prueba para develar su comportamiento.
La complejidad alcanzable es tal que el jugador puede _quemar_ sus propios circuitos en chips de 8 pines.
Hay quien ha afirmado [haber aprendido casi tanto sobre lógica digital completando el juego que en la materia "Introducción a la ingeniería eléctrica y de computadoras" en la universidad](http://forum.caravelgames.com/viewtopic.php?TopicID=9781). 
De más está decir que esta complejidad creó tal fascinación por el juego al punto que personas como Micah Elizabeth Scott se dedicaron a [encontrar como estaban "cableados" los chips del juego][cable] y recrear el juego para permitir [jugarlo con el hardware de hoy día][Robot Odyssey Rewired].


![Mientras el protagonista despliegue su antena naranja Scanner, Sparky y Checkers siguen su programación hasta agotar su energía.]({{ site.baseurl }}/images/robotOdyssey_robots.png){: .center-image }
*Mientras el protagonista despliegue su antena naranja Scanner, Sparky y Checkers siguen su programación hasta agotar su energía.*


No es que el sufrido protagonista del juego se dedica a la electrónica digital de gusto, está forzado a hacerlo para resolver los acertijos que le permitirán escapar de una ciudad subterranea habitada por robots.
Muchos de estos se empeñan en mantener a esta desdichada _unidad de carbono_ alejado de los artefactos que necesita para avanzar en su intento de escape.


![En el interior de cada robot se opera la magia. Dentro de Scanner un mero flip-flop y una compuerta NOT comandan su lógica al inicio del juego.]({{ site.baseurl }}/images/robotOdyssey_interior.png){: .center-image }
*En el interior de cada robot se opera la magia. Dentro de Scanner un mero flip-flop y una compuerta NOT comandan su lógica al inicio del juego.*


La programación es visual y se realiza llevando al protagonista al interior de los robots.
El juego funciona sobre el motor que programó [Warren Robinett][RobinettWiki], no otro que el legendario creador de _Adventure_ en la Atari 2600 (leer esta [entrevista][AdventureEntrevista] de 2003), para _Rocky's Boots_ publicado para la Apple II en 1982.
Leslie Grimm, otro Co-fundador de The Learning Co., estuvo a cargo del juego lo lanzó para Apple II en 1984. 


## Recursos para jugarle
* Recreación en línea por Micah Elizabeth Scott: [Robot Odyssey Rewired][Robot Odyssey Rewired]
* Recreación en Java: [DroidQuest](https://github.com/ThomasFooteDQ/DroidQuest)
	* Droidquest [archivo jar](/{{ site.baseurl }}/filetes/DQ2.7.zip) complilado
* Recreación para Android: [DroidQuest Robot Odyssey](https://play.google.com/store/apps/details?id=com.droidquest.android)
* Original para Apple II (Versión 2.0, última): [Archive.org](https://archive.org/details/RobotOdysseyI_v20_4amCrack)
* Original para MS-DOS: [My Abandonware](https://www.myabandonware.com/game/robot-odyssey-6g)
	* NECESITA aplicar un [patch][Patch DOS] siguiendo [estas instrucciones](https://scanlime.org/2009/04/a-binary-patch-for-robot-odyssey/).
* Original para MS-DOS (Versión 1.1, última): [Archive.org](https://archive.org/details/msdos_Robot_Odyssey_1985)
* Manual
	* [Archive.org](https://archive.org/details/Robot_Odyssey_1_1986_Learning_Company/page/n7/mode/2up)
	* [Color Computer Archive](http://www.colorcomputerarchive.com/coco/Documents/Manuals/Educational/Robot%20Odyssey%20I%20%28The%20Learning%20Company%29.pdf)
	* [Copia local](/{{ site.baseurl }}/filetes/Robot%20Odyssey%20I%20%29The%20Learning%20Company%29.pdf)


## Más información (y ayuda)
* ¡Micah Elizabeth Scott resuelve el juego en 13 horas! (video): [Robot Odyssey (1984) Full Game Playthrough](https://youtu.be/GJeseZEZn6Y)
* Guía y solución: [Robot Odyssey(Apple II) FAQ/Walkthrough](https://gamefaqs.gamespot.com/appleii/566255-robot-odyssey/faqs/57379)
* Otra resolución en video: [Let's Play Robot Odyssey 1 - Robot Anatomy, Part 1](https://youtu.be/GJeseZEZn6Y) 
* [Foro en Reddit](https://www.reddit.com/r/robotodyssey/)
* [Artículo de la Wikipedia en inglés][Wiki]
* [Artículo en Mobygames](https://www.mobygames.com/game/robot-odyssey)
* [Robot Odyssey for the TRS-80 CoCo](https://www.youtube.com/watch?v=O59UUoL8sFY) (video)

Robot Odyssey  
The Learning Company  
1984  
Mike Wallace y Leslie Grimm   
Apple II, TRS-80 Color Computer, IBM PC  


[Slate]: https://slate.com/technology/2014/01/robot-odyssey-the-hardest-computer-game-of-all-time.html
[RobinettWiki]: https://en.wikipedia.org/wiki/Warren_Robinett
[AdventureEntrevista]: https://tjg.joeysit.com/of-dragons-and-easter-eggs-a-chat-with-warren-robinett/
[cable]: https://scanlime.org/category/projects/robot-odyssey/
[Wiki]: https://en.wikipedia.org/wiki/Robot_Odyssey
[Robot Odyssey Rewired]: https://www.robotodyssey.online/
[Patch DOS]: https://github.com/houtianze/robot_odyssey_patcher
