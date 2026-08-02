# Casos de Prueba - Historia 1: Registro de Usuario

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-001-POS
- **Título breve:** Registro exitoso de usuario nuevo
- **Objetivo:** Validar que un nuevo usuario puede registrarse correctamente ingresando un correo válido y una contraseña segura.
- **Precondiciones:** La aplicación web LePetitDep está abierta en el formulario de registro y la cuenta no existe previamente.
- **Datos de prueba:** Correo: `usuario.nuevo@email.com`, Contraseña: `Password123!`
- **Pasos:**
  1. Ingresar a la sección de Registro de la aplicación LePetitDep.
  2. Escribir el correo electrónico `usuario.nuevo@email.com` en el campo correspondiente.
  3. Escribir la contraseña `Password123!` en el campo de contraseña.
  4. Hacer clic en el botón "Crear cuenta".
- **Resultado esperado:** El sistema crea la cuenta exitosamente, muestra un mensaje de confirmación y redirige al usuario al inicio de sesión o al menú principal.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-001-NEG
- **Título breve:** Fallo al registrar usuario con correo con formato inválido
- **Objetivo:** Validar que el sistema bloquee el registro cuando el usuario ingresa un correo sin formato válido.
- **Precondiciones:** La aplicación web LePetitDep está abierta en la sección de registro.
- **Datos de prueba:** Correo: `usuario.sin.dominio`, Contraseña: `Password123!`
- **Pasos:**
  1. Ingresar a la sección de Registro.
  2. Escribir `usuario.sin.dominio` en el campo de correo electrónico.
  3. Escribir `Password123!` en el campo de contraseña.
  4. Hacer clic en el botón "Crear cuenta".
- **Resultado esperado:** El sistema no permite el registro, resalta el campo de correo en rojo y muestra un mensaje de error: "Por favor ingrese un correo válido".
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
