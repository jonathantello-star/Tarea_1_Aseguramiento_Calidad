# Historia de Usuario 2: Inicio de sesión

### Definición
**Como** cliente registrado de LePetitDep  
**Quiero** iniciar sesión de forma segura ingresando mis credenciales  
**Para** poder realizar compras y consultar mis datos guardados en la aplicación.

### Criterios de Aceptación
* **Escenario 1: Validación exitosa de credenciales**
    * **Dado que** el usuario tiene una cuenta activa y está en el formulario de Login.
    * **Cuando** ingresa sus credenciales correctas (email y contraseña) y hace clic en "Iniciar Sesión".
    * **Entonces** el sistema le otorga acceso seguro y muestra su sesión activa en la interfaz.
* **Escenario 2: Credenciales inválidas**
    * **Dado que** el usuario está en el formulario de Login.
    * **Cuando** ingresa un correo o una contraseña incorrectos.
    * **Entonces** el sistema despliega un mensaje de error ("Credenciales incorrectas") y deniega el acceso, protegiendo los datos.
