# ChallengeTeorico 📋

## ¿Qué es y para qué utilizar el code review?

Es una práctica de desarrollo, donde los distintos miembros de un equipo revisan en conjunto la implementación realizada por otro miembro para un requerimiento de algún proyecto, aportando ideas sobre mejoras en la implementación, posibles refactorizaciones, discusión de posibles bugs, optimizaciones, errores o mejoras de arquitectura. Se utiliza para mejorar la calidad del código y para crear una cultura de equipo.

Otros motivos destacables:
- Compromiso y motivación.
- Comunicación y conocimiento compartido.
- Aprendizaje.
- Consistencia.

## ¿Cuáles son los niveles de acceso y cómo funcionan?

- `public`: Acceso desde dentro y fuera de la clase.
- `private`: Acceso solo desde dentro de la clase.
- `protected`: Acceso dentro de la clase o desde clases heredadas.

## ¿Qué patrones de arquitectura conoces y cómo funcionan?

Un `patrón arquitectónico` es una solución general y reutilizable a un problema común en la arquitectura de software.

- ### Patrón de capas:
Es un patrón que se utiliza para dividir sistemas de software complicados en capas, donde cada capa tiene un papel y una responsabilidad específica dentro de la aplicación.
- ### Patrón cliente-servidor:
Este patrón consiste en dividir un sistema en dos niveles o programas, donde un programa (cliente) realiza peticiones a otro programa (servidor), y este le da una respuesta.
- ### Modelo Vista Controlador (MVC):
Este patrón divide una aplicación en 3 partes:

 `Modelo`: Contiene la funcionalidad y los datos básicos.
 
 `Vista`: Muestra la información al usuario.
 
 `Controlador`: Maneja la entrada del usuario.
 
- ### Modelo Vista Vista Modelo (MVVM):
Este patrón es parecido al MVC con la diferencia de que el controlador desaparece y la vista pasa a ser capaz de gestionar las acciones indicadas por el usuario.

## ¿Qué patrones de diseño conoces y cómo funcionan?
Los `patrones de diseño` son técnicas para resolver problemas comunes en el desarrollo de software.

- ### Patrones creacionales:

 `Singleton`: Asegura que solo haya una instancia de una clase.
 
 - ### Patrones estructurales:

 `Decorator`: Este patrón restringe la alteración de la estructura del objeto mientras se le agrega una nueva funcionalidad.
 
 `Injection`: Es un patrón de diseño en el que una clase solicita dependencias de fuentes externas en lugar de crearlas.
 
 - ### Patrones de comportamiento:

 `Observer`: Define una dependencia de uno-a-muchos entre objetos, de forma que cuando un objeto cambie de estado se notifique y actualicen automáticamente todos los objetos que dependen de él.
 
 `State`: Permite que un objeto modifique su comportamiento cada vez que cambie su estado interno.
 
 ## ¿Qué es SOLID?
 
 Los principios SOLID son eso: principios, es decir, buenas prácticas que pueden ayudar a escribir un mejor código: más limpio, mantenible y escalable.
 
 SOLID está muy relacionada con la comprensión y el uso de patrones de diseño, que nos permitirán mantener un bajo acoplamiento de software.
 
 Los cinco principios de SOLID para el diseño de aplicaciones de software son:
 
 - `S`: Principio de responsabilidad única.
 - `O`: Principio abierto / cerrado.
 - `L`: Principio de substitución de Liskov.
 - `I`: Principio de segregación de interfaz.
 - `D`: Principio de inversión de dependencia.

## POO: ¿Qué es una clase?

Una clase es una plantilla para la creación de objetos de datos según un modelo predefinido.

## POO: ¿Qué es y para qué se utiliza la herencia?

Es el mecanismo por el cual una clase permite heredar las características (atributos y métodos) de otra clase.

Se utiliza para definir nuevas clases basadas de unas ya existentes a fin de reutilizar el código, generando así una jerarquía de clases dentro de una aplicación.

## ¿Qué es y para que se utilizan las interfaces?

Una interfaz es un contrato entre dos entidades, la interfaz provee un servicio a una clase consumidora. Por ende, la interfaz solo nos muestra la declaración de los métodos que esta posee, no su implementación.

Se utiliza para asegurar que una clase haga uso de las declaraciones que se le ofrece la interfaz.

## ¿Qué es el polimorfismo?

Es la capacidad que tienen los objetos de una clase en ofrecer respuesta distinta e independiente en función de los parámetros (diferentes implementaciones) utilizados durante su invocación.

## ¿Qué es y cómo funciona una API web?

Es una interfaz que un software utiliza para interactuar con otro software y funciona a través del protocolo HTTP.

## Test driven development

Es una práctica de ingeniería de software que involucra otras dos prácticas: Escribir las pruebas primero y Refactorización.
