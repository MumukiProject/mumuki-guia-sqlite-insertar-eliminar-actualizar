Queremos agregar nuevo contenido. Acá te mostramos una forma de hacerlo. 

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "formato", "creador", "estreno", "puntuacion"]'
  data-rows='[
    [1, "El planeta de los simios", "Novela", "Pierre Boulle", 1963, 9.8], 
    [2, "El planeta de los simios", "Película", "Franklin Schaffner", 1968, 7.9],
    [3, "Escape del plantea de los simios", "Película", "Arthur P. Jacobs", 1971, 6.5],
    [4, "Conquista del planeta de los simios", "Película", "Arthur P. Jacobs", 1972, 6.7], 
    [5, "La batalla por el planeta de los simios", "Película", "Arthur P. Jacobs", 1973, 8.6],
    [6, "El planeta de los simios", "Serie", "	Mort Abraham", 1974, 7],
    [7, "Regreso al planeta de los simios", "Serie", "DePatie-Freleng Enterprises", 1975, 7.4],
    [8, "El planeta de los simios", "Cómic", "El planeta de los simios franquicia", 1975, 8.2],
    [9, "El planeta de los simios", "Película", "Tim Burton", 2001, 8],
    [10, "El planeta de los simios: evolución", "Película", "Rupert Wyatt", 2011, 7.8],
    [11, "El planeta de los simios: confrontación", "Película", "Matt Reeves", 2014, 9], 
    [12, "La guerra del planeta de los simios", "Película", "Matt Reeves", 2017, 9.5]
  ]'>
</div>

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "descripcion", "creador", "principales", "temporadas", "estreno"]'
  data-rows='[
    [1, "Stranger things", "Después de la extraña desaparición de un niño, un pueblo se encuentra ante un misterio que revela experimentos secretos, fuerzas sobrenaturales y a una niña muy especial.", "The Duffer Brothers", "Eleven, Mike, Will, Dustin, Lucas, Hopper, Joyce, Nancy, Jonathan, Steve", 2, 2016], 
    [2, "Breaking bad", "Un profesor de química de escuela secundaria recurre a la venta de drogas para mantener a su familia.", "Vince Gilligan", "Walter White, Jesse Pinkman, Gus Fring, Saul Goodman, Mike Ehrmantraut, Hank Schrader, Tuco Salamanca, Skyler White", 5, 2008],
    [3, "IT", "Un grupo de chicos intimidados se unen cuando un monstruo con apariencia de payaso comienza a cazar niños.", "Stephen King", "El payaso Pennywise, Beverly Marsh, Richie Tozier, Bill Denbrough, Eddie Kaspbrak, Stanley Uris, Ben Hanscom, Mike Hanlon, Georgie Denbrough", 2, 2017]
  ]'>
</div>

```sql
INSERT INTO series_peliculas 
VALUES (4, 'Better call Saul', “James Jimmy McGuill, antes de asumir la identidad de Saul Goodman, es un abogado corrupto con un humor políticamente incorrecto vinculado al mundo criminal que empieza a crear una importante red de contactos en los bajos mundos.”, “Vince Gilligan, Peter Gould”, “Jimmy McGuill, Mike Ehrmantraut, Gus Fring, Hector Salamanca, Tuco Salamanca, Chuck McGill, Kim Wexler, Howard Hamlin, Nacho Varga”, 3, 2015);
```
