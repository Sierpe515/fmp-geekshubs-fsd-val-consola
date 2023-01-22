#### fmp-geekshubs-fsd-val-consola

#Replica Steam Deck

***

#### Índice

1. [Cómo se lanza] (#como-se-lanza)
2. [¿Qué es?] (#que-es)
3. Manejo (#manejo)
4. Cómo se ha hecho (#como-se-ha-hecho)
5. Licencia (#licencia)
6. Sección de bugs conocidos (#seccion-de-bugs-conocidos)
7. Créditos (#creditos)

***
### Cómo se lanza

El lanzamiento de está que replica la videoconsola portátil Steam Deck es muy sencillo. Únicamente abre el archivo index.html en tu navegador o accede a ella a traves del enlace <_>.

***

### ¿Qué es?

Se trata de una reproducción -salvando las diferencias- de la videoconsola portátil Steam Deck, realizada a través de HTML y CSS.
También cabe decir que este proyecto se ha desarrollado en un ámbito educativo con fines didácticos para la Academía GeeksHubs.
En dicho proyecto se nos pedía que replicasemos cualquier consola o hardware relacionado con el mundo de los videojuevos, para poner en práctica los conocimientos adquiridos. Especialmente los relacionados con el Layaout, tanto el flow como el grid.
Yo he elegido la Steam Deck en parte por su novedad, en parte por su complejidad.

image.png

***

### Manejo

Para usar la Steam Deck replicada sencillamente desliza el cursor sobre los elementos interactivos.
No se puede jugar con ella, pero se han integrado elementos :Hover para que respondan al movimiento del ratón cuando se pasa el ratón sobre estos.

### Cómo se ha hecho

La web se ha desarrollado únicamente utilizando las tecnologías de HTML y CSS.
En HTML se ha dado forma a la estructura básica de contenedores y en CSS se les ha dado estilo.
Se han combinado el flow y el grid para colocar los contenedores (div) en el lugar deseado.
También se han investigado y aplicado diversas propiedades y valores de CSS para tratar de dar un aspecto más realista al objeto, tales como box-shadow, background-image (linear gradient, radial gradient...), border o border-radius.
Uno de los momentos críticos del proyecto fue la inserción de las agarraderas laterales, para las que hubo que describir una serie de curvas, a traves de la propiedad border-radius, que antes de alcanzar el resultado final, llegaron a lucir un aspecto deplorable.
De la misma manera se han aplicado elementos :hover para que la consola reaccione a la interacción con el cursor.