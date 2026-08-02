# Casos de Prueba - Historia 6: Historial de Pedidos

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-006-POS
- **Título breve:** Consulta de órdenes guardadas en el historial del usuario
- **Objetivo:** Verificar que el usuario registrado pueda consultar la lista detallada de sus órdenes anteriores.
- **Precondiciones:** Usuario autenticado que haya generado al menos un pedido anteriormente.
- **Datos de prueba:** Usuario autenticado con historial previo.
- **Pasos:**
  1. Abrir el menú del perfil de usuario.
  2. Hacer clic en la pestaña "Mis Pedidos" o "Historial".
- **Resultado esperado:** Se despliega la lista cronológica con las órdenes realizadas, indicando fecha, número de orden, detalle de productos y estado para recoger.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-006-NEG
- **Título breve:** Consulta de historial en cuenta de usuario nuevo (Sin pedidos)
- **Objetivo:** Confirmar que el sistema maneje limpiamente el escenario en que un usuario no posea compras previas registradas.
- **Precondiciones:** Usuario recién registrado sin ningún pedido en la base de datos.
- **Datos de prueba:** Usuario nuevo autenticado.
- **Pasos:**
  1. Navegar hasta la opción "Mis Pedidos" o "Historial".
- **Resultado esperado:** La pantalla muestra un diseño limpio con un mensaje informativo: "Aún no has realizado ninguna compra" y un botón rápido para ir al catálogo.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
