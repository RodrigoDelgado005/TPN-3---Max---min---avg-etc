# TPN-3---Max---min---avg-etc

a. Listar todos los autores de que sean de Nacionalidad Argentina
SELECT * FROM autores WHERE nacionalidad = 'argentino';

b. Listar todos los autores que tengan hayan publicado entre 1960 a 1980.
SELECT nombre FROM autores WHERE anio_publicacion BETWEEN 1960 AND 1980;

c. Mostrar el promedio de la edad de publicación. (avg).
SELECT AVG(edad_publicacion) AS promedio_edad_publicacion FROM autores;