---
title: El proceso de SW
author: Josue Baque
layout: post
---

<span class="image left"><img src="{{ 'assets/images/cuadro3.png' | relative_url }}" alt="" /></span>

Cuando un proceso implica la construcción de algún producto, suele referirse al proceso como un ciclo de vida
* El proceso de desarrollo de software suele denominarse ***ciclo devida del software***

La evolución del software representa el ciclo de actividades involucradas en el desarrollo, uso y mantenimiento de sistemas software [Scacchi, 1987].
Los proyectos software se desarrollan en una serie de fases
* Van desde la ***concepción del software*** y su desarrollo inicial hasta su puesta en funcionamiento y posterior retirada por otra nueva generación de software

Estas fases pueden ser
* Temporales
  * Forman una secuencia en el tiempo
* Lógicas
  * Cuando representan pasos o etapas que no constituyen una secuencia temporal

**Se puede definir ciclo de vida del software como:**

Las distintas fases por las que pasa el software desde que nace una necesidad de mecanizar un proceso hasta que deja de utilizarse el software que sirvió para ese objetivo, pasando por las fases de desarrollo y explotación [Frakes et al., 1991]

El período de tiempo que comienza cuando se concibe un producto software y finaliza cuando el producto pierde su utilidad. El ciclo de vida del software incluye las siguientes fases: fase de requisitos, fase de diseño, fase de realización, fase de pruebas, fase de instalación y aceptación, fase de operación y mantenimiento y, algunas veces, fase de retirada [AECC, 1986]

Un marco de referencia que contiene los procesos, las actividades y las tareas involucradas en el desarrollo, la explotación y el mantenimiento de un producto de software , abarcando la vida del sistema desde la definición de requisitos hasta la finalización de su uso [ISO/IEC, 2008]

Una aproximación lógica a la adquisición, el suministro, el desarrollo, la explotación y el mantenimiento del software IEEE Std 1074-1997 Standard for Developing Software Life Cycle Processes [IEEE, 1999b]

El ciclo de vida del software consiste de las siguientes fases: análisis de requisitos, diseño, implementación, prueba y mantenimiento. El proceso dedesarrollo tiende a una iteración de estas fases más que a un proceso lineal [CERN, 1996].

El ciclo de vida del software usa el modelo de que un elemento software tiene vida. Un elemento software tiene una fase de concepción (una idea en una mente de un usuario potencial), después de una fase de gestación (la fase de desarrollo del software ) hacia una fase de madurez (la revisión y corrección de errores, o fase de mantenimiento), y finalmente la fase de retirada [Leaney, 2004]

Se puede definir ciclo de desarrollo del software como:

El período de tiempo que comienza con la decisión de desarrollar un producto software y finaliza cuando se ha entregado éste. Este ciclo incluye, en general, una fase de requisitos, una fase de diseño, una fase de implantación, una fase de pruebas, y a veces, una fase de instalación y aceptación [AECC, 1986]

**Ámbito general del ciclo de vida del SW**

Desde un punto de vista general puede considerarse que el ciclo de vida de un software tiene tres etapas claramente diferenciadas:

***Planificación:*** idearemos un planeamiento detallado que guíe la gestión del proyecto, temporal y económicamente.
***Implementación:*** acordaremos el conjunto de actividades que componen la realización del producto.
***Puesta en producción:*** nuestro proyecto entra en la etapa de definición, allí donde se lo presentamos al cliente o usuario final, sabiendo que funciona correctamente y responde a los requerimientos solicitados en su momento. Esta etapa es muy importante no sólo por representar la aceptación o no del proyecto por parte del cliente o usuario final sino por las múltiples dificultades que suele presentar en la práctica, alargándose excesivamente y provocando costos no previstos.

**Objetivos de cada etapa**

En cada una de las etapas de un modelo de ciclo de vida, se pueden establecer una serie de objetivos, tareas y actividades que lo caracterizan.

***Expresión de necesidades:*** esta etapa tiene como objetivo el armado de un documento en el cual se reflejan los requerimientos y funcionalidades que ofrecerá al usuario el sistema a implementar (qué, y no cómo, se va a implementar).
***Especificaciones:*** formalizamos los requerimientos; el documento obtenido en la etapa anterior se tomará como punto de partida para esta etapa.
***Análisis:*** determinamos los elementos que intervienen en el sistema a desarrollar, su estructura, relaciones, evolución temporal, funcionalidades, tendremos una descripción clara de qué producto vamos a construir, qué funcionalidades aportará y qué comportamiento tendrá.
***Diseño:*** ya sabemos qué hacer, ahora tenemos que determinar cómo debemos hacerlo (¿cómo debe ser construido el sistema en cuestion?; definimos en detalle entidades y relaciones de las bases de datos, seleccionamos el lenguaje que vamos a utilizar, el Sistema Gestor de Bases de Datos, etc.).
***Implementación:*** empezamos a codificar algoritmos y estructuras de datos, de- finidos en las etapas anteriores, en el correspondiente lenguaje de programación o para un determinado sistema gestor de bases de datos. En muchos proyectos se pasa directamente a esta etapa; son proyectos muy arriesgados que adoptan un modelo de ciclo de vida de code & fix (codificar y corregir) donde se eliminan las etapas de especificaciones, análisis y diseño con la consiguiente pérdida de control sobre la gestión del proyecto.
***Debugging:*** el objetivo de esta etapa es garantizar que nuestro programa no contiene errores de diseño o codificación. En esta etapa no deseamos saber si nuestro programa realiza lo que solicitó el usuario, esa tarea le corresponde a la etapa de implementación. En ésta deseamos encontrar la mayor cantidad de errores. Todas los programas contienen errores: encontrarlos es cuestión de tiempo. Lo ideal es encontrar la mayoría, si no todos, en esta etapa. También se pueden agregar testeos de performance.
***Validación:*** esta etapa tiene como objetivo la verificación de que el sistema desarrollado cumple con los requerimientos expresados inicialmente por el cliente y que han dado lugar al presente proyecto. En muchos proyectos las etapas de validación y debugging se realizan en paralelo por la estrecha relación que llevan. Sin embargo, tenemos que evitar la confusión: podemos realizarlos en paralelo, pero no como una única etapa.
***Evolución:*** en la mayoría de los proyectos se considera esta etapa como Mantenimiento y evolución, y se le asigna, no sólo el agregado de nuevas funcionalidades (evolución); sino la corrección de errores que surgen (mantenimiento). En la práctica esta denominación no es del todo errónea, ya que es posible que aun luego de una etapa de debugging y validación exhaustiva, se filtren errores.













