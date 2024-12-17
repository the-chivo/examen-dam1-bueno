# Teoria

Realiza el examen directamente sobre el archivo!

Este examen solo muestra algunos conceptos al azar que me parecen importantes, hay muchos!

Intenta añadir código cuando lo necesites utilizando

```lenguaje
codigo
```

1. ¿Que diferencia una variable creada con `let` de una creada con `const`?

    Let una vez declarado solo es accesible dentro del propio bloque de codigo donde se creó, estas si pueden ser modificadas y const tambien tienen alcance de bloque pero no pueden ser modificadas una vez declaradas
    
2. ¿Qué es un dato primitivo? ¿y un objeto?

 dato basico que no esta compuesto por otros datos, se usan para almacenar datos y no tienen metodos ni propiedades asociadas. Los objetos son estructuras de datos que pueden contener porpiedades y metodos, se puede operar sobre sus propiedades.
 
2. ¿Qué diferencia hay entre `==` y `===`?

el == compara dos valores aunque no sean del mismo tipo, java los iguala para intentar compararlos, y el === los compara y debe de ser estrictamente el mismo dato y el mismo tipo.

3. Analiza el siguiente código, ¿qué valor se mostrará en la consola?
```js
let a = 1;

function mi_funcion() {
    let a = 2;
}

mi_funcion();
console.log(a);
```
se mostrara 1

4. ¿Qué es el DOM? Explícalo brevemente.

 Representacion estructurada de un documento html en un arbol de objetos. Permite modificar la estructura de una pagina de manera dinamica y mas sencilla.
5. ¿Este código es correcto? Si no lo es, ¿por qué?

```js
const boton = document.querySelector('button');
function saluda() {
    console.log('Hola');
}
boton.addEventListener('click', saluda());
```
no, el problema esque el parentesis de saluda esta haciende que se ejecute la funcion saludar al iniciar el codigo y no al dar click, la solucion seria retirar el parenetesis de saluda
(solo quitar el parentesis de saluda en la ultima linea)

6. ¿Que formas de seleccionar elementos del DOM conoces? ¿Cuál es la diferencia entre ellas?

 GetElementById() : selecciona el unico elemento con el id asignado
 getElementsByClassName(): Selecciona todos los elementos con una clase especifica
 getElementByTagName(): Selecciona todos los elementos con el tag especificado
 query.Selector(): Selecciona el primer elemento que encuentre con el selector seleccionado, el selector puede ser id, clase...
 querySelectorAll(): lo mismo que el query.selector pero este los selecciona todos.
 
7. ¿Qué es un evento? ¿Qué formas conoces de crearlos?

 Cualquier accion o suceso que ocurre en el navegador y que puede ser detectada y gestionada a traves de programacion. Que yo conozca el addListenerEvent(), el setTimeOut() y setInterval()
 
8. ¿Como se añade una libreria externa a un proyecto de JavaScript? Puedes usar p5 como referencia.
```
<script>src = "direccion_libreria"<script>
```

9. ¿Que es esto? `<meta charset="UTF-8">` ¿Por qué es importante?

proporciona informacion sobre el documento, especifica la codificacion de caracteres. Si no se especifica el ordenador interpretara incorrectmente ciertos caracteres como eñes o tildes.

10. ¿Que es una función? Explica brevemente su sintaxis en el lenguaje que prefieras.

Un bloque de codigo que se puede definir para luego ejecutar o llamar cuando quieras.
La explicare en c#
public void hola(){print("hola mundo"}
Public: Marca si la funcion es privada o publica, en este caso publica, lo cual determina si es accesible o no dentro de otro bloque de codigo.
Void: determina si la funcion devolvera un valor o no, en este caso con void no lo devuelve
Hola: Es el nombre que se ha asignado a esa funcion
(): Sirve para definir parametros dentro de la funcion si asignas uno dentro, o simplemente para definir que es una funcion.
{}: Dentro va el codigo que ejecutara la funcion cuando sea llamada.
