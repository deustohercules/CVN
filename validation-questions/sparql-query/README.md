![](https://github.com/HerculesCRUE/ROH/blob/gh-pages/media/CabeceraDocumentosMD.png)

# Validation questions 

This folder is composed with couples of files with the same name but with different endings, `.sparql`, `.result`:
* The `.sparql` file are the queris in language [SPARQL](https://www.w3.org/TR/rdf-sparql-query/).These queries are defined to demonstrate the [ROH ontology](https://github.com/HerculesCRUE/ROH/blob/main/roh/modules/core/roh-core.ttl) usage. The meaning of each query can be found below. 
* The `.result` files are the expected result of the execution of the sparql file with the same name, using the data located in the [validation-data/rdf](https://github.com/HerculesCRUE/ROH/tree/main/validation-data/rdf) folder. 


The real result of executing a sparql query, using the data located in the [validation-data/rdf](https://github.com/HerculesCRUE/ROH/tree/main/validation-data/rdf) folder, can be found in the link that follows the query in the list below. These files are created automatically, by the [workflow](https://github.com/HerculesCRUE/ROH/blob/main/.github/workflows/widoco-and-validation-questions.yaml) deployed in Github Actions, each time a modification is made. 


The following list details the meaning of each query with the link to the real execution result:

* CQ01. Listado de centros de investigación los cuales tiene area de conocimiento `uneskos-individuals:120304`. Se devuelve la URI de dicho centro (columna *centro*) y en caso de que este declarado en el grafo de conocmiento, tambien se devolvera el nombre de dicho centro (columna *centerName*) y el nombre de la universidad a la que pertenece (columna *universityName*). - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q01.html)

* CQ02. Listado de los investigadores (columna *researcher*) que tienen el area de conocimiento `unekos:120304` y cuya posicion (columna *positionClass*) es de `ResearcherPosition` en un centro de investigacion concreto (columna center). - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q02.html)

* CQ3. Devuelve un listado de investigadores (columna *researcher*) con área de investigación `uneskos-individuals:120304`. Por cada investigador se devuelve el número de citas de su CV (columna *n_citas*), la metrica h_index de su CV (columna *h_index*), la métrica i10-index de su CV (columa *i10-index*), el numero de publicaciones en las que ha participado (columna *n_pubicaciones*) y el numero de publicaciones de las que es autor principal (columna *n_corresponding_author*). Los usuarios estan ordenados según la suma de todos estos parametros. Como maximo se devolveran 10 usuarios. - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q03.html)

* CQ4 - Listado de los centros de investigación (columna *center*) que tienen sellos de calidad y el número de sellos que tienen (columna *numberOfSeals*). Solo se muestran los 10 primeros centros con un ordenacion descendiente. - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q04.html)

* CQ05 - Listado de centros de investigacion (columna *centre*) que han partipado en proyectos (columna *proyect*). Ademas se incluira, en caso de que dicho proyecto lo tenga definido en el grafo de conocimiento su clasificacion (columna *classClasificacionProject*). - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q05.html)

* CQ06 - Listado de la producción científica (columna *ResearchObject*) en un determinado rango de fechas (`de 1980 a 2022`) de un centro/estructura de investigación (columna *Organization*) en un área/disciplina  `uneskos-individuals:120304`). Como infromacion adicional se incluyen los siguientes datos: el tipo de archivo que es (columna *researchObjectClass*), autor de correspondencia (columna *author*), fecha (columna  *dateTime*) , titulo (columna title), si esta en un repo se devolvera la URI de dicho repo (columna *repository*), palabras claves del recurso (columna *keyword*)  y doi (columna *doi*) . - [Link](https://htmlpreview.github.io/?https://github.com/HerculesCRUE/ROH/blob/gh-pages/html/Q06.html)
