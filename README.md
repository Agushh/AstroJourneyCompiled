# AstroJourney
Astro Journey es un videojuego 2D de supervivencia espacial. Este videojuego se encuentra en etapa de desarrollo.
El juego consiste en un jugador que podra viajar en diversos planetas procedimentales. Estilo retro - pixel art.
Las mecanicas de las que dispone el juego son las siguientes :  
# Generacion Procedimental de terreno :  
La creacion de terreno consiste en ruidos Fractales ( fractal noise ). Esta tecnica consiste en sobreponer capas de un ruido con diferentes frecuencias y amplitudes, para que de esta forma se suavice el terreno. Luego se utiliza otro ruido para que las elevaciones en el terreno queden diferentes segun la zona, siendo que las zonas altas sean altas por un largo trayecto, y las zonas bajas, sean asi por un largo trayecto, formando una generacion de terreno mucho mas viva que si fuesen solo montañas. Ejemplo (imagen vista desde lejos) :   
![image](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/b7d18ce1-7b3c-4b0d-b85d-1f4733aad749)
# Generacion Procedimental de cuevas :  
Con la misma tecnica de combinar dos ruidos se busca que con uno se modifique la cantidad de cuevas que hay, y con el otro se crea la forma de las cuevas, todavia se puede mejorar el codigo para que tengan mejor forma, pero el ejemplo practico se ve asi :  
![image](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/d976385c-ecdf-44bd-994d-48fdf391d8dd)
# Generacion de texturas mediante Shader :  
Esta tecnica consiste en un shader que se aplica por arriba de cada bloque, generando una textura aleatoria y procedimental mediante un algoritmo llamado voronoi. Esta textura se utiliza sobre cada material del juego para que las texturas esten mas enriquecidas y que no sean monotonas y repetitivas. Este shader se controla mediante parametros, los cuales crean la textura, le añaden color y sombra y lo pixela. Esto se ve talque asi (texturas a modo de prueba) :  
![image](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/0e965fd7-4e9b-4bc0-9669-63f36336482d)
a la vez se trabaja con RuleTiles, esto hace que cada bloque se una dinamicamente a los que tenga alrededor.  
![Desktop_2023_08_03_-_21_16_28_01_AdobeExpress](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/665170d9-3461-4470-87f7-e7153b7e7210)
# Generacion de mapas de luz :
Para que el juego tenga mas volumen y mas enriquecimiento grafico, se creo un codigo que crea un mapa de pixeles en un rango entre 0 y 1, con la iluminacion de cada tile, esto luego se aplica con un shader por encima de la textura de los bloques. El resultado es el siguiente :  
![image](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/1d52171c-556f-44bd-88ca-e4740959b552)
# Mecanicas del jugador : 
A dia de hoy ya se tiene un personaje principal con mecanicas de movimiento basicas, y animaciones y diseño grafico. Las mecanicas de este personaje consisten en : Moverse izquierda y derecha, saltar y mirar hacia donde se encuentre el mouse. A futuro se buscara aplicar muchas mas mecanicas alrededor del jugador. El jugador es el siguiente :  
![Desktop_2023_08_03_-_21_32_43_02_AdobeExpress_AdobeExpress](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/b1be75d5-e968-405b-9242-ed92742dfba3)
# Metal Ball :
El jugador es acompañado por una bola de metal futurista que dispondra a futuro las mecanicas de poder modificar el terreno. Esta es : 
![image](https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/ca27b5b9-4dd8-49c7-93c4-71e111f5a402)
