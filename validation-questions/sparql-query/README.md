![](https://github.com/HerculesCRUE/ROH/blob/gh-pages/media/CabeceraDocumentosMD.png)

# Validation questions 

This folder is composed with couples of files with the same name but with different endings, `.sparql`, `.result`:
* The `.sparql` file are the queris in language [SPARQL](https://www.w3.org/TR/rdf-sparql-query/).These queries are defined to demonstrate the [ROH ontology](https://github.com/HerculesCRUE/ROH/blob/main/roh/modules/core/roh-core.ttl) usage. The meaning of each query can be found below. 
* The `.result` files are the expected result of the execution of the sparql file with the same name, using the data located in the [validation-data/rdf](https://github.com/HerculesCRUE/ROH/tree/main/validation-data/rdf) folder. 


The real result of executing a sparql query, using the data located in the [validation-data/rdf](https://github.com/HerculesCRUE/ROH/tree/main/validation-data/rdf) folder, can be found in the link that follows the query in the list below. These files are created automatically, by the [workflow](https://github.com/HerculesCRUE/ROH/blob/main/.github/workflows/widoco-and-validation-questions.yaml) deployed in Github Actions, each time a modification is made. 


The following list details the meaning of each query with the link to the real execution result:

* CQ01 - Listado de autores y documentos de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01.html)

    *  CQ01A - Listado de autores y Academic Article de los que son el autor correspondiente.  - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01A.html)

    * CQ01B -  Listado de autores y thesis de grado de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01B.html)

    * CQ01C - Listado de autores y libros o secciones de libros de los que son el autor correspondiente. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q01C.html)
  

* CQ02. Listado de personas y su dirección. La direccion sera espuesta por diversos parametros en los que se incluye el codigo postal, la direccion, la extencion de la direccion o la ciudad. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q02.html)

* CQ3.  Listado de PhD Thesis junto con el nombre de cada uno de estos documentos y en caso de tenerla la nota de estos mismos. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q03.html)

* CQ4 - Listado de investigadores principales junto con los proyectos en los que han tenido este rol. Ademas se incluira el nombre del proyecto y la cantidad monetaria asignada a dicho proyecto. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q04.html)

* CQ05 - La pregunta Q04 pero en vez de unicamente exponer los investigadores principales se expondran todas aquellas personas declaradas con un rol de miembro en dicho proyecto. - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q05.html)

* CQ06 - - [Link](https://htmlpreview.github.io/?https://github.com/deustohercules/CVN/blob/gh-pages/Q07.html)
