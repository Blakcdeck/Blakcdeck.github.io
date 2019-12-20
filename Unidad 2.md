---
layout: post
title: PROYECTO INTRODUCCION INGENIERA SOFTWARE
---

## Unidad 2

![_config.yml]({{ site.baseurl }}/images/unidad2.gif)

### Ciclos de vida del Software
Cuando un proceso implica la construcción de algún producto, suele referirse al proceso como un ciclo de vida

### Se puede definir ciclo de vida del software como:

Las distintas fases por las que pasa el software desde que nace una necesidad de mecanizar un proceso hasta que deja de utilizarse el software que sirvió para ese objetivo, pasando por las fases de desarrollo y explotación [Frakes et al., 1991]

### Ámbito general del ciclo de vida del Software
Desde un punto de vista general puede considerarse que el ciclo de vida de un software tiene tres etapas claramente diferenciadas:

* Planificación
* Implementación
* Puesta en producción

### Objetivos de cada etapa
Expresión de necesidades: esta etapa tiene como objetivo el armado de un documento en el cual se reflejan los requerimientos y funcionalidades que ofrecerá al usuario el sistema a implementar (qué, y no cómo, se va a implementar). Especificaciones: formalizamos los requerimientos; el documento obtenido en la etapa anterior se tomará como punto de partida para esta etapa. Análisis: determinamos los elementos que intervienen en el sistema a desarrollar, su estructura, relaciones, evolución temporal, funcionalidades, tendremos una descripción clara de qué producto vamos a construir, qué funcionalidades aportará y qué comportamiento tendrá. Diseño: ya sabemos qué hacer, ahora tenemos que determinar cómo debemos hacerlo (¿cómo debe ser construido el sistema en cuestion?; definimos en detalle entidades y relaciones de las bases de datos, seleccionamos el lenguaje que vamos a utilizar, el Sistema Gestor de Bases de Datos, etc.). Implementación: empezamos a codificar algoritmos y estructuras de datos, de- finidos en las etapas anteriores, en el correspondiente lenguaje de programación o para un determinado sistema gestor de bases de datos. Debugging: el objetivo de esta etapa es garantizar que nuestro programa no contiene errores de diseño o codificación Validación: esta etapa tiene como objetivo la verificación de que el sistema desarrollado cumple con los requerimientos expresados inicialmente por el cliente y que han dado lugar al presente proyecto.

### Evolución: 
en la mayoría de los proyectos se considera esta etapa como Mantenimiento y evolución, y se le asigna, no sólo el agregado de nuevas funcionalidades (evolución); sino la corrección de errores que surgen (mantenimiento).
Razones para modelar un proceso de SW: • Ayuda al equipo de desarrollo a comprender dónde debe adaptarse el proceso • Los modelos de proceso de desarrollo de software incluyen los requisitos del sistema como entrada y un producto entregado como salida

### Modelo general de proceso en Ingeniería: 
• Especificación 
• Formulación de los requisitos y restricciones del sistema 
• Diseño 
• Elaboración de un documento con el modelo del sistema 
• Fabricación 
• Construcción del sistema 
• Prueba 
• Comprobación de que el sistema cumple las especificaciones requeridas 
• Instalación 
• Entrega del sistema al cliente y garantía de que es operativo 
• Mantenimiento 
• Reparación de los fallos que aparecen en el sistema

### En el proceso de construcción de sistemas informáticos se pueden distinguir tres fases genéricas:
• La definición: Se identifican los requisitos claves del sistema y del software Se desarrolla: 
• Un Análisis de Sistemas 
• Un Análisis de Requisitos • Esta fase está orientada al QUÉ

• El desarrollo: Fase orientada al CÓMO, el primer paso de esta fase corresponde al Diseño del Software.

• El mantenimiento: Fase de mantenimiento: Mantenimiento correctivo Corrección de errores Mantenimiento adaptativo Adaptaciones requeridas por la evolución del entorno del software Mantenimiento perfectivo Las modificaciones debidas a los cambios de requisitos del usuario para mejorar el sistema Mantenimiento preventivo Mejora de las características internas del producto para hacer más mantenible

### El proceso de SW:
Marco de trabajo de las tareas que se requieren para construir software de alta calidad. Modelos de procesos de software • El modelo de cascada Modelo de Plan-impulsado. Fases separadas y distintas de especificación y desarrollo. • El desarrollo incremental Especificación, desarrollo y validación se intercalan. Puede ser el plan impulsado o ágil.

### Modelo de Cascada
Las fases están identificadas por separado: • El análisis y definición de requerimientos • Diseño del sistema y software. • Pruebas de implementación de unidades • Integración y pruebas del sistema • Operación y mantenimiento

