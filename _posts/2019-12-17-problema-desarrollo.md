---
title: Problemas en el desarrollo de software
author: Josue Baque
order: 3
layout: post
---

**¿Qué es un proyecto software?**

Haciendo uso de la definición de proyecto de la guía del PMBOK, y adaptándola a un proyecto software, podríamos definirlo como: 

“Un proyecto software es un esfuerzo temporal que se lleva a cabo para crear un producto software, servicio TI o resultado único.” 

**¿Pero que es el software?**  Según la definición del IEEE, "software es la suma total de los programas de ordenador, procedimientos, reglas, la documentación asociada y los datos que pertenecen a un sistema de cómputo", y "un producto de software es un producto diseñado para un usuario". 

El software puede dividirse en dos grandes categorías:

**Software de aplicaciones:** se usan para proveer servicios a clientes y ejecutar negocios de forma más eficiente. El software de aplicaciones puede ser un sistema pequeño o uno grande integrado. Como ejemplos de este tipo de software estarían un sistema de cuentas, un sistema de planificación de recursos... 

**Software de sistemas:** El software de sistemas se usa para operar y mantener un sistema informático. Permite a los usuarios usar los recursos del ordenador directamente y a través de otro software. Algunos ejemplos de este tipo de software son los sistemas operativos, compiladores y otras utilidades del sistema. 

**Ingeniería del software**

Los proyectos software tienen características específicas que los hacen diferentes de otros proyectos de ingeniería. 

La Ingeniería del Software es la rama de la ingeniería que crea y mantiene las aplicaciones de software usando tecnologías y prácticas de las ciencias de la computación, manejo de proyectos, ingeniería, el ámbito de la aplicación, y otros campos. 

¿Por qué el software es diferente a cualquier otro proceso de fabricación? Podríamos identificar los siguientes motivos: 

El software se ***desarrolla***, no se ***fabrica*** en el sentido clásico de la palabra. Ambas actividades se dirigen a la construcción de un "producto", pero los métodos son diferentes. Los costes del software se encuentran en la ingeniería, esto implica que los proyectos no se pueden gestionar como si lo fueran de fabricación. 

La juventud de la ingeniería del software con respecto a otras ingenierías, la mayoría del software se construye a ***medida***, en vez de ***ensamblar*** componentes previamente creados. Aunque ya se están dando importantes pasos en esta dirección, que facilitaría en gran medida el desarrollo de aplicaciones informáticas. 

En el software, el recurso principal son las ***personas***. No es siempre posible acelerar la construcción de software añadiendo personas porque la construcción de software requiere un esfuerzo en equipo. El equipo tiene que trabajar de forma coordinada y compartir un objetivo de proyecto común. Se necesita comunicación efectiva dentro del equipo. 

El software no se estropea, pero se ***deteriora***. Durante su vida, el software sufre cambios (***mantenimiento***). Conforme se hacen los cambios, es bastante probable que se introduzcan nuevos defectos, lo que hace que el software se vaya deteriorando debido a estos cambios. 

**Visión general del proceso de ingeniería del software**

Con independencia del área, tamaño o complejidad del proyecto, cualquier proyecto se encontrará al menos en una de las siguientes fases:  
* Definición ~ Análisis (del sistema, del sw).
* Desarrollo ~ Diseño, codificación, prueba.
* Mantenimiento.  

**Definición**

¿Qué debe hacer el sistema?

* Información que ha de manejar el sistema.
* Necesidades de rendimiento.
* Restricciones de diseño.
* Interfaces del sistema con los usuarios y con otros sistemas.
* Criterios de validación.

**Desarrollo**

¿Cómo construir el sistema?

* Se diseñan las estructuras de los datos y los programas.
  * Como se caracterizan las interfaces.
  * Como realizar el paso del diseño al lenguaje de programación.
  * Como ha de realizarse la prueba. 
* Se escriben y documentan los programas.
* Y se prueba el software construido.

**Mantenimiento**

* Comienza una vez construido el sistema.
* Se centra en el cambio.
* El software es sometido a reparaciones y modificaciones cada vez que se detecta un fallo o se necesita cubrir una nueva necesidad de los usuarios.
* En esta fase recae el mayor porcentaje del costo de un sistema.
* Un buen sistema no es sólo un conjunto de programas que funcionan bien => ***Debe ser fácil de mantener***

Tipos de mantenimiento.

* Correctivo. El programa no funciona correctamente, hay que modificarlo.
* Perfectivo. Se modifica el programa para obtener más eficiencia o nuevas funcionalidades no especificadas en la definición del sistema.
* Adaptativo. Adaptar el programa a los cambios en su entorno (cambio de SO, de CPU, de legislación, …)
* Preventivo. El software se deteriora con los cambios, este mantenimiento hace cambios para que los programas se puedan corregir, adaptar y mejorar más rápidamente -> Reingeniería del SW.

<span class="image left"><img src="{{ 'assets/images/cuadro1.png' | relative_url }}" alt="" /></span>

