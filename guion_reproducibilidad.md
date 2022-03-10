# Reproducibilidad de trabajos científico-técnicos


> + **_Versión_**: 2021-2022
> + **_Asignatura (titulación)_**: Ciclo de gestión del dato: ecoinformática (máster conservación, gestión y restauración de la biodiversidad. UGR). Curso 2021-2022
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es) cuenta la historia parasitando vilmente trabajo de Pedro Javier Magaña Redondo y Antonio Jesús Pérez Luque, que son los que realmente saben de esto...



## Objetivos

La reproducibilidad se refiere a la capacidad que tenemos de repetir un estudio en el que analizamos datos (ecológicos en nuestro caso, pero se refiere a cualquier disciplina). Dado que los grandes avances científicos (y sociales) suelen producirse por la acumulación de pequeños avances encadenados, resulta muy importante promover que cada avance sea reproducible. Esta aparente obviedad no lo es tanto. Desgraciadamente la ciencia actual sufre una crisis de reproducibilidad. Una parte muy importante de los estudios que se realizan no son reproducibles por diversas razones (métodos poco claros, datos no documentados, etc.). En esta sesión abordamos este asunto y nos planteamos los siguientes objetivos:

+ Poner de manifiesto la importancia de la reproducibilidad en ciencia.
+ Analizar los elementos básicos que pueden fomentar la reproducibilidad.
+ Practicar en la creación de hábitos que promueban la reproducibilidad.




## Contenido

A modo de introducción al tema de la reproducibilidad, os recomiendo que veáis con detalle este material:

+ [Presentación](https://github.com/aprendiendo-cosas/TP_reproducibilidad_ecoinf_UGR/raw/2021-2022/presentacion/reproducibilidad_pmagana.pdf) de nuestro Pedro sobre el tema. Veréis muchos ejemplos de los problemas que ocasiona la falta de reproducibilidad. 
+ [Presentación](https://ajpelu.github.io/repro_ecoinf_2014_2015/) de [Antonio Jesús Pérez Luque](https://ajperezluque.com/). Compañero con gran experiencia en estas lides. Fue el responsable de este asunto en el [Observatorio de cambio global de Sierra Nevada.](https://obsnev.es/) 
+ [Artículo](https://www.revistaecosistemas.net/index.php/ecosistemas/article/view/1838): "Compartiendo datos en Ecología: cómo añadir más valor a los datos"

Durante la sesión comentamos que la reproducibilidad en ciencia tiene cuatro pilares fundamentales:

+ Árbol de directorios bien organizado. Puede parecer una obviedad, pero no lo es tanto. Es importante construir un árbol de directorios en cuyas carpetas vamos a guardar la información que necesitamos para nuestro proyecto. Las carpetas deben de tener nombres que no lleven a confusión y que sean disjuntos. Es decir, que no haya ambigüedad al incorporar archivos a cada una de ellas. También es muy recomendable que las carpetas tengan nombres cortos, sin espacios, ni tildes, ni eñes, ni otros caracteres no convencionales.
  
+ También es fundamental documentar los conjuntos de datos con los que trabajamos. Hay formas de documentar datos muy elaborados. Pero en nuestro caso bastará con un archivo de texto que describa cuestiones básicas como:
  
  + Origen del arreglo de datos.
  + Metodología utilizada para su creación.
  + Web de acceso.
  + Persona de contacto.
  + Procesamiento previo realizado.
  + Comentarios generales: calidad de los datos, problemas encontrados, etc.
  
  Además, es bastante recomendable subir los datos a un repositorio público. Hay muchos repositorios que permiten hacer esto y que, además, devuelven un DOI que se puede asignar al conjunto de datos en cuestión. Un buen repositorio es **[Zenodo](https://zenodo.org/)**.
  
+ Documentar procesamientos de datos. Si documentar los datos es importante, más (si cabe) es documentar lo que hacemos con ellos. Se trata de disponer de una serie de "recetas" con las que cocinamos los datos. Este campo está poco avanzado todavía, pero hay iniciativas interesantes que permiten documentar multitud de flujos de trabajo. Si te interesa mucho el tema, aquí tienes un texto que resume una de estas herramientas. En nuestro caso bastará con generar un archivo de texto (quizás usando [Markdown](https://es.wikipedia.org/wiki/Markdown)) en el que vamos describiendo (a modo de diario) cómo procesamos los datos. 

+ Control de versiones. El último pilar nos permite poner todo lo anterior "en movimiento" y proyectarlo en el dominio del tiempo. Es decir, además de tener la información bien organizada, es útil que podamos hacer un seguimiento de cómo cambia tanto la estructura de carpetas de un proyecto, como su contenido (sean datos o código o guiones que explican cómo procesamos los datos). Para hacer esto disponemos de multitud de herramientas. Una de las más potentes es GitHub. 

Durante la explicación usamos la pizarra de apoyo y sale este dibujo, que aunque es feo, quizás te ayude a evocar lo que vimos durante la sesión.



![image](https://github.com/aprendiendo-cosas/TP_reproducibilidad_ecoinf_UGR/raw/2021-2022/presentacion/pizarra.jpg)
