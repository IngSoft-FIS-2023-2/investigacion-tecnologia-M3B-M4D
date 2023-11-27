# Estrategia de Testing Exploratorio

## Fuentes

- **Abstracta:**
  - [Testing Exploratorio en Entorno Ágil](https://cl.abstracta.us/blog/testing-exploratorio-entorno-agil/)
  - Publicado: 08/04/2020
  - De: Abstracta team

- **Globe:**
  - [Pruebas Exploratorias](https://ahorasomos.izertis.com/globetesting/2012/03/pruebas-exploratorias/)
  - Publicado: *no se aclara en el sitio*
  - De: Aitor de la Puente

## Definiciones

- **Testing Exploratorio:**
  - El testing exploratorio es un enfoque de prueba de software que se basa en la experiencia y habilidades del probador para descubrir defectos en lugar de seguir un conjunto de pasos de prueba predefinidos.

- **Flexibilidad y creatividad:**
  - Los probadores exploratorios tienen la libertad de diseñar pruebas en función de su comprensión del sistema, sus habilidades y experiencia.

- **Adaptabilidad:**
  - Los probadores pueden ajustar sus estrategias y enfoques de prueba sobre la marcha según lo que descubran durante el proceso de prueba.

- **Conocimiento del Dominio:**
  - La comprensión profunda del sistema y su contexto.

- **Pruebas Simultáneas:**
  - Los probadores pueden ajustar su enfoque en tiempo real en función de los resultados de las pruebas anteriores.

- **Mejora Continua:**
  - A medida que se descubren defectos, el probador puede profundizar en esas áreas específicas para identificar problemas adicionales o relacionados.

- **Documentación Ligera:**
  - Documentación de pruebas realizadas.

- **Requisitos Cambiantes o Incompletos:**
  - En proyectos donde los requisitos cambian con frecuencia o no están completamente definidos, el testing exploratorio permite a los probadores adaptarse rápidamente a los cambios y explorar áreas críticas sin depender de documentación exhaustiva.

- **Desarrollo Ágil:**
  - En entornos ágiles, donde el desarrollo es iterativo y se espera una entrega continua, el testing exploratorio se alinea bien con los principios ágiles.

- **Exploración de Nuevos Productos o Funcionalidades:**
  - Cuando se introduce un nuevo producto o una nueva funcionalidad, el testing exploratorio puede ayudar a identificar rápidamente posibles problemas y áreas de mejora sin depender de casos de prueba predefinidos.

- **Detección Temprana de Defectos:**
  - El testing exploratorio es efectivo para la detección temprana de defectos, ya que permite a los probadores utilizar su conocimiento y experiencia para explorar áreas críticas del software y encontrar problemas antes de que se vuelvan más costosos de corregir.

- **Pruebas de Usabilidad:**
  - Para evaluar la usabilidad del software, es importante realizar pruebas exploratorias para simular cómo los usuarios reales interactúan con el sistema.

- **Escenarios de Prueba Complejos o No Documentados:**
  - En situaciones donde los escenarios de prueba son complejos o no están bien documentados, el testing exploratorio permite a los probadores adaptarse y explorar diferentes caminos sin restricciones estrictas.

## Sesión de Testing en Clase

- **Título de la Sesión:** Exploración de las funcionalidades con números

- **Fecha y Hora:** 20/11/2023 [Hora]

- **Objetivo de la Sesión:** Explorar las funcionalidades con números para identificar posibles problemas y mejorar la experiencia del usuario.

- **Miembros del Equipo:** La clase

- **Área de Enfoque:** La sesión se centrará en las funcionalidades con números.

- **Estructura de división:**
  - **Duración:** 5 minutos
  - **Diseño y ejecución de pruebas (80%):**
    - Ingresar números en la funcionalidad de duplicar números: ingresar números positivos y negativos.
    - Ingresar datos que no sean números en la funcionalidad de duplicar números: ingresar letras o caracteres especiales.
    - Ingresar números en la funcionalidad de calcular factorial: ingresar números positivos y negativos.
    - Ingresar datos que no sean números en la funcionalidad de calcular factorial: ingresar letras o caracteres especiales.
  - **Investigación y reporte de defectos (20%):**
    - Defecto #001: Duplicar números acepta letras y caracteres especiales
      - Gravedad: Baja
      - Pasos para Reproducir: Ingresar datos que no sean números en la funcionalidad de duplicar números
    - Defecto #002: Resultado incorrecto para números negativos al calcular factorial
      - Gravedad: Alta
      - Pasos para Reproducir: Ingresar números negativos en la funcionalidad de calcular factorial
    - Defecto #003: Calcular factorial acepta letras y caracteres especiales
      - Gravedad: Baja
      - Pasos para Reproducir: Ingresar datos que no sean números en la funcionalidad de duplicar números
    - Defecto #004: La web no es responsive
      - Gravedad: Media
      - Pasos para Reproducir: Achicar en alto o ancho el navegador hasta ver los errores

- **Recomendaciones de uso:**
  - En la página se muestran 3 caminos: un input que recibe un número y te muestra su duplicado, un input que recibe un número y te devuelve su factorial y un input que recibe un string que te da su invertido. El sistema es sencillo y está diseñado para ser fácil y rápido de demostrar en clase. Se recomienda probar un input por vez, ya que la prueba de varios o todos los inputs al mismo tiempo puede dejar pasar errores clave. Siempre se debe dirigir la concentración a un lugar específico.

- **Recursos de aprendizaje:**
  - Para la presentación de la prueba se utilizó Visual Studio Code, y su función de Live preview para probarlo pre presentación. El día de la presentación, simplemente se abrió el archivo `index.html` en el navegador. Para la creación de la presentación teórica, se utilizó la función de presentaciones de Google Drive.
  - Link a la presentación: [Presentación en Google Drive](https://docs.google.com/presentation/d/1YzjtTLc7w6XhrWhy68oObBe2cRUfvGFbR3Ol8O7sGdE/edit#slide=id.p)