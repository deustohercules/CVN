# Validation questions 

Los ficheros sparql están en el lenguaje [SPARQL](https://www.w3.org/TR/rdf-sparql-query/). El resultado real de ejecutar cada una de las preguntas sparql, usando como datos los ttl resultantes de la transformación de los CVN en formato XML, pueden encontrarse en los link de este documento. Estos ficheros (tanto los ttl como los ficheros HTML que contiene la respuesta real) son generados automáticamente mediante Git Actions. Estas acciones se ejecutan cada vez que hay una modificación en el repositorio por lo que los archivos HTML están actualizados en todo momento.  En la siguiente lista encontramos el significado de cada fichero/pregunta sparql junto con el link de los ficheros HTML generados.

<!--The `.sparql` files are the queries in language [SPARQL](https://www.w3.org/TR/rdf-sparql-query/). The meaning of each query can be found below. The real result of executing a sparql query, using the data located in the `examples/result` folder, can be found in the link that follows the query in the list below. These files are created automatically, by the [workflow](https://github.com/deustohercules/CVN/blob/main/.github/workflows/widoco-and-validation-questions.yaml) deployed in GitHub Actions, each time a modification is made. -->


<!--The following list details the meaning of each query with the link to the real execution result:-->

* CQ01 - Listado de autores y documentos de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01.html)

    *  CQ01A - Listado de autores y Academic Article de los que son el autor correspondiente.  - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01A.html)

    * CQ01B -  Listado de autores y tesis de grado de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01B.html)

    * CQ01C - Listado de autores y libros o secciones de libros de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01C.html)
  

* CQ02. Listado de personas y su dirección. La dirección vendrá dada por diversos parámetros en los que se incluye el código postal, la dirección, la extensión de la dirección o la ciudad. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q02.html)

* CQ3.  Listado de PhD Tesis junto con el nombre de cada uno de estos documentos y en caso de tenerla la nota de estos mismos. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q03.html)

* CQ4 - Listado de investigadores principales junto con los proyectos en los que han tenido este rol. Además se incluirá el nombre del proyecto y la cantidad monetaria asignada a dicho proyecto. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q04.html)

* CQ05 - La pregunta Q04 pero en vez de únicamente exponer los investigadores principales se expondrán todas aquellas personas declaradas con un rol de miembro en dicho proyecto. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q05.html)

* CQ06 - - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q06.html)
