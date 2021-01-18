# PRÁCTICA 2

Esta practica es un esquema de las diferencias opciones basicas que se pueden hacer con HTML y creamos nuestra primera pagina web. Esta se puede acceder desde [aquí.](https://polarcs.gitlab.io/practica-2)

## EL ENUNCIADO

Práctica 2: Secciones y líneas generales de un documento HTML5
Secciones y líneas generales de un documento HTML5

La especificación HTML5 trae muchos nuevos elementos a los desarrolladores web, permitiéndoles describir la estructura de un documento web con semántica estandarizada. Este documento describe estos elementos y cómo usarlos para definir el perfil de cualquier documento.

Problemas resueltos por HTML5

La definición de la estructura de un documento en HTML 4 y su algoritmo de perfilado es muy tosco y genera numerosos problemas:
 

1.     HTML5 quita la necesidad de elementos <div> para definir secciones semánticas sin definir valores específicos para los atributos class, introduciendo un nuevo elemento, <section>, el elemento de sección HTML.

2.     Mezclar varios documentos es difícil: la inclusión de un sub-documento en un documento principal. Esto se resuelve en HTML5 con los elementos de seccionado (<article>, <section>, <nav> y <aside>) son siempre subsecciones de su sección ancestra más cercana.

3.     HTML5 introduce el elemento <hgroup> que oculta todos los elementos de cabecera excepto el primero de más alto rango (por ejemplo, <hgroup><h1>Justine</h1><h2>Les Malheurs de la Vertu</h2></hgroup> crea el perfil 1. Justine).

4.     Un documento puede tener secciones especiales conteniendo información relacionado que no es parte del flujo principal. HTML5 introduce el elemento <aside> permitiendo a dichas secciones no ser parte del perfil principal.

5.     Hay información relacionada no al documento pero si al sitio entero, como logos, menús, tablas de contenidos, o información de derechos de autor y notas legales. Para ese propósito, HTML5 introduce tres elementos de sección específicos: <nav> para colecciones de enlaces, como una tabla de contenidos, <footer> y <header> información relacionada con el sitio.

 

De manera más general, HTML5 trae precisión a las características de seccionado y cabecera, permitiendo a los perfiles de documento ser predecibles y usados por el navegador para mejorar la experiencia de usuario.


El algoritmo de perfilado de HTML5

Definiendo secciones en HTML5

Todo el contenido incluido dentro del elemento <body> es parte de una sección. Las secciones en HTML5 pueden ser anidadas. Además de la sección principal, definida por el elemento <body>, los límites de la sección son definidos explícita o implícitamente. La secciones definidas explícitamente son el contenido definido en las etiquetas <body>, <section>, <article>, <aside>, <footer>, <header>, y <nav>. Nota: Cada sección puede tener su propia jerarquía de cabeceras. Por lo tanto, incluso una sección anidada puede tener un elemento <*h1> Consulte también Definiendo cabeceras en HTML5.

Ejemplo:


<*section>
    <*h1>Forest elephants</h1>
<*section>
     <*h1>Introduction<*/h1>
     <*p>In this section, we discuss the lesser known forest elephants.
<*/section>
 <*section>
    <*h1>Habitat</h1>
    <*p>Forest elephants do not live in trees but among them.
 <*/section>
 <*aside>
    <*p>advertising block
    <*/aside>
<*/section>
<*footer>
     <*p>(c) 2010 The Example company
<*/footer>

Instrucciones para la Entrega
La entrega debe incluir el URL de la página Web (o app) publicada en Internet en la descripción de la entrega con un texto como el siguiente:

Mi entrega está accesible en:

[aquí.](https://polarcs.gitlab.io/practica-2)



Además debe subirse el fichero con la página Web o app como un fichero adjunto la entrega por seguridad.

¡OJO! Una vez enviada la entrega, esta no se puede cambiar. Comprueben que entregan todo correctamente antes de enviarlo.

 

Instrucciones para la evaluación por pares. 
El evaluador debe analizar y visualizar dicho fichero y comprobar que funciona correctamente.

La nota se calculará sobre 10 puntos:

1.     Etiquetas básicas HTML5, comprobando la correcta jerarquía visual del archivo y emplea correctamente las siguientes etiquetas: titulares h1, h2, h3... párrafos, listas, negrita, cursiva, código...- 2/10.

2.     Etiquetas semánticas HTML5, comprobando que el alumno utiliza, <section>, <article>, <aside>, <footer>, <header>, y <nav>- 2/10.

3.     Emplea propiedades CSS para formatear el contenido, comprobando que el alumno incluye características tipográficas, colores, márgenes... - 2/10.
 

4.     Comprobando que incluye en el HEAD la información general de la página, al menos debe incluir,el tipo de documento, el charset y title - 2/10.
 

5.     Comprobar que ha subido correctamente a neocities todos los archivos necesarios para su correcta visualización - 2/10.


Dado que es un curso para principiantes, ante la duda les pedimos que sean benevolentes con sus compañeros, porque muchos participantes están empezando con HTML5 y los primeros pasos siempre son difíciles.

El objetivo de este curso es sacar el máximo provecho al trabajo dedicado y para ello lo mejor es utilizar las evaluaciones para ayudar al evaluado, especialmente a los principiantes. Al evaluar se debe dar comentarios sobre la corrección del código CSS, su claridad, legibilidad, ordenación y comentarios, siempre que puedan ayudar al evaluado. 

OJO! Una vez enviada la evaluación, está no se puede cambiar. Piensen bien su evaluación antes de enviarla.
