# mona-ondulada [Spanish]
Creative Coding using Processing and Python in order to generate a simplified version of an image using only ellipses in Processing (asignment).

## Geometrize by Sam Twidale (web version)
Para generar una versión simplificada de una foto usando solo elipses utilicé la versión web de Geometrize de Sam Twidale (basado a su vez en Primitive de Michael Fogleman):

[https://www.samcodes.co.uk/project/geometrize-haxe-web/](https://www.samcodes.co.uk/project/geometrize-haxe-web/)

Con dicho recurso generé un archivo tipo SVG que contenía los elipses para representar la imagen deseada.

## SVG file parsing using Python assited by copilot (AI)
Con el fin de adaptar dicho archivo a Processing code sin utilizar una función u objeto para abrir/reproducir archivos de este tipo. Cree un script the parsing en python ayudandome de copilot (IA) para hacer la conversión de la información en el formato precisado  para la tarea. El prompt utilizado especificaba la información  relevante para cada elipse (opacidad, rgb, posición, rotación, escalado,  etc).

## Processing code (copy & paste)
Finalmente, una vez "traducido" el código con el parser  procedí a probarlo directamente en procesing y el script de ~6400  líneas produjo el resultado deseado.
