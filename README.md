# Proyecto: Generación de Mockup + plan de trabajo para Dashboard
* Creador: Javier Stumpf
* Diplomatura Intensiva en Data Sciences
* Comisión: IA Generacion de Prompts (71950)

# Resumen
Este proyecto tiene como objetivo optimizar el proceso de definición y desarrollo de dashboards en consultorías de datos mediante el uso de inteligencia artificial. A menudo, los clientes no tienen una visión clara de sus necesidades al solicitar un tablero, lo que genera ajustes constantes y prolonga el desarrollo.

Para abordar este problema, se propone una solución basada en IA que automatiza tres etapas clave:
* Definición de objetivos
* Generación de mockup
* Plan de trabajo

La solución se apoya en herramientas como Google Gemini, OpenAI DALL·E y Python, permitiendo mejorar la comunicación con el cliente, reducir tiempos de desarrollo y estructurar la planificación de manera eficiente. La IA se posiciona como un recurso clave para agilizar el diseño y conceptualización de dashboards sin reemplazar el criterio del consultor.

# Introducción
## Título
Generación de Mockup + plan de trabajo para Dashboard

## Presentación del Problema a Abordar
El trabajo como profesional independiente en el ámbito de los datos exige optimizar el tiempo para responder de manera eficiente a las demandas de los clientes y, al mismo tiempo, aportar valor mediante el desarrollo de tableros efectivos.

Uno de los principales desafíos es que los clientes, en muchas ocasiones, no tienen una idea clara de los resultados que desean obtener al contratar servicios de análisis de datos. Más allá de que el analista debe relevar información sobre su negocio, sus sistemas, bases de datos y objetivos estratégicos, es fundamental ordenar las ideas y proyectar soluciones concretas y tangibles que el cliente pueda visualizar.

Tener una representación clara del resultado final no solo facilita la toma de decisiones del cliente, sino que también agiliza el proceso de trabajo del analista, permitiéndole obtener información clave desde el inicio y reduciendo el tiempo dedicado a ajustes y reelaboraciones.

En este contexto, la inteligencia artificial puede ser una herramienta clave. La creación de prompts estructurados que guíen al cliente en la generación de mockups con IA puede ayudar a que visualicen rápidamente el tipo de tablero que necesitan. Esto permite que el cliente tenga un punto de referencia desde el inicio, facilitando la comunicación con el analista y acelerando el desarrollo de soluciones ajustadas a sus necesidades.

Este enfoque no solo aumenta la eficiencia del proceso, sino que también potencia la propuesta de valor del analista, al ofrecer un servicio más dinámico, visual y alineado con las expectativas del cliente, además de generar un plan de acción detallado para potenciar los resultados.

## Desarrollo de la propuesta de solución

### Parte 1: Definición de objetivo del Dashboard

Se busca que el cliente cargue su base de datos a trabajar y establezca una idea inicial del objetivo de un tablero, qué pretende medir con el mismo, cuáles son sus prioridades y qué necesidades posee.

1.  En primera instancia, se le solicitará al cliente que introduzca la URL de Google Drive de la base de datos a trabajar.

2.  Luego, se debe efectuar la importación de la misma, para que sirva de input en los pasos siguientes.

3.  Por último, se le solicitará al cliente que ingrese sus necesidades y objetivos iniciales.

El resultado será:
* La base de datos cargada en Python
* El planteo de 3 objetivos estratégicos a trabajar

En esta parte se trabajará con un modelo de Texto a texto, utilizando la herramienta Gemini.

### Parte 2: diseño de un mockup del Dashboard

En base al objetivo del cliente, las especificaciones sobre el tablero y la base de datos que el mismo provea, se espera que el modelo arroje un mockup del Dashboard.

1.  Lo primero será generar un prompt para el mockup del dashboard, de acuerdo a lo que el cliente especifique, los datos aportados y los objetivos que se han definido en el paso anterior.

2.  El segundo paso será la generación de la imagen del mockup, utilizando como input el prompt generado.

El resultado final de esta etapa será:

* El prompt para generar el mockup
* La URL de la imagen del mismo