### Problemas del Modelo de Cascada:
El modelo de cascada se utiliza sobre todo para los grandes proyectos de ingeniería de sistemas en que un sistema se desarrolla en varios lugares Desarrollo incremental El costo de atender las necesidades cambiantes de los clientes se reduce. • La cantidad de análisis y la documentación que tiene que ser hecho de nuevo es mucho menor que la que se requiere con el modelo de cascada. Beneficios: • Más rápida entrega y despliegue de software de utilidad para el cliente es posible. • Los clientes pueden usar y obtener valor a partir del software anterior que es posible con un proceso de cascada. Problemas: • El proceso no es visible. • Los gerentes necesitan entregas regulares para medir el progreso. Si se desarrollan rápidamente los sistemas, no es rentable para producir documentos que reflejen todas las versiones del sistema.

### Espiral: 
Las actividades de este modelo son una espiral, cada bucle es una actividad. Actividades principales: • Primer Paso. Identificación de: • Los objetivos de la parte del producto que está siendo elaborada (rendimientos, funcionalidad, adaptación al cambio, etc.). • Segundo paso. • Evaluar las diferentes alternativas que se plantean teniendo en cuenta los objetivos a conseguir y las restricciones impuestas. Frecuentemente, este paso identifica las áreas de incertidumbre del proyecto con sus correspondientes riesgos. • Tercer paso. Consiste en desarrollar, verificar y validar (probar): • Tareas de la actividad propia y de prueba. • Análisis de alternativas e identificación resolución de riesgos • Cuarto paso. Revisar todo lo hecho, evaluándolo, y con ello decidir si se continúa con las fases siguientes y planificar la próxima actividad.

### Desarrollo Rápido de Aplicaciones (DRA)
Es un modelo de proceso del ciclo de vida clásico que enfatiza un ciclo de vida de desarrollo extremadamente corto.
• Modelado de gestión: El flujo de información entre las funciones de gestión se modela de forma que responda a las siguientes preguntas: ¿Qué información conduce el proceso de gestión? ¿Qué información se genera? ¿Quién la genera? ¿A dónde va la información? ¿Quién la procesa? • Modelado de datos: El flujo de información definido como parte de la fase de modelado de gestión refina como un conjunto de objetos de datos necesarios para apoyar la empresa. • Modelado de procesos: Los objetos de datos definidos en la fase de modelado de datos quedan transformados para lograr el flujo de información necesario para implementar una función de gestión • Generación de aplicaciones: El DRA asume la utilización de técnicas de cuarta generación. • Prueba y entrega: Como el proceso DRA enfatiza la reutilización, ya se han comprobado muchos de los componentes de los programas.

### Problemas: 
DRA no es adecuado cuando los riesgos técnicos son altos. Esto ocurre cuando una nueva aplicación hace uso de tecnologías nuevas, o cuando el nuevo software requiere un alto grado de interoperatividad con programas de computadoras ya existentes.

### Orientados a la reutilización: 
El proceso tiende a estructurarse en dos subprocesos distintos y separados: • El desarrollo para reutilización: construcción de elementos reutilizables dentro de un dominio concreto. • El desarrollo con reutilización: construcción de aplicaciones utilizando elementos reutilizables.

• Etapas del proceso 
• Análisis de los componentes; 
• Requisitos de modificación; 
• Configuración del sistema con la reutilización; 
• Desarrollo e integración

### Orientado a Objetos:
El modelo orientado a objetos utiliza el paradigma de la orientación a objetos para el desarrollo de software. Características: • EL modelado Orientado a Objetos está basado en el paradigma orientado a objetos. • Trata el almacenamiento de objetos (persistencia de los objetos).

### Procesos Ágiles: Cualquier proceso del software ágil se caracteriza por la forma en la que aborda cierto número de suposiciones clave  acerca de la mayoría de proyectos de software:

### Factores Humanos:
El desarrollo ágil se centra en los talentos y habilidades de los individuos, y adapta el proceso a personas y equipos específicos.” • Competencia. En un contexto de desarrollo ágil (así como en la ingeniería de software), la “competencia” incluye el talento innato, las habilidades específicas relacionadas con el software y el conocimiento general del proceso que el equipo haya elegido aplicar. • Enfoque común. Aunque los miembros del equipo ágil realicen diferentes tareas y aporten habilidades distintas al proyecto, todos deben centrarse en una meta: entregar al cliente en la fecha prometida un incremento de software que funcione. • Colaboración. La ingeniería de software (sin importar el proceso) trata de evaluar, analizar y usar la información que se comunica al equipo de software; crear información que ayudará a todos los participantes a entender el trabajo del equipo; y generar información (software de cómputo y bases de datos relevantes) que aporten al cliente valor del negocio.
