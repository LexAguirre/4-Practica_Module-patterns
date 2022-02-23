![Logo](img/ucol-logo.jpg)

# Práctica 4: Module Patterns

> Primera Parcial

- FACULTAD DE TELEMATICA
- INGENIERÍA EN SOFTWARE
- “4ºG”
- ESTRUCTURA DE DATOS
- CATEDRATICO: ULIBARRI IRETA CARLOS
- AGUIRRE ROMERO RAMÓN ALEJANDRO

## OBJETIVO

- text

> ENTREGA: DOMINGO 27 DE FEBRERO DEL 2022

## INFORMACIÓN ADICIONAL

Un módulo es un conjunto de código y de datos relacionados lógicamente. Encapsula (o encierra) detalles de la implementación (o sea, de la forma en cómo está escrito el código), de esta forma el que usa el módulo no necesita saber «cómo está hecho» el módulo, sino solamente «cómo se usa«. Y como sólo se necesita saber «cómo se usa» un módulo, lo único que se expone al mundo exterior es la forma de usarlo (tal como sucede con los paquetes que descargas de npmjs.com). Finalmente, combinando varios módulos se pueden crear aplicaciones mucho más grandes.

El código dentro de cada “módulo” es “self contained” y su ámbito de acceso es “protected”. No puedes acceder a ese código a menos que el módulo lo “exponga” de forma explícita mediante la función “module.exports’. El module.exports nos permite “exponer” cierto contenido de nuestro módulo a un ámbito diferente, de tal forma que se pueda tener acceso a sus funcionalidades desde cualquier otro módulo.

> Javascript Objects

Name/Value pairs: a name which maps to a value, the name may be defined more than once but only can have one value in any given context (The value may be another name/value pair).

Un Javascript Object es: a collection of name value pairs
Que puede contener un objeto:

- Datos primitivos
- Funciones (method)
- Otros objetos

Object literal: Name/value pair separated by colons and surrounded by curly braces

## EXPLICACIÓN DEL PROCESO

1. Crear nuevo directorio “modules”

2. Crear un nuevo archivo app.js

3. Crear un nuevo archivo greet.js

4. Escribir "console.log("Hello from the module");" en el archivo greet.js y deja el archivo app.js vacio

5. Ahora en la linea de comando ejecuta "node app" y observa lo ocurrido

6. Ahora convierte el saludo del archivo greet.js

7. En app.js agregar la cláusula require del archivo greet.js

8. En la linea de comando ejecuta "node app" y observa lo ocurrido

9. Manda llamar la función "greet();" en el archivo app.js

10. En la linea de comando ejecuta "node app" y observa lo ocurrido

11. Ahora la capsula require conviertela en una variable

12. En el archivo greet.js en se colocará un "module.export = greet" para que pueda tener acceso al codigo del archivo greet.js

13. En la linea de comando ejecuta "node app" y observa lo ocurrido

14. En
