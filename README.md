
Mazo de la asignatura _Programación y estructuras de Datos avanzadas (PREDA)_ de la Universidad Nacional a Distancia Española UNED. Contiene 106 preguntas cuyo enunciado se han cogido de esta [herramienta de la asignatura](https://ineda.lsi.uned.es/recursos/self-assessment/PREDA/). Las preguntas incluyen:

- Grafos, con sus respectivas imágenes.
- Pseudocódigo.
- Todos los esquemas vistos en la asignatura.
- Conceptos teóricos:
  - Costes
  - Métodos de hashing
  - Resolución de un problema con el esquema apropiado.

:exclamation: **Este mazo no es oficial**; ha sido hecho por un alumno de la asignatura. Al igual que cualquier otro recurso, **está sujeto a fallos**.

:star: En el apartado [Referencias](#referencias) puedes encontrar los recursos usados para hacer todo el proyecto además de otra página web con más preguntas test de la asignatura.

---

#### Tabla de contenidos

- [**Características**](#características)
  - [**Desarrollo del proyecto**](#desarrollo-del-proyecto)
- [**Usar el mazo**](#usar-el-mazo)
- [**Referencias**](#referencias)
  - [**Recursos adicionales**](#recursos-adicionales)

## Características

Todas las preguntas son de tipo test. Cada respuesta tiene dos secciones, divididas por una línea horizontal:

1. La letra o letras correspondientes a las respuestas de la pregunta. 
2. Razonamiento de la o las respuestas. 

Ciertas preguntas carecen de la segunda sección, teniendo solo como texto "Nada que comentar", porque la respuesta se ha considerado obvia. 

<table>
  <tr><th scope="col" colspan="2">Ejemplos</th></tr>
  <tr><th scope="col">Front</th><th scope="col">Back</th></tr>
  <tr>
    <td><img src="docs/front-01.png"></td>
    <td><img src="docs/back-01.png"></td>
  </tr>
    <tr>
    <td><img src="docs/front-02.png"></td>
    <td><img src="docs/back-02.png"></td>
  </tr>
    </tr>
    <tr>
    <td><img src="docs/front-03.png"></td>
    <td><img src="docs/back-03.png"></td>
</table>

### Estructura interna de las tarjetas

Anki permite varios tipos de notas. El mazo de este projecto solo está compuesto de notas tipo _Basic_. Cuando se crea una nota de este tipo, lo mínimo que necesita es introducir el texto de la pregunta en el apartado _front_ y el de la respuesta en el apartado _back_. Cuando se da a crear nota, se introduce en el mazo una única carta asociada a la nota. Para más información referente a los tipos de notas puedes consultar este [enlace](https://docs.ankiweb.net/getting-started.html#note-types).

A cualquier tipo de nota se le pueden añadir más campos. Siguiendo las pautas dadas en el [vídeo]((https://www.youtube.com/watch?v=5vh_bWsztPc&t=145s)) usado como referencia para el proyecto (ver siguiente sección), las notas tienen un campos extra, el **ID**: es un número entero que identifica unívocamente cada tarjeta y que facilita muchísimo su búsqueda en la aplicación.

### Desarrollo del proyecto

El proceso que se ha seguido para la realización del mazo está inspirado en [este vídeo de Jake Romm](https://www.youtube.com/watch?v=5vh_bWsztPc&t=145s), donde cuenta:

1. Como hacer un script .txt para automatizar el proceso de realización de las tarjetas en ChatGPT, teniendo que pasarle únicamente el texto del que se quiere hacer una tarjeta.
2. Las respuestas de ChatGPT, se copian en una hoja de cálculo. El tipo de tarjeta usada es _Basic_ por lo que mínimo se necesita una columna para el campo _Front_ (pregunta) y otra para el _Back_ (respuesta). También se usa otra columna para asignar a cada tarjeta un identificador, de forma que sea más fácil encontrar una tarjeta concreta. El documento [preda-deck.txt](docs/preda-deck.txt) muestra como queda la hoja de cálculo convertida a archivo de texto.
3. La hoja de cálculo es exportada a Anki. En el [apartado importación, de la documentación oficial](https://docs.ankiweb.net/importing/intro.html) puedes encontrar más información al respecto. Básicamente consiste en pasar la hoja de cálculo a un .txt. El archivo **debe estár en UTF-8**.

A partir de los scripts de muestra publicados en la [página web de Jake](https://thevitalcurriculum.super.site/1697e3f550934489b3b23ef29e278382), se hizo un [script](docs/formatting-instructions.md) adaptado para este proyecto, añadiendo las órdenes de formatear los enunciados con HTML y LaTeX. 

El modelo de ChatGPT que se ha usado en la mayor parte del proyecto a sido ChatGPT 3.5. Las restricciones de mensajes por día han hecho que el desarrollo general fuera _lento_.

## Usar el mazo

Solo tienes que descargar el **preda-deck.apkg** y ejecutarlo. Cuando Anki muestre la pantalla de opciones de importación, no necesitas hacer nada, solo darle a importar.

## Referencias

* **Herramienta OFICIAL de la asignatura**: https://ineda.lsi.uned.es/recursos/self-assessment/PREDA/. 
* Vídeo usado para hacer el proyecto: https://www.youtube.com/watch?v=5vh_bWsztPc&t=145s.
* Página donde se sacan los ejemplos de scripts: https://thevitalcurriculum.super.site/1697e3f550934489b3b23ef29e278382.

### Recursos adicionales

* **Más tests de esta asignatura (no oficial)**: https://www.daypo.com/buscar.php?t=PREDA.
* Documentación de Anki: https://docs.ankiweb.net.