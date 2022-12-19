# Curso Gratis de Programación Básica
## ¿Qué objetivo cumple una función?
    Nos ayuda a reutilizar / encapsular fragmentos de código que se usarán constantemente. 
## 2. En programación, Backend es:
    Quien programa la conexión con el servidor y de datos   para el usuario
## 3. ¿Qué resultado obtenemos al tener z = Math.ceil(4.64);    
    5
## 4. Para el código:
```
var a = 10;
var b = "12";
var c = b + a;
```
## ¿Qué tipo de variable es c?
    String

## 5. ¿Qué hace la función document.write ?
    Nos ayuda a escribir directamente en nuestro HTML usando JavaScript. Por defecto, inserta un string dentro de la etiqueta Body 
## 6. ¿Para qué sirve console.log( )?
    Funciona para mostrar información dentro de la consola web
## 7. En el siguiente código, ¿Cuál es el resultado que se mostrará en la consola?
```
var billetes = [ [ 1 , 2 , 3 ] ,
              [ 4 , 5 , 6 ] ,
              [ 7 , 8 , 9 ] ];
console.log(billetes[1][2])
```
    6
## 8. Si ejecutas el siguiente código, qué se mostrara en consola
```
varvariable; 
if(variable) { console.log("funciona"); 
} 
else{ console.log("no funciona"); 
}
```
    Error: variable not defined
## 9. ¿Cuál es el valor que mostrará el console.log en el siguiente programa? 
```
var entrar = 0;
var altura = 101;
if( altura > 100 || altura < 50){
    entrar = 1;
}
else if(altura > 60 || altura < 40){
    entrar = 2;
}
console.log(entrar);
```
    1
## 10. Es la forma en la que se invoca un archivo externo de JavaScript desde nuestro HTML:
```
<script src = “archivo.js”></script>
```
## 11. ¿Para qué sirve la etiqueta <strong>?
    Hace que el texto tenga más importancia mostrandolo con negrita 
## 12. ¿Para qué se utiliza JavaScript?
    Para programar la interactividad de un sitio web
## 13. Si tengo el siguiente código
```
console.log(variable);
function declarar() { variable = 12; }
```
## ¿Qué se mostrará en la consola?
    Uncaught ReferenceError: variable is not defined(…) 

## 14. En programación, Frontend es:
    Quien programa la interacción con el usuario
## 15. Cuando quieres comenzar a dibujar en HTML ¿Qué etiqueta nos ayuda a crear un lienzo?
    canvas
## 16. Al ejecutar el siguiente código:
```
var contador = 2;
var na = "na";
while(contador)
{
    na += na;
    contador -= 1;
}
console.log(na + " Freddy ")
```
## ¿Qué se va a mostrar en consola? 
   nananana Freddy

## 17. Si tengo el siguiente código
```
declarar(); console.log(variable);
```
## ¿Qué se mostrará en la consola?
    Uncaught ReferenceError: declarar is not defined(…)

## 18. Son algunas reglas que tienen los nombres de las variables en JavaScript:
    Deben empezar con una letra y no pueden tener espacios
## 19. ¿Para qué se utiliza HTML?
    Para estructurar semanticamente el contenido de un sitio web
## 20. ¿Qué es el DOM?
    Document Object Model, es la forma en que internamente el navegador organiza todo el HTML dentro de una estructura de árbol 
## 21. ¿Para qué sirve la etiqueta <p>?
    Define un párrafo en HTML 
## 22. ¿Cuál es la estructura básica de un archivo de HTML5?
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset=“utf-8”>
    <title></title>
  </head>
  <body>
  </body>
</html>
```
## 23. En el siguiente código, ¿Cuánto vale la variable vida?
```
function pakiman(vida)
{
    vida = vida + vida;
    vida++;
    return vida;
}
var vida = 2;
vida = pakiman(vida);
```
    5
## 24. Es la forma de ejecutar la función "mover" cuando el usuario oprima cualquier tecla: 
    document.addEventListener("keydown", mover);
## 25. Si queremos declarar una variable llamada mensaje y asignarle el texto "Ya sé programar", lo hago con la opción:
    var mensaje = "Ya sé programar”;
## 26. ¿Para qué se utiliza CSS?
    Para definir los estilos de un sitio web
## 27. Al ejecutar el siguiente código:
```
var paki = {
    nombre: "Pakiman",
    ataque: 101
};
paki.ataque = paki.ataque * 2;
```
## ¿Cuánto equivale paki.ataque ?
    202
## 28. Para examinar el HTML de cualquier página con nuestro navegador, ¿Cuál es la herramienta que usamos?
    El Inspector de elementos (Inspect) o Ver código fuente de la página
## 29. ¿Para qué sirve la función “alert” en JavaScript y cómo se invoca?
    Dispara una ventana de alerta en el navegador, con el mensaje que configuremos; se ejecuta como: alert(“ Mi Mensaje ”);

## 30. ¿Para qué usamos la función prompt?
    Para recibir datos del usuario

## Extras
1 - ¿Por qué debemos ubicar la etiqueta <script> justo antes de que se cierre el <body>?
    Porque así nuestra página podrá mostrar algo antes de ejecutar el código
    
2 - ¿Cómo llamamos a los textos en la industria de la programación?
    String
    
3 - En programación da igual si escribimos código en mayúsculas o minúsculas, nuestra computadora 
    tiene suficiente sentido común para entenderlo.
    Falso. La programación es exacta en su sintaxis.

4 - ¿Qué etiqueta en HTML nos permite escribir código JavaScript?
    Script
    
5 - JavaScript es el único lenguaje que voy a aprender para mi carrera profesional en
programación.
    Falso. JavaScript es un gran lenguaje de programación. Muchos otros también aportarán a mi aprendizaje.

6 - ¿Cuál de las siguientes propiedades de CSS NO hace parte del modelo de caja?
    background
    
7 - ¿Qué es :hover en CSS?
    Una pseudo-clase.
    
8 - ¿Qué significa el “this” al momento de construir nuestra clase?
    La palabra clave “this” se refiere al objeto actual en el que se está escribiendo el código.
    
9 - ¿Qué son los arreglos?
    Son objetos que nos permiten guardar diferentes tipos de datos en una lista.

10 - ¿Para qué se utiliza el método .push?
    Es un método que se utiliza con los arreglos que nos permiten agregar uno o más elementos al final de arreglo 
    y nos regresa la nueva longitud del mismo

11 - ¿A qué nos referimos cuando decimos “Don't repeat yourself”?
    A un principio del desarrollo de software que nos recomienda evitar repetir nuestro código cuando estamos 
    trabajando una solución. Por ejemplo, al momento de crear funciones, lo ideal sería que se puedan reutilizar 
    a evitar copiar y pegar la misma función muchas veces.
    
12 - ¿Qué símbolos utilizo para guardar los elementos de un arreglo?
    Corchetes cuadrados [ ]

13 - ¿Qué es el método forEach? ¿Para qué sirve?
    Es un método que nos permite recorrer y realizar una función específica por cada uno de
    los elementos que se encuentren en un arreglo.
    
14 - ¿Cúal es la etiqueta que nos permite dibujar en el navegador?
    <canvas>
        
15 - ¿Para obtener el contexto del canvas usamos getContext()?
    verdadero
        
16 - ¿Cómo agregamos una imagen a un canvas?
    drawImage()

17 - ¿Cómo logramos que una función se ejecute cada cierto tiempo?
    setInterval()
        
18 - ¿Qué es Node.js?
    Es el intérprete que nos permite ejecutar JavaScript fuera del navegador.

19 - ¿Cuál es el protocolo que nos permite solicitar y recibir recursos en la web?
    HTTP o HyperText Transfer Protocol
        
20 - ¿Para qué sirve el dominio o la IP?
    Para identificar a una computadora en una red de internet.
        
21 - ¿Para qué sirve el puerto después de la IP?
    Es como un canal que indica con qué programa nos estamos comunicando}

22 -  ¿Qué significa JSON?
    JavaScript Object Notation

        
------

Este proyecto sigue la especificación de [todos los contribuyentes](https://github.com/all-contributors/all-contributors) . ¡Contribuciones de cualquier tipo son bienvenidas!
