¡Paremos todo! Si quisiéramos modificar una sola cosa, claramente no estaría bueno borrar todo y volver a insertar cada registro con el dato modificado. 

En ese caso, simplemente actualizaremos la tabla, fijando los valores deseados en los campos que queramos.

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "puntuacion"]'
  data-rows='[
    [1, "Stranger things", 9.7], 
    [2, "Breaking bad", 7],
    [3, "IT", 4.9],
    [4, "Better call Saul", 6],
    [5, "The Flash", 4.7]
  ]'>
</div>

``` sql
UPDATE series_peliculas SET puntaje = 8;
```

> ¡Presioná Continuar y mirá lo que pasa! :open_mouth: