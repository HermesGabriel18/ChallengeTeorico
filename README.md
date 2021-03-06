# ChallengeTeorico 馃搵

## 驴Qu茅 es y para qu茅 utilizar el code review?

Es una pr谩ctica de desarrollo, donde los distintos miembros de un equipo revisan en conjunto la implementaci贸n realizada por otro miembro para un requerimiento de alg煤n proyecto, aportando ideas sobre mejoras en la implementaci贸n, posibles refactorizaciones, discusi贸n de posibles bugs, optimizaciones, errores o mejoras de arquitectura. Se utiliza para mejorar la calidad del c贸digo y para crear una cultura de equipo.

Otros motivos destacables:
- Compromiso y motivaci贸n.
- Comunicaci贸n y conocimiento compartido.
- Aprendizaje.
- Consistencia.

## 驴Cu谩les son los niveles de acceso y c贸mo funcionan?

- `public`: Acceso desde dentro y fuera de la clase.
- `private`: Acceso solo desde dentro de la clase.
- `protected`: Acceso dentro de la clase o desde clases heredadas.

## 驴Qu茅 patrones de arquitectura conoces y c贸mo funcionan?

Un聽`patr贸n arquitect贸nico`聽es una soluci贸n general y reutilizable a un problema com煤n en la arquitectura de software.

- ### Patr贸n de capas:
Es un patr贸n que se utiliza para dividir sistemas de software complicados en capas, donde cada capa tiene un papel y una responsabilidad espec铆fica dentro de la aplicaci贸n.
- ### Patr贸n cliente-servidor:
Este patr贸n consiste en dividir un sistema en dos niveles o programas, donde un programa (cliente) realiza peticiones a otro programa (servidor), y este le da una respuesta.
- ### Modelo Vista Controlador (MVC):
Este patr贸n divide una aplicaci贸n en 3 partes:

 `Modelo`: Contiene la funcionalidad y los datos b谩sicos.
 
 `Vista`: Muestra la informaci贸n al usuario.
 
 `Controlador`: Maneja la entrada del usuario.
 
- ### Modelo Vista Vista Modelo (MVVM):
Este patr贸n es parecido al MVC con la diferencia de que el controlador desaparece y la vista pasa a ser capaz de gestionar las acciones indicadas por el usuario.

## 驴Qu茅 patrones de dise帽o conoces y c贸mo funcionan?
Los `patrones de dise帽o` son t茅cnicas para resolver problemas comunes en el desarrollo de software.

- ### Patrones creacionales:

 `Singleton`: Asegura que solo haya una instancia de una clase.
 
 - ### Patrones estructurales:

 `Decorator`: Este patr贸n restringe la alteraci贸n de la estructura del objeto mientras se le agrega una nueva funcionalidad.
 
 `Injection`: Es un patr贸n de dise帽o en el que una clase solicita dependencias de fuentes externas en lugar de crearlas.
 
 - ### Patrones de comportamiento:

 `Observer`: Define una dependencia de uno-a-muchos entre objetos, de forma que cuando un objeto cambie de estado se notifique y actualicen autom谩ticamente todos los objetos que dependen de 茅l.
 
 `State`: Permite que un objeto modifique su comportamiento cada vez que cambie su estado interno.
 
 ## 驴Qu茅 es SOLID?
 
 Los principios SOLID son eso: principios, es decir,聽buenas pr谩cticas聽que pueden ayudar a escribir un mejor c贸digo: m谩s limpio, mantenible y escalable.
 
 SOLID est谩 muy relacionada con la comprensi贸n y el uso de聽patrones de dise帽o,聽que nos permitir谩n mantener un聽bajo acoplamiento聽de software.
 
 Los cinco principios de SOLID para el dise帽o de aplicaciones de software son:
 
 - `S`: Principio de responsabilidad 煤nica.
 - `O`: Principio abierto / cerrado.
 - `L`: Principio de substituci贸n de Liskov.
 - `I`: Principio de segregaci贸n de interfaz.
 - `D`: Principio de inversi贸n de dependencia.

## POO: 驴Qu茅 es una clase?

Una聽clase聽es una plantilla para la creaci贸n de objetos de datos seg煤n un modelo predefinido.

## POO: 驴Qu茅 es y para qu茅 se utiliza la herencia?

Es el聽mecanismo por el cual una clase permite heredar las caracter铆sticas (atributos y m茅todos) de otra clase.

Se utiliza para definir nuevas clases basadas de unas ya existentes a fin de reutilizar el c贸digo, generando as铆 una jerarqu铆a de clases dentro de una aplicaci贸n.

## 驴Qu茅 es y para que se utilizan las interfaces?

Una interfaz es un contrato entre dos entidades, la interfaz provee un servicio a una clase consumidora. Por ende, la interfaz solo nos muestra la declaraci贸n de los m茅todos que esta posee, no su implementaci贸n.

Se utiliza para asegurar que una clase haga uso de las declaraciones que se le ofrece la interfaz.

## 驴Qu茅 es el polimorfismo?

Es la capacidad que tienen los objetos de una clase en ofrecer respuesta distinta e independiente en funci贸n de los par谩metros (diferentes implementaciones) utilizados durante su invocaci贸n.

## 驴Qu茅 es y c贸mo funciona una API web?

Es una interfaz que un software utiliza para interactuar con otro software y funciona a trav茅s del protocolo HTTP.

## Test driven development

Es una pr谩ctica de ingenier铆a de software que involucra otras dos pr谩cticas: Escribir las pruebas primero y Refactorizaci贸n.
