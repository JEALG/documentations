Aquí es donde podremos definir la lista de usuarios
permitido conectarse a Jeedom, pero también sus derechos
d'administrateur

Accesible por Administración → Usuarios.

En la parte superior derecha tiene un botón para agregar un usuario, un
para guardar y un botón para abrir un acceso de soporte.

Abajo tienes una mesa :

-   **Nombre del usuario** : ID de usuario

-   **Actif** : permite desactivar la cuenta

-   **Solo local** : autorizar inicio de sesión de usuario
    solo si está en la red local de Jeedom

-   **Profils** : permite elegir el perfil de usuario :

    -   **Administrateur** : obtiene todos los derechos sobre Jeedom

    -   **Utilisateur** : puede ver el tablero, las vistas,
        diseño, etc.. y actuar sobre equipos / controles. En cambio,
        no tendrá acceso a la configuración de controles / equipos
        ni a la configuración de Jeedom.

    -   **Usuario limitado** : el usuario solo ve el
        equipo autorizado (configurable con el botón &quot;Administrar&quot;
        los derechos&quot;)

-   **Clave API** : clave de API personal del usuario

-   **Doble autenticación** : indica si la autenticación doble
    está activo (OK) o no (NOK)

-   **Fecha de la última conexión** : fecha de la última conexión de
    el usuario en Jeedom. Tenga en cuenta que esta es la fecha de conexión
    real, así que si guarda su computadora, la fecha de
    la conexión no se actualiza cada vez que vuelve a ella.

-   **Cambiar contraseña** : permite cambiar la contraseña de
    l'utilisateur

-   **Supprimer** : eliminar usuario

-   **Regenerar clave API** : regenera la clave API del usuario

-   **Administrar derechos** : permite gestionar con precisión los derechos de
    el usuario (atención los perfiles deben estar en
    "usuario limitado ")

Gestión de derechos 
==================

Al hacer clic en &quot;Administrar derechos&quot; aparece una ventana que le permite
administrar con precisión los derechos de los usuarios. La primera pestaña muestra
los diferentes equipos. El segundo presenta los escenarios..

> **Important**
>
> El perfil debe ser limitado, de lo contrario no se aplicarán restricciones aquí
> se tendrá en cuenta

Obtiene una tabla que permite, para cada equipo y cada
escenario, definir derechos de usuario :

-   **Aucun** : el usuario no ve el equipo / escenario

-   **Visualisation** : el usuario ve el equipo / escenario pero no ve
    no puedo actuar en consecuencia

-   **Visualización y ejecución** : el usuario ve
    El equipo / escenario y puede actuar sobre él (encender una lámpara, tirar
    el escenario, etc.)


