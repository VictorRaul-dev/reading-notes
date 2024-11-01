### ¿Qué es “Control Flow” (Control de Flujo)?

El **Control de Flujo** se refiere a cómo se ejecutan las instrucciones en un programa, determinando el orden en el que se llevan a cabo. En JavaScript (y en otros lenguajes de programación), el flujo de control permite que el código siga distintas rutas basadas en condiciones y estructuras, como `if`/`else`, `switch`, `for`, y `while`. Esto ayuda a los desarrolladores a tomar decisiones dentro del código y a repetir ciertas operaciones solo cuando se cumplan ciertas condiciones.

### ¿Qué es una “function” (Función) de JavaScript?

Una **función** en JavaScript es un bloque de código reutilizable que realiza una tarea específica o calcula un valor. Las funciones se pueden definir, invocar (llamar) y reutilizar a lo largo del código, lo cual ayuda a mantenerlo más limpio y modular. Se declaran usando la palabra clave `function`, seguidas del nombre de la función, paréntesis `()`, y un bloque de código `{}`. Las funciones pueden recibir argumentos y pueden devolver un valor usando `return`.

```javascript
function saludo(nombre) {
    return `Hola, ${nombre}!`;
}

console.log(saludo("Carlos")); // Imprime "Hola, Carlos!"

### ¿Cuántas veces se ejecutará un bucle “while”?

Un **bucle `while`** se ejecutará repetidamente mientras una condición especificada sea `true`. El número de veces que se ejecuta depende de esa condición. Si la condición inicial es `false`, el bucle no se ejecutará ninguna vez. En cambio, si la condición nunca se vuelve `false`, el bucle será infinito y se ejecutará indefinidamente (lo que puede causar problemas de rendimiento).

```javascript
let contador = 0;
while (contador < 5) {
    console.log(contador); // Se ejecutará 5 veces: 0, 1, 2, 3, 4
    contador++;
}

### ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?

Para agregar un elemento al final de un array en JavaScript, se usa el método `.push()`. Este método toma uno o más elementos como argumentos y los añade al final del array, devolviendo la nueva longitud del array.

```javascript
const frutas = ["manzana", "naranja"];
frutas.push("banana");
console.log(frutas); // Imprime ["manzana", "naranja", "banana"]
