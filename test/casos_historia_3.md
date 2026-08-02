# Casos de Prueba - Historia 3: Explorar Menú

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-003-POS
- **Título breve:** Carga exitosa del catálogo de menú
- **Objetivo:** Validar que el usuario puede visualizar la lista completa de productos (cafés y panadería) con sus nombres, descripciones y precios.
- **Precondiciones:** Usuario ha iniciado sesión o está navegando en la app.
- **Datos de prueba:** N/A (Consulta general)
- **Pasos:**
  1. Navegar a la sección "Menú" de la aplicación.
  2. Desplazarse por la lista de productos disponibles.
- **Resultado esperado:** La interfaz despliega la lista con las fotografías, precios legibles y descripciones detalladas de los productos.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-003-NEG
- **Título breve:** Búsqueda o filtrado de producto inexistente en el menú
- **Objetivo:** Validar la respuesta del sistema al buscar un ítem que no está disponible en la oferta de LePetitDep.
- **Precondiciones:** El usuario se encuentra dentro del catálogo del menú.
- **Datos de prueba:** Término de búsqueda: `Pizza Napolitana`
- **Pasos:**
  1. Hacer clic en la barra de búsqueda del menú.
  2. Ingresar la palabra `Pizza Napolitana`.
  3. Presionar Enter o la lupa de búsqueda.
- **Resultado esperado:** El sistema muestra una pantalla vacía con el mensaje aclaratorio: "No se encontraron productos que coincidan con tu búsqueda".
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
