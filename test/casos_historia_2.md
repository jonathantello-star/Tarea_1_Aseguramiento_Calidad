# Casos de Prueba - Historia 2: Inicio de Sesión

## Caso de Prueba 1 (Positivo)
- **ID del caso de prueba:** TC-002-POS
- **Título breve:** Inicio de sesión exitoso con credenciales correctas
- **Objetivo:** Verificar que un usuario previamente registrado puede iniciar sesión en la plataforma.
- **Precondiciones:** El usuario ya está registrado en la base de datos de LePetitDep.
- **Datos de prueba:** Correo: `usuario.nuevo@email.com`, Contraseña: `Password123!`
- **Pasos:**
  1. Ir a la pantalla de Inicio de Sesión.
  2. Ingresar el correo `usuario.nuevo@email.com`.
  3. Ingresar la contraseña `Password123!`.
  4. Presionar el botón "Iniciar Sesión".
- **Resultado esperado:** El sistema autentica correctamente las credenciales y da acceso al menú interactivo del local.
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente

---

## Caso de Prueba 2 (Negativo)
- **ID del caso de prueba:** TC-002-NEG
- **Título breve:** Fallo de autenticación por contraseña incorrecta
- **Objetivo:** Verificar que el sistema impida el acceso cuando la contraseña no coincide con el correo ingresado.
- **Precondiciones:** El usuario `usuario.nuevo@email.com` existe en la plataforma.
- **Datos de prueba:** Correo: `usuario.nuevo@email.com`, Contraseña: `WrongPassword123`
- **Pasos:**
  1. Abrir la pantalla de Inicio de Sesión.
  2. Ingresar el correo `usuario.nuevo@email.com`.
  3. Ingresar la contraseña errónea `WrongPassword123`.
  4. Presionar el botón "Iniciar Sesión".
- **Resultado esperado:** El sistema deniega el acceso y muestra la alerta: "Credenciales incorrectas, por favor intente de nuevo".
- **Resultado obtenido:** Pendiente
- **Estado:** Pendiente
- **Notas/Evidencias:** Pendiente
