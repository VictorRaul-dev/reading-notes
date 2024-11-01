## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?
En JavaScript, tenemos varios tipos de datos:

- **Números (`number`)**: Representan valores numéricos, ya sean enteros o decimales.  
  Ejemplo: `42`, `3.14`.
- **Cadenas de texto (`string`)**: Representan texto y van entre comillas (`""` o `''`).  
  Ejemplo: `"Hola mundo"`.
- **Booleanos (`boolean`)**: Representan valores `true` o `false`, usados para decisiones lógicas.
- **Objetos (`object`)**: Colecciones de propiedades y valores. Son útiles para agrupar datos relacionados.  
  Ejemplo: `{nombre: "Juan", edad: 30}`.
- **Arreglos (`array`)**: Listas de elementos que pueden ser de cualquier tipo, y están entre corchetes `[]`.  
  Ejemplo: `[1, 2, 3]`.
- **Null**: Representa la ausencia de valor.
- **Undefined**: Representa una variable que ha sido declarada pero no tiene un valor asignado.
- **Símbolos (`symbol`)**: Un tipo único y poco común que se usa para identificadores únicos.

## ¿Cómo se utilizan las estructuras condicionales `if` y `else` en JavaScript, y qué propósito cumplen dentro de un programa?
Las estructuras `if` y `else` se utilizan para ejecutar código condicionalmente, es decir, dependiendo de si una condición es `true` o `false`. Sirven para tomar decisiones en el programa.

```javascript
let edad = 18;
if (edad >= 18) {
    console.log("Eres mayor de edad");
} else {
    console.log("Eres menor de edad");
}
