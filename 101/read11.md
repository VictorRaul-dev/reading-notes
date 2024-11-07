### ¿Qué es el DOM?
El DOM (Document Object Model) es una representación en forma de árbol de los elementos de una página web. Cada etiqueta HTML, atributo y texto dentro del documento se convierte en un nodo en este árbol. El DOM permite que los lenguajes de programación, como JavaScript, accedan y manipulen la estructura y el contenido de la página.

### Relación entre el DOM y JavaScript
JavaScript utiliza el DOM para interactuar con las páginas web de manera dinámica. Gracias al DOM, JavaScript puede acceder, modificar o eliminar elementos y atributos de una página sin necesidad de recargarla, lo que permite crear experiencias interactivas para los usuarios.

### ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
Para seleccionar un elemento del DOM por su ID, se utiliza el método `document.getElementById()`. Este método devuelve el primer elemento del documento con el `id` especificado.

Ejemplo:
let miElemento = document.getElementById('mi-id');
console.log(miElemento);

### ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?
Para cambiar el color de fondo de un elemento en el DOM, se puede usar la propiedad `style.backgroundColor` del elemento seleccionado.

Ejemplo:
let miElemento = document.getElementById('mi-id');
miElemento.style.backgroundColor = 'lightblue'; // Cambia el color de fondo a azul claro.
