# Casos de Prueba - Historia 5: Realizar Pedido

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-005-POS
- **Título breve:** Confirmación exitosa de pedido y pago simulado
- **Objetivo:** Validar que un usuario pueda confirmar su orden para recoger en local, completar el flujo de pago simulado y generar un número de pedido.
- **Precondiciones:** El carrito de compras contiene al menos un producto agregado.
- **Datos de prueba:** Método de pago: `Tarjeta de Crédito Simulado`, Datos simulados requeridos completos.
- **Pasos:**
  1. Dirigirse al Carrito y presionar "Proceder al Pago / Confirmar".
  2. Seleccionar el método de pago simulado.
  3. Hacer clic en "Finalizar Orden".
- **Resultado esperado:** El pago procesa correctamente, se muestra la pantalla de confirmación con el resumen y un código/número de orden único (ej. `#LPD-1024`).
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-005-NEG
- **Título breve:** Intento de procesar la orden con el carrito vacío
- **Objetivo:** Validar que la interfaz restrinja completar un pedido si no hay artículos seleccionados.
- **Precondiciones:** El carrito de compras no contiene ningún artículo (0 ítems).
- **Datos de prueba:** Carrito vacío.
- **Pasos:**
  1. Intentar acceder a la vista checkout/pago mediante la URL o presionar el botón de pedido.
- **Resultado esperado:** El sistema bloquea el flujo, mantiene deshabilitado el proceso de pago y muestra la indicación: "Tu carrito está vacío. Agrega productos antes de realizar el pedido".
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
