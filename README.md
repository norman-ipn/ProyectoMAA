# ProyectoMAA
Análisis y Automatización del juego MAA

##Objetivo
Automatizar el juego MAA

##Propuesta

Capturar pantalla y localizar botones y casillas con OpenCV[1], particularmente
con la función de Template Matching[2]. Requiere hacer capturas de los botones y 
casillas (templates) para poder localizarlas en pantalla.

Interactuar con el juego mediante la herramienta xdotool[3], que permite mandar
clics a las ventanas. Una vez que OpenCV determine la posición de los botones y
casillas, xdotool podrá hacer clic en ellas. 

Codificar las reglas del juego en Prolog[4] para poder realizar consultar
sobre la mejor estrategia. Aprovechando el motor de búsqueda de prolog
se prodran resolver preguntas respecto a qué ataque utilizar o a qué enegimo 
atacar. Requiere codidifcar todos los ataques, potenciadores, despotenciadores, 
isos, etc, etc.

##Referencias

* [1] http://opencv.org/
* [2] http://docs.opencv.org/doc/tutorials/imgproc/histograms/template_matching/template_matching.html
* [3] http://www.semicomplete.com/projects/xdotool/
* [4] http://www.swi-prolog.org/
