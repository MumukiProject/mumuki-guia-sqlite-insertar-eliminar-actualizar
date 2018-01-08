Varias cosas a tener en cuenta:

1. Como no nos interesaba guardarle en la tabla la puntuación general, simplemente no lo hicimos (fijate cómo ;) )
2. Seleccionamos las filas que nos importaban usando distintos métodos:
  * Por el id que identifica unívocamente. 
  * Por el nombre de la serie, de formas que ya te adelantamos:
    ```
    a) Usando el nombre exacto con un igual.
    b) Usando LIKE que permite poner una aproximación del nombre sin respetar mayúsculas y minúsculas.
    c) Agregándole al LIKE los porcentajes (%) delante y detrás del nombre, que considere opciones con algo más escrito en esos lugares. 
    ```
3. En este caso, lo más práctico y menos confuso es usar el id para traer las filas específicas que nos interesan. Obviamente eso dependerá de cada caso particular, y de lo que necesite. 
