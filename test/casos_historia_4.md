# Casos de Prueba - Historia 4: Agregar Productos al Carrito

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-004-POS
- **Título breve:** Adición correcta de un producto con cantidad específica
- **Objetivo:** Confirmar que un producto seleccionado con su respectiva cantidad se agrega al carrito de compras recalculando el total.
- **Precondiciones:** Estar ubicado en la sección Menú.
- **Datos de prueba:** Producto: `Café Americano`, Cantidad: `2`
- **Pasos:**
  1. Seleccionar el ítem `Café Americano`.
  2. Ajustar el contador de cantidad a `2`.
  3. Presionar el botón "Agregar al Carrito".
- **Resultado esperado:** Se añade el producto al carrito, se actualiza el contador global de ítems a 2 y el precio total refleja la suma adecuada.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-004-NEG
- **Título breve:** Intento de agregar un producto con cantidad cero o negativa
- **Objetivo:** Asegurar que el sistema impida ingresar cantidades no válidas al carrito.
- **Precondiciones:** Usuario interactuando con la ficha de un producto.
- **Datos de prueba:** Producto: `Croissant de Mantequilla`, Cantidad: `0`
- **Pasos:**
  1. Seleccionar `Croissant de Mantequilla`.
  2. Cambiar manualmente o ajustar la cantidad a `0`.
  3. Hacer clic en "Agregar al Carrito".
- **Resultado esperado:** El botón "Agregar al Carrito" permanece deshabilitado o la aplicación lanza una alerta solicitando seleccionar una cantidad mayor a cero.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
