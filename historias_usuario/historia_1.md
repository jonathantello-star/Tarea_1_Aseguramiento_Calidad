# Historia de Usuario 1: Registro de usuario

### Definición
**Como** nuevo cliente de LePetitDep  
**Quiero** crear una cuenta usando mi email y una contraseña  
**Para** poder acceder al sistema y gestionar mis pedidos de panadería de forma personalizada.

### Criterios de Aceptación
* **Escenario 1: Registro exitoso**
    * **Dado que** el usuario no está registrado y se encuentra en la página de registro.
    * **Cuando** ingresa un correo electrónico válido y una contraseña que cumple las políticas de seguridad, y hace clic en "Registrarse".
    * **Entonces** el sistema guarda el usuario de forma segura y lo redirige a la página de inicio o menú principal.
* **Escenario 2: Correo electrónico duplicado**
    * **Dado que** un usuario intenta registrarse en la plataforma.
    * **Cuando** ingresa un correo electrónico que ya existe en la base de datos.
    * **Entonces** el sistema muestra un mensaje de error indicando que el correo ya está registrado.
