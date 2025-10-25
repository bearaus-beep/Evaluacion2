Este código funciona en conjunto con la API de Geocodificación y Ruteo, específicamente a la de Graphhopper.

Como funciona:

El usuario elige en que medio de transporte se esta movilizando, este puede ser en auto, bicicleta o caminando.

Escribe la ciudad de origen, desde donde esta empezando el recorrido, el programa buscar en su base los datos de geolocalización de la ubicación especificando el tipo de localización, si pertenece a un pueblo, ciudad, etc. como también las coordenadas de latitud y longitud de la ubicación

Después pedirá la localización del destino con la cual hará lo mismo que la de origen entregándonos los datos de ubicación acompañada de un URL de Graphhopper con los detalles de la ubicación

Después de esto detallara la instrucciones de como llegar a nuestro destino seleccionado indicando calles tiempo y longitud del camino a recorrer 