Se ultilizarán los modelos Texto a texto (utilizando Gemini) y texto a imagen (generado con OpenAI).

### Parte 3: Elaboración de un plan de trabajo para el desarrollo del Dashboard

La etapa final del proceso está abocada al desarrollo de un plan de trabajo sugerido para la creación del Dashboard en base a lo trabajado anteriormente (objetivos y prompt del dashboard) y las definiciones de recursos por parte del cliente (duración y personas involucradas).

El resultado será un plan de trabajo sugerido, detallando fases, duración, recursos y cronograma en semanas.

Se utilizará un modelo texto a texto, a través de la herramienta Gemini.

## Justificación de la Viabilidad del Proyecto
La viabilidad del proyecto se sustenta en:

* Disponibilidad de herramientas de IA: Se utilizan modelos accesibles como Gemini (para generación de texto) y OpenAI (para generación de imágenes).

* Implementación rápida: Solo es necesario diseñar prompts adecuados para guiar al cliente en la descripción de su tablero y generar los outputs correspondientes.

* Automatización del proceso: Al reducir la intervención manual, el proyecto se vuelve eficiente y escalable.

* Flexibilidad y personalización: La solución se adapta a diferentes sectores y necesidades de los clientes.

* Optimización del tiempo: Permite que el cliente visualice su tablero antes de desarrollarlo, evitando ajustes innecesarios y mejorando la comunicación con el analista.

* Baja inversión en recursos: No se requiere infraestructura propia, ya que las herramientas funcionan en la nube.

# Objetivos
1.  Automatizar la importación de bases de datos desde Google Drive a Python.

2.  Definir de manera estructurada los objetivos estratégicos de un dashboard según las necesidades del cliente.

3.  Generar un mockup visual del dashboard que sirva como referencia para su desarrollo final.

4.  Diseñar un plan de trabajo estructurado para la implementación del dashboard en Power BI.

# Metodología
El proyecto se desarrollará en tres etapas:

1. Carga de datos y definición de objetivos:
   
   a. Carga de datos: Se solicitará al cliente un enlace de Google Drive y se generará automáticamente el código de importación.

   b. Definición de objetivos: Mediante un modelo de IA, se analizarán las necesidades del cliente para definir tres objetivos estratégicos.

2. Generación de mockup: Se creará un prompt detallado y una imagen representativa del dashboard.

3. Plan de trabajo: Se generará un cronograma con fases, recursos y duración estimada para la implementación.

# Herramientas y Tecnologías

* Google Gemini: Para generación de texto (definición de objetivos y plan de trabajo).

* OpenAI DALL·E: Para generación de imágenes (mockup del dashboard).

* Pandas: Para manipulación y análisis de datos.

* Python: Lenguaje de programación principal.

* Power BI: Herramienta de visualización para la implementación final del dashboard.

# Implementación
Se encuentra en el archivo Entrega_final_IA_Stumpf.ipynb del presente repositorio.

# Resultados

La implementación de este proyecto permite:

* Automatizar la carga de datos desde Google Drive.

* Definir objetivos estratégicos de manera eficiente con IA.

* Generar un diseño preliminar del dashboard, facilitando la comunicación con el cliente.

* Planificar la implementación con un plan de trabajo detallado.


  # Conclusiones
Este proyecto demuestra el potencial de la IA en la automatización de procesos relacionados con la inteligencia de negocios. Se logró optimizar la definición de objetivos y el diseño inicial de dashboards, reduciendo el tiempo de desarrollo. La solución es adaptable y escalable para diversas industrias, lo que abre la posibilidad de futuras mejoras y expansión en su aplicación.

En líneas generales, el desarrollo cumple con lo esperado. Si bien, se encuentran limitaciones en la generación de imágenes, se debe tener como un recurso más para apoyar a la creación del tablero. 

Además, se debe comprender que la inteligencia artificial es una herramienta que facilita los procesos en base a predicciones, por ello no siempre será acertado el resultado. En conclusión, no reemplaza el trabajo del consultor, sólo permite darle forma al proyecto de manera ágil y automatizada. 

