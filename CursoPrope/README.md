# Descripción del proyecto

El análisis se efectuará sobre la información obtenida de las encuestas realizadas a los estudiantes del curso propedéutico impartido por la Facultad de Ciencias de la UNAM en el año 2022. 

### Recapitulación de la información

La información con la que trabajaremos corresponde a los datos generados en la primer semana del curso propedéutico.
Dentro de dicho curso se dieron diferentes talleres de diferentes temas, de la siguiente manera: inicialmente se abordaron
temas de matemáticas desde un punto de vista didáctico y de divulgación. Después, dichos conceptos
fueron formalizados en las secuencias didácticas.

Ahora bien, para la información recopilada consideraremos dos archivos csv:

* Encuestas: Recopila información sobre los diferentes talleres brindados, donde las preguntas evalúan qué tan claro fue la exposición de los temas, el lenguaje que se ocupó, etcétera. De manera global las encuestas evalúan los talleres. En las encuestas se evalúan tanto los talleres como las secuencias didácticas. Además, éstas contienen comentarios de los estudiantes respecto a cómo les pareció la impartición del taller.

[Archivo csv](Datasets/Encuentas.csv)

* Asistencias: Recopila la asistencia de los participantes del curso propedéutico en la primer semana del curso (es decir, recopila las asistencias de 5 días). Además, éstas contienen comentarios de los estudiantes respecto a cómo les pareció la impartición de las secuencias didácticas.

[Archivo csv](Datasets/Asistencias.csv)

Con base en lo anterior, es natural enfocar nuestro análisis de datos en ver las evaluaciones que se les dieron a cada uno de los talleres, o ver de manera global la evalución conjunta de todos los talleres para determinar una evalución general al curso propedéutico. Podremos ver también cuáles fueron los aspectos (o preguntas de la encuesta) que obtuvieron mejor o peor respuesta; por ejemplo, si logramos identificar las preguntas de la encuesta que obtuvieron peor respuesta, se puede enfocar más en dicho tema o abordarlo de una manera distinta en los siguientes cursos propedéuticos. En teoría, cada participante debía responder sólo una vez la encuesta en dicha primer semana.

Asimismo, podemos ver el comportamiento de los participantes entorno a sus asistencias. Por ejemplo, puede ser que el día viernes asistieron menos participantes a los talleres respecto a los demás días, o tal vez, el día en que asistieron más participantes fue, justamente, el primer día del curso (lunes). Lo anterior podremos responderlo de una manera certera. Así, lo dicho antes representa el punto de partida y el camino que debemos seguir respecto a nuestro análisis de datos.

### Notebook's de Python

En la primer notebook realizamos la carga y limpieza. Adicionalmente, realizamos un primer análisis de la información en la cual obtuvimos:

* Gráficos informativos.
* Primeras conclusiones.
* Conjuntos de datos para posteriormente realizar un tablero en Power BI.
* Comportamiento de las asistencias de los estudiantes.

[Archivo ipynb](analisis_datos_notebook.ipynb)

En la segunda notebook analizaremos los comentarios que los estudiantes escribieron respecto a la impartición de los talleres y las secuencias didácticas. Lo que haremos será analizar el sentimiento de dichos comentarios utilizando procesamiento del lenguaje natural. Buscaremos clasificar los comentarios en positivos, neutros y negativos, y también crearemos nubes de palabras. Con lo anterior conseguiremos ver de manera general las opiniones de los estudiantes respecto de los talleres, secuencias didácticas y en general sobre el curso porpedéutico.

[Archivo ipynb](analisis_datos_notebook_2.ipynb)

### Tablero 

Con la información y conjuntos de datos obtenidos en las notebook's anteriores, crearemos un tablero utilizando Power BI. Antes de ello creamos un diagrama relacional:

[Link](https://luisapaez.github.io/Proyectos_AnalisisDatos/CursoPrope/TableroPowerBI/DiagramaRelacional.html)

Utilizando el diagrama relacional anterior obtendremos dos diagramas estrella, los cuales serán utilizados para crear, ahora sí, un tablero en Power BI.

[Archivo PDF](Resumen_curso_propedeutico.pdf)

[Archivo pbix](TableroPowerBI/Tablero.pbix)

Finalmente creamos una presentación en Power Point presentando los resultados obtenidos.

[Archivo PDF](Presentación.pdf)

[Archivo pptx](Curso propedéutico 2022.pptx)
