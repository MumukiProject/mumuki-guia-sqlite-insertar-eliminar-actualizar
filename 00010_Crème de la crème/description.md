Ahora que sabemos cómo ordenar los resultados, queremos armar un Top Five del mejor contenido que tenemos en nuestra plataforma. 

Para eso, debemos ordenar todo el contenido por el puntaje de mayor a menor (descendente). 

¡Oye oye, despacio cerebrito! Porque además necesitamos solo los primeros 5. :trophy:
En ese caso, tenemos la expresión `LIMIT <cantidad>`, que se pone al final de la consulta, para indicar la cantidad de resultados que nos interesa mostrar. 

> Consultá el Top 5 de los títulos con mayor puntaje. 

<div
  class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "id_contenido": {
        "type": "Integer",
        "pk": true
      },
      "titulo": {
        "type": "Text"
      },
      "temporadas": {
        "type": "Integer"
      },
      "puntaje": {
        "type": "Real"
      }
    }
  }'>
</div>