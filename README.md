Guía de Laboratorio III – Programación Web (CSS Avanzado)
✅ Ejercicio 1 – Variables CSS

Pregunta: ¿Cuál es el objetivo de usar variables en CSS?
Respuesta: El objetivo es definir valores reutilizables (como colores o tamaños) que permiten hacer cambios de manera más eficiente sin necesidad de reescribir código en diferentes partes del proyecto.

✅ Ejercicio 2 – Flexbox

Pregunta 1: ¿Por qué cambia el posicionamiento de las cajas internas al div principal?
Respuesta: Porque las propiedades de Flexbox controlan la dirección, alineación y distribución de los elementos dentro del contenedor. Al modificar flex-direction, justify-content o align-items, cambia la forma en que los hijos se posicionan.

Pregunta 2: ¿Qué pasa si me solicitan cambiar el orden de los elementos sin tocar el HTML ni JS? ¿Puedo lograrlo con CSS?
Respuesta: Sí, es posible usando la propiedad order en Flexbox. Esto permite reorganizar visualmente los elementos sin modificar la estructura HTML.

Pregunta 3: ¿Qué hacen las propiedades de flex-wrap?
Respuesta: Controlan si los elementos se ajustan en varias líneas o permanecen en una sola.

nowrap: todos en una sola línea.

wrap: los elementos se envuelven a una nueva línea cuando no hay espacio.

wrap-reverse: igual que wrap pero en sentido inverso.

✅ Ejercicio 3 – Grid Avanzado

Pregunta 1: ¿Puedo diseñar toda mi web usando GRID?
Respuesta: Sí, es posible, ya que Grid permite un control bidimensional completo de filas y columnas. Sin embargo, lo más recomendable es combinar Grid y Flexbox, ya que cada uno resuelve mejor distintos escenarios.

Pregunta 2: ¿Por qué se dan estos cambios con tan pocas líneas de CSS?
Respuesta: Porque Grid está diseñado para manejar estructuras complejas de diseño con pocas propiedades (display: grid, grid-template-columns, grid-template-rows, grid-column, grid-row), lo que permite definir de forma concisa el posicionamiento y distribución de los elementos.

✅ Ejercicio 4 – Animaciones

Pregunta: ¿Qué aportan las transiciones y animaciones en CSS?
Respuesta: Hacen que los elementos sean más interactivos y atractivos, mejorando la experiencia de usuario con efectos como cambios de color, tamaño o movimiento suave al pasar el cursor.

✅ Ejercicio Final

Pregunta 1: ¿Cómo hago que un componente aparezca unos segundos después de cargar la web?
Respuesta: Usando animaciones con @keyframes y aplicando animation-delay para que el efecto ocurra después de cierto tiempo.

Pregunta 2: ¿Cómo logro que el botón cambie el cursor al pasar el mouse?
Respuesta: Usando la pseudo-clase :hover junto con la propiedad cursor: pointer;.

Ejemplo:

.btn:hover {
  background-color: #0056b3;
  cursor: pointer;
}
