# Historia de Usuario 5: Realizar pedido

### Definición
**Como** cliente con productos agregados en el carrito  
**Quiero** confirmar mi orden, procesar un método de pago simulado y recibir mi número de pedido  
**Para** asegurar que la cafetería comience a preparar mi orden y pueda retirarla en el local.

### Criterios de Aceptación
* **Escenario 1: Confirmación de orden y pago simulado**
    * **Dado que** el usuario tiene artículos en el carrito y está en la pantalla de "Checkout".
    * **Cuando** confirma sus datos, ingresa la información del pago simulado y hace clic en "Finalizar Pedido".
    * **Entonces** el sistema procesa la transacción, genera un número único de orden y le muestra un mensaje de confirmación en pantalla.
