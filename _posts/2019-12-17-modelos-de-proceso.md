---
title: Modelos de procesos de software 
author: Josue Baque
layout: post
---
**Modelo de Cascada**

<span class="image left"><img src="{{ 'assets/images/cascada.png' | relative_url }}" alt="" /></span>

Las fases están identificadas por separado: 
* El análisis  y definición de requerimientos
* Diseño del sistema y software.
* Pruebas de implementación de unidades
* Integración y pruebas del sistema 
* Operación y mantenimiento 

El principal inconveniente del modelo de la cascada es la dificultad de acomodar el cambio después de que está en marcha el proceso. En principio, una fase tiene que ser completada antes de pasar a la siguiente fase.

**Desarrollo incremental**

<span class="image left"><img src="{{ 'assets/images/incremental.png' | relative_url }}" alt="" /></span>

***Beneficios:*** 
* El costo de atender las necesidades cambiantes de los clientes se reduce. 
  * La cantidad de análisis y la documentación que tiene que ser hecho de nuevo es mucho menor que la que se requiere con el modelo de cascada. 
* Es más fácil obtener retroalimentación de los clientes en el trabajo de desarrollo que se ha hecho.
  * Los clientes pueden hacer comentarios sobre las manifestaciones del software y ver cuánto se ha implementado. 
* Más rápida entrega y despliegue de software de utilidad para el cliente es posible. 
  * Los clientes pueden usar y obtener valor a partir del software anterior que es posible con un proceso de cascada.

***Problemas:*** 
* El proceso no es visible.
  * Los gerentes necesitan entregas regulares para medir el progreso. Si se desarrollan rápidamente los sistemas, no es rentable para producir documentos que reflejen todas las versiones del sistema.
* Estructura del sistema tiende a degradarse a medida que se añaden nuevos incrementos. 
  * A menos tiempo y dinero que se gasta en la refactorización para mejorar el software, cambio regular tiende a corromper su estructura. La incorporación de nuevos cambios de software se vuelve cada vez más difícil y costoso. 

**Espiral**

<span class="image left"><img src="{{ 'assets/images/espiral.png' | relative_url }}" alt="" /></span>

**Definición:** 
Es un modelo de ciclo de vida desarrollado por Barry Boehm en 1988. 

Las actividades de este modelo son una espiral, cada bucle es una actividad. 

Las actividades no están fijadas a prioridad, sino que las siguientes se eligen en función del análisis de riesgo, comenzando por el bucle interior.

En este modelo, el esfuerzo de desarrollo es iterativo. Tan pronto como uno completa un esfuerzo de desarrollo, otro comienza. Además, en cada desarrollo ejecutado, puedes seguir estos cuatros pasos.
1. Determinar qué quieres lograr. 
2. Determinar las rutas alternativas que puedes tomar para lograr estas metas. Por cada una, analizar los riesgos y resultados finales, y seleccionar la mejor. 
3. Seguir la alternativa seleccionada en el paso 2. 	
4. Establecer qué tienes terminado. 

**Desarrollo Rápido de Aplicaciones (DRA)**


<span class="image left"><img src="{{ 'assets/images/aplicaciones.png' | relative_url }}" alt="" /></span>

**Definición:** 

Es un modelo de proceso del ciclo de vida clásico que enfatiza un ciclo de vida de desarrollo extremadamente corto.   

El modelo DRA es una adaptación a alta velocidad del ciclo de vida clásico en el que se logra el desarrollo rápido utilizando un enfoque de construcción basado en componentes. Si se comprenden bien los requisitos y se limita el ámbito del proyecto, el proceso DRA permite al equipo de desarrollo crear un sistema completamente funcional dentro de períodos cortos de tiempo. 

Cuando se utiliza principalmente para aplicaciones de sistemas de información, el enfoque DRA comprende las siguientes fases:
 * ***Modelado de gestión:*** El flujo de información entre las funciones de gestión se modela de forma que responda a las siguientes preguntas: ¿Qué información conduce el proceso de gestión? ¿Qué información se genera? ¿Quién la genera? ¿A dónde va la información? ¿Quién la procesa? 
  * ***Modelado de datos:*** El flujo de información definido como parte de la fase de modelado de gestión refina como un conjunto de objetos de datos necesarios para apoyar la empresa. Se definen las características de cada uno de los objetos y relaciones entre estos objetos.
 * ***Modelado de procesos:*** Los objetos de datos definidos en la fase de modelado de datos quedan transformados para lograr el flujo de información necesario para implementar una función de gestión. Las descripciones se crean para añadir, modificar, suprimir, o recuperar un objeto de datos.
 * ***Generación de aplicaciones:*** El DRA asume la utilización de técnicas de cuarta generación. En lugar de crear software con lenguajes de programación de tercera generación, el proceso DRA trabaja para volver a utilizar componentes de programas ya existentes (cuando es posible) o a crear componentes reutilizables (cuando sea necesario). En todos los casos se utilizan herramientas automáticas para facilitar la construcción del software.
 * ***Prueba y entrega:*** Como el proceso DRA enfatiza la reutilización, ya se han comprobado muchos de los componentes de los programas. Esto reduce tiempo de pruebas. Sin embargo, se deben probar todos los componentes nuevos y se deben ejercitar todas las interfaces a fondo.

**Orientados a la reutilización**

<span class="image left"><img src="{{ 'assets/images/reutilizacion.png' | relative_url }}" alt="" /></span>

**Definición:**

Esta aproximación se basa en la existencia de un número significativo de elementos reutilizables. El proceso de desarrollo, se centra en la integración de estos elementos en un sistema, en lugar de desarrollarlo desde cero.

Incorpora muchas características del modelo en espiral. Es evolutivo por naturaleza. 

El proceso tiende a estructurarse en dos subprocesos distintos y separados: 
 * ***El desarrollo para reutilización:*** construcción de elementos reutilizables dentro de un dominio concreto.
 * ***El desarrollo con reutilización:*** construcción de aplicaciones utilizando elementos reutilizables.

Etapas del proceso 
 * Análisis de los componentes; 
 * Requisitos de modificación; 
 * Configuración del sistema con la reutilización; 
 * Desarrollo e integración. 

La reutilización es ahora el enfoque estándar para la construcción de muchos tipos de sistemas de negocio 

**Orientado a Objetos (OO)**

<span class="image left"><img src="{{ 'assets/images/objetos.png' | relative_url }}" alt="" /></span>

**Definición:**

El modelo orientado a objetos utiliza el paradigma de la orientación a objetos para el desarrollo de software.

Este enfoque realiza la construcción de modelos de un sistema por medio de la identificación y la especificación de un conjunto de objetos relacionados, que colaboran entre si de acuerdo a los requerimientos establecidos para el sistema de objetos.

La definición del modelado orientado a objetos puede claramente dividir el enfoque en tres dimensiones: 
 * La dimensión estructural. 
 * La dimensión dinámica. 
 * La dimisión funcional. 

Este tipo de modelado implica la realización de las siguientes actividades: 
1. Identificar las clases, modelos y objetos. (objetos y atributos).
2. Asociar estáticamente los objetos. (relaciones dependientes del dominio del problema). 
3. Especificación del comportamiento de los objetos. (Definir como se comportaran los objetos). 
4. Definir la jerarquía de herencia de las clases. (Definir la jerarquía de clases, para que el sistema quede lo más abstracto posible).








