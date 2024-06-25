# Sistema de Reserva de Boleto de Cine

Este es un sistema interactivo para la reserva de boletos de cine, donde los usuarios pueden seleccionar y reservar asientos en una sala virtual de 10x10. Cada asiento está identificado por una fila (de la A a la J) y una columna (del 1 al 10).

## Características

- Visualización interactiva de los asientos en una cuadrícula de 10x10.
- Los asientos pueden ser reservados una vez.
- Confirmación de reserva con un mensaje que indica los asientos reservados.
- Leyenda visual para indicar el estado de los asientos: disponibles y reservados.

## Tecnologías Utilizadas

- HTML
- CSS
- JavaScript

## Funcionamiento

1. **Visualización de Asientos:**
   - Los asientos se muestran en una cuadrícula de 10x10, etiquetados desde A1 hasta J10.
   - Cada asiento inicialmente se muestra como disponible (verde claro).

2. **Reserva de Asientos:**
   - Para reservar un asiento, el usuario debe hacer clic en el asiento deseado.
   - Los asientos reservados cambian de color a rojo claro para indicar que ya han sido reservados y no están disponibles para ser reservados nuevamente.

3. **Confirmación de Reserva:**
   - Una vez que el usuario ha seleccionado y reservado los asientos deseados, se muestra un mensaje indicando los asientos reservados.

4. **Leyenda de Colores:**
   - Hay una leyenda visual que describe el significado de los colores utilizados para los asientos:
     - Verde claro: Disponible.
     - Rojo claro: Reservado.

## Notas Adicionales

- Este proyecto es solo una simulación y no incluye funcionalidad de backend para almacenar las reservas realizadas.
- Los asientos reservados se deben guardan en el localStorage y mostrar al recargar.

¡Disfruta reservando tus asientos virtuales en el cine!

---

Este README proporciona una visión general del proyecto, explica cómo funciona la aplicación y cómo ejecutarla. También incluye información sobre las tecnologías utilizadas y notas adicionales sobre la funcionalidad del sistema. Puedes personalizar y expandir este README según sea necesario para adaptarlo a las especificaciones y detalles adicionales de tu implementación.
