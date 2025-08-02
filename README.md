# ejercico-en-clase-

Mejora #1
Ubicación: Clase PedidoService, línea 29

Descripción del cambio:
Se añadió una validación que impide agregar un producto si ya existe otro con el mismo nombre en el pedido. Esto evita la duplicación innecesaria de productos con nombres idénticos dentro de un mismo pedido.

Justificación:
Antes, al agregar productos con el mismo nombre, el sistema permitía duplicados, lo que causaba conflictos en el manejo de inventario y en el cálculo total del pedido. Con esta validación, se mejora la integridad y consistencia de los datos.

Mejora #5
Ubicación: Clase Pedido

Descripción del cambio:
Se simplificó la lógica interna del código, eliminando pasos redundantes y utilizando estructuras más claras para el procesamiento de los datos. Esto facilita el mantenimiento y la comprensión del código.

Justificación:
La simplificación permitió optimizar el rendimiento y la legibilidad del código, lo que a su vez reduce la posibilidad de errores y mejora la eficiencia en futuras modificaciones.
