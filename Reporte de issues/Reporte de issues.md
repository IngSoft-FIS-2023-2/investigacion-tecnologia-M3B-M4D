### Franco Fagundez (283316) - Mauro Correa (287417) - Sebastian Menendez (283555)  

#Reporte de Issues  

##¿Que es un issue o bug?  

**Issue/Bug:** Término utilizado dentro de la informática y el desarrollo de software que hace referencia a los fallos o diferencias que se encuentran en el programa respecto a lo que se espera del mismo. Pueden ser desde errores pequeños hasta fallas graves que modifiquen los resultados del sistema o dañen la integridad del mismo.  

Los mismos pueden manifestarse también como comportamientos erráticos o inesperados del software, como por ejemplo, en vez de mostrar una parte de una página que muestre otra distinta. En general, el término refiere a cosas que no deberían ocurrir si el programa tuviese un correcto funcionamiento, cualquier cosa que afecte negativamente el rendimiento/comportamiento/resultado de un programa, será considerado un “bug” o un issue.  

Dichos issues deberán ser reportados por los tester para posteriormente ser tratados correctamente por los desarrolladores, siguiendo prácticas y protocolos designados por el equipo de trabajo. Una vez corregidos, se deberá verificar que realmente lo estén, y si así es el caso, se tomará al bug como arreglado. Si el error persiste, se debe volver a reportar y tratar.  

## ¿Qué es un reporte de issues?  

Es una parte fundamental del proceso de desarrollo de software, contiene los “bugs” o issues encontrados durante la revisión del código o los testeos realizados sobre el programa. Se describen los mismos con el detalle suficiente como para identificarlos y solucionarlos. Este documento debe ser detallado, específico, con evidencia adjunta sobre cada error encontrado y la información necesaria para identificarlo, además, debe ser objetivo y formal.  

##¿Cual es el propósito de un reporte de issues?  

El reporte de issues tiene múltiples propósitos en el ámbito del desarrollo de software como lo son los siguientes:  

-Favorecer la comunicación entre los integrantes del equipo
-Posibilitar la organización y jerarquización de las actividades
-Asistir a los desarrolladores en la identificación, comprensión y resolución de diversos fallos o conductas inesperadas del sistema.  
-Aumentar las probabilidades de que el bug sea solucionado eficientemente

##¿Qué información debe contener un reporte de issues?  

- Resumen (descripción breve del problema / título).
- Código de identificación del reporte (único).
- Estado (abierto/en proceso/cerrado).
- Plataforma.
- Descripción (descripción más detallada del problema).
- Prioridad (baja/media/alta).
- Datos de prueba (entradas y salidas).
- Severidad (su impacto en el software).
- Pasos a reproducir (guia de como ejecutar el problema).
- Resultado actual (el output que da).
- Resultado esperado (el output que debería dar).
- Adjuntos (fotos, videos, logs, etc…)
- Información de contacto del tester (nombre/email/teléfono)

##Problemas comunes en reportes de issues:

- Reporte muy coloquial.
- Reporte muy ambiguo / Falta detalle.
- No incluir en el reporte cuál era el resultado esperado de la falla.
- Escribir para uno mismo y no para el desarrollador.
- Criticar al desarrollador en vez de al programa.

##Causas de los problemas en reportes de issues:

-Falta de capacitación.
-Falta de tiempo.
-Falta de reglas/organización.

## Buenas prácticas al reportar un issue  

- Realizar una crítica constructiva al programa y no al desarrollador.
- Tener un nivel de detalles muy alto en el reporte.
- Evidenciar todo.
- Dar una buena clasificación.
- Que el reporte permita un buen rastreo y posterior verificación.
- Dejar tus datos como responsable del issue.
- Hacerlo pensando en el equipo de desarrollo.
- Que sea reproducible por el tester.
- Seguir la estructura dictaminada por tu grupo de trabajo.

##Ejemplo 1:  

**ID:** 1.  

**Título:** Error al registrar un equipo.  

**Estado:** Sin solucionar.  

**Plataforma/Ambiente:** Windows 10, Google Chrome, Notebook.  

**Descripción:** Al intentar registrar un equipo de fútbol y sus respectivos datos en la página web, se produce un error que no permite continuar con el proceso.  

**Pasos para reproducir el error:**  

1) Acceder a la página: https://www.paginadefutbolimaginaria.com
2) Clickear en “Registrar un equipo” en la barra superior.
3) Completar los campos requeridos por el sistema de manera correcta (nombre, cantidad de trofeos, año de fundación, información extra).
4) Clickear en “Registrar cuadro”.

**Resultado esperado:** El cuadro se agrega a la base de datos de la página junto a todos sus datos, reiniciando el formulario y dándonos una alerta de que se agregó satisfactoriamente.  

**Resultado actual:** El cuadro no se agrega a la base de datos, por lo cual no será tomado en cuenta posteriormente por ninguna operación, además, el formulario no se reinicia ni tampoco lanza la alerta requerida.  

**Capturas de pantalla:**

[Captura 1] - Captura del formulario  
[Captura 2] - Captura del formulario después de clickear “Registrar cuadro”.  

**Prioridad:** Alta.  

**Severidad:** Bloqueante.

**Fecha de reporte:** 30 de noviembre de 2023.  

**Autor:** Administrador 1.  

**Comentarios adicionales:** Solucionar lo antes posible, no permite realizar una de las funciones principales de la página.

##Ejemplo 2:  

**ID:** 2.  

**Título:** Problema al iniciar sesión, contraseña visible.  

**Estado:** En proceso de ser solucionado.  

**Plataforma/Ambiente:** Windows 10, Google Chrome, Notebook.  

**Descripción:** Al intentar iniciar sesión en la página, la información escrita en el campo “Password” es visible, cuando debería de ser del estilo “*******”.  

**Pasos para reproducir el error:**  

1) Acceder a la página: https://www.paginadefutbolimaginaria.com  
2) Clickear en “Login” en la barra superior.  
3) Completar los campos requeridos por el sistema de manera correcta (correo electrónico, contraseña).  
4) Clickear en “Ingresar”.  

**Capturas de pantalla:**  

[Captura 1] - Captura del formulario de login    
[Captura 2] - Captura del formulario con una contraseña genérica escrita en el input “password”.  

**Resultado actual:** La información del campo “password” es visible para todos.  

**Resultado esperado:** La información del campo “password” debe estar oculta/encriptada.  

**Prioridad:** Alta. 

**Severidad**: Bajo impacto.  

**Autor:** Administrador 2.  

**Comentarios adicionales:** Problema grave, supone vulnerabilidad en la información privada de los usuarios y debe ser solucionado cuanto antes.  

##Bibliografía

- Sommerville, I. (2011). Capitulo 8. In Ingenieria de Software 9 (Novena edicion, Vol. 9). essay, Pearson. 
- Kaner, C., Falk, J., Nguyen, H. Q. (1999). Testing Computer Software (Second Edition, Vol. 2). Wiley.
-Sarco, J. P. (2010, December 9). ¿CÓMO ESCRIBIR UN BUEN REPORTE DE FALLAS/BUGS?. Testing en español. https://josepablosarco.wordpress.com/2010/12/09/%C2%BFcomo-escribir-un-buen-reporte-de-fallasbugs/ 
- OpenAI. (2023). ChatGPT. https://chat.openai.com/

