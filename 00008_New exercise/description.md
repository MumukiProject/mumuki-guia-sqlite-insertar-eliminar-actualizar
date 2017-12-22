Para mejorar la plataforma queremos hacer un perfil más especial para cada usuario. Para eso, crearemos una tabla para cada uno que guarde los datos del contenido que vio. 

Supongamos que Denisse, fiel clienta de NetFix, estuvo mirando recientemente Los juegos del hambre, Stranger things, The walking dead y El internado. Desde _nuestra tabla_ de contenidos podríamos cargarle fácilmente toda la información en _su tabla_ de la siguiente manera:

``` sql
INSERT INTO denisse (titulos_vistos, temporadas)
SELECT titulo, temporadas
 FROM series_peliculas 
WHERE id = 5 
OR name = “Stranger Things” 
OR name LIKE “the walking dead” 
OR name LIKE “%internado%”
```

> Hacé click en Continuar para ver cómo queda la tabla de Denisse.

MOSTRAR AMBAS TABLAS
