# ¿Qué es Node.js?
Node.js es un entorno de ejecución de un solo hilo y multiplataforma basado en el motor V8 de JavaScript de Google Chrome. 
Es un software de código abierto para construir aplicaciones de red escalables y en tiempo real.

## HISTORIA

La historia de Node.js comienza en 2009 cuando Ryan Dahl, un ingeniero de software, presentó por primera vez Node.js en el evento 
"JSConf EU" en Berlín. La idea detrás de Node.js surgió de la frustración de Dahl con los servidores web tradicionales que 
utilizaban el modelo de hilos, que a menudo resultaba en un rendimiento deficiente y problemas de escalabilidad.

Ryan Dahl quería construir un entorno de servidor que pudiera manejar múltiples solicitudes concurrentes de manera eficiente 
y escalable. Para lograr esto, eligió utilizar el motor V8 de Google Chrome, que es un motor de JavaScript de alto rendimiento. 
Este poderoso motor puede ejecutar JS a una velocidad impresionante y su ejecucion es independiente de los navegadores,
una ventaja que aprovecho Dahl incorporandolo al nucleo de node.
Dahl desarrolló una capa de red y E/S sobre el motor utilizando el lenguaje de programación C++, y lo llamó "Node.js".

## VERSIONES

[NodeJS](http://nodejs.org/es/download) pagina de descarga

Existen 2 versiones para descargar:
- LTS (Long Term Support) recomendada para mayoria de usuarios
- Actual (Ultimas caracteristicas)
                    
Estan disponibles para Windows, MacOS, Linux y varias opciones mas.
Para saber si ya esta instalado en nuestro equipo, chequeamos en el command prompt, usando los comandos node --version.

## APLICACIONES de Node.js

Node es usado para desarrollo de backend y desarrollo de APIs.

- Desarrollo backend: desarrollo de la parte de los servidores que interactuan con el navegador y la base de datos.
- APIs: Application Programming Interface, un intermediario entre los distintos programas. Nos permite conectar la aplicacion que se esta ejectando con el servidor, para acceder a la base de datos o realizar procesos en el servidor mismo.

## ORIENTADO A EVENTOS ASINCRONICOS

Node realiza las tareas de forma asincronica. 
Un evento asincrono es un evento que se ejecuta independientemente del proceso principal de la aplicacion.
Cuando Node recibe una tarea costosa en tiempo, no se detiene a esperar la respuesta sino que sigue ejecutando las siguentes lineas
de codigo mientas no recibe la respuesta. 

## ¿POR QUÉ USAR Node.js?

Nos permite desarrollar aplicaciones escalables y de tiempo real.

Aplicaciones Escalables:
- Su rendimiento se puede adaptar a medida que crece el uso de la aplicacion y recibe mas solicitudes.
    Nuestra aplicacion puede tener un promedio de 1000 visitas al dia, pero en algun momento en particular 
    esta cantidad se puede multiplicar y la aplicacion debe responder de forma veloz y correcta.

Aplicaciones en  tiempo real: 
- Establece una conexion bidireccional y dinamica entre el servidor y el cliente.
    El cliente puede pedir informacion y el servidor se la devuelve.
    La aplicacionanaliza los eventos que ocurren y reaccionea de forma casi inmediata.

## MODULOS en Node.js

Un modulo es una funcionalidad organizada en uno o varios archivos JavaScript que puede ser reutilizada en una aplicacion.
Esta es la principal razon de organizar en modulos, reutilizar codigo.
Ventajas: 
- Evitar repetir codigo
- Es mas facil encontrar y corregir 'bugs'
- Es mas facil modificar el codigo
- Es mas facil agregar nuevas funcionalidades

Los modulos se importan/exportan para dar acceso a las funcionalidades que definen
- exportar -> module.exports.funcionalidad
- importar -> const funcion = require('./archivo.js')

Node ya trae modulos incorporados (Built-in) que se pueden usar directamente como http, https, fs(file System), OS, path, console.
Y hay otros modulos crados por otros desarrolladores que se pueden importar desde internet. Para esto cuenta con NPM.
NPM es el ecosistema de paquetes de Node.js. Es el mayor ecosistema de todas las bibliotecas de código abierto del mundo, 
con más de un millón de paquetes y creciendo. El uso de NPM es gratuito y miles de desarrolladores de código abierto 
contribuyen a él diariamente.

# NPM

Node Package Manager o NPM es el gestor de paquetes de JavaScript que está integrado con NodeJS y es una de sus claves de éxito.
NPM tiene 3 componentes estructurales:  
- 	Website: Entorno donde los desarrolladores pueden crear perfiles y subir paquetes realizados por ellos o descubrir nuevos
-	Registry: Base de datos pública donde puedes acceder a todos los paquetes que ofrece NPM. Cabe destacar que el registro además mantiene información sobre el versionado de cada paquete además de sus dependencias y información sobre el autor, etc.
-	CLI(Command Line Inteface): Entorno de línea de comando generalmente usado por los desarrolladores para interactuar con los distintos paquetes de NPM. Ofrece opciones como instalar/desinstalar paquetes, crear nuevos paquetes y gestionar dependencias dentro de los proyectos.

## Exito de NPM
Cabe destacar que uno de los grandes éxitos de NPM es poder compartir con otros usuarios los paquetes, fomentando la ayuda y colaboración general entre la comunidad para asi lograr por ejemplo, que no necesites comenzar de 0 para realizar un paquete ya que puedes importar el trabajo realizado por otro, optimizando tu desempeño.

## Aplicacion de manera independiente
NPM además puede utilizarse de manera independiente, es decir sin el uso de NodeJS, para darle al desarrollador un mayor grado de libertad para decidir cómo encarar su proyecto.
El manejo de versiones, como fue mencionado anteriormente, permite al desarrollador poder elegir entre la versión más actual de un paquete, hasta la que sea compatible con su proyecto.

## Gestionado de dependencias
Otra funcionalidad clave de NPM es el gestionado de dependencias dentro del proyecto, esto refiere a que, por ejemplo: si un sector de desarrollo no requiere de cierto paquete, NPM permite manejar ese tipo de dependencias de tal manera que solamente se asignaran los paquetes necesarios para cada sector de desarrollo.

### Referencias

[Node](https://nodejs.org/en/docs)

[Node Wikipedia](https://en.wikipedia.org/wiki/Node.js)

[NPM](https://docs.npmjs.com/)

## Recomendaciones de uso

Recomendamos el uso tanto de nodeJS como de NPM cuando se requiera de un entorno de desarrollo web para producir a corta/media/gran escala productos de software web, donde estos facilitan la implementacion a su vez que los hacen mas practico y adaptable a cualquier dispositivo.

## Recursos de aprendizaje

- Manejo de evento asincronos
- Gestion de dependencias dentro un proyecto
- Manejo de modulos en node
- Escalibilidad de la aplicacion de NodeJS y NPM en empresas de desarrollo front-end
