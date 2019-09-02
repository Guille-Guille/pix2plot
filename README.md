# pix2plot

@autor: Guillermo Alonso Alonso de Linaje
contacto: guillealonso.g@gmail.com

El programa convertirá una imágen satelite en su correspondiente mapeo tridimensional.
Pese a que una foto aerea no te facilita el relieve de la zona, con este algoritmo se consigue
una muy buena primera aproximación. 

Este repositorio cuenta con dos ficheros de código. El primero de todos, 'Relieves' transformará
la imágen satélite en su correspondiente mapa topográfico con ayuda del algoritmo 'pix_2_pix'.
Para el entrenamiento adjunto una carpeta con las fotos satélite y su correspondiente mapa topogŕafico que
he utilizado. (carpetas 'fotos' y 'relieve') Los mapas se reajustan a 1024 x 512

En otro fichero a parte, 'relieve2' generará el mapa tridimensional a partir del mapa topográfico.
Para poder utilizar este fichero, hay que subir en una carpeta comprimida de nombre 'Resultados', 
los mapas topográficos y posteriormente en la casilla señalada elegir el mapa concreto a plotear.

Dejo adjuntado también un video explicativo del proyecto.

Posible aplicación:
Para generar los mapas topográficos de la Tierra, se realizaron misiones como  la "Misión topográfica Radar Shuttle"
que con ayuda de un satelite con dos cámaras consiguió unos buenos resultados en 11 días. Con esté programa se puede
realizar una primera estimación mucho más económica tanto en tiempo como en dinero. Además se podría utilizar en la 
generación de mapas topográficos de otros planetas sin la necesidad de llevar satélites, tan solo con un DataSet pequeño
de diferentes zonas de el mismo.


