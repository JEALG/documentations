# Centro de actualizaciones
**Configuración → Sistema → Centro de actualizaciones**


La **centro de actualizaciones** le permite actualizar toda la funcionalidad de Jeedom, incluido el software principal y sus complementos.
Otras funciones de administración de extensiones están disponibles (eliminar, reinstalar, verificar, etc.).


## Funciones de la página

En la parte superior de la página, independientemente de la pestaña, se encuentran los botones de control.

Jeedom se conecta periódicamente al mercado para ver si hay actualizaciones disponibles. La fecha de la última verificación se indica en la parte superior izquierda de la página..

Al abrir la página, si esta verificación tiene más de dos horas, Jeedom rehace automáticamente una verificación.
También puedes usar el botón **Verifique las actualizaciones** Para hacerlo manualmente.
Si desea realizar una verificación manual, puede presionar el botón "Buscar actualizaciones".

El botón **Sauvegarder** se utilizará cuando cambie las opciones en la tabla a continuación, para especificar que no se actualicen ciertos complementos si es necesario.

## Actualiza el núcleo

El botón **Poner al día** le permite actualizar el Core, los complementos o ambos.
Una vez que haces clic en él, obtienes estas diferentes opciones :
- **Pre-actualización** : La permite actualizar el script de actualización antes de aplicar las nuevas actualizaciones. Generalmente se usa a pedido del soporte.
- **Ahorre antes** : Haga una copia de seguridad de Jeedom antes de actualizar.
- **Actualizar complementos** : La permite incluir complementos en la actualización.
- **Actualiza el núcleo** : La permite incluir el núcleo Jeedom (el núcleo) en la actualización.

- **Modo forzado** : Realice la actualización en modo forzado, es decir, incluso si hay un error, Jeedom continuará y no restaurará la copia de seguridad.. (¡Este modo desactiva el guardado!).
- **Actualización para volver a aplicar** : La permite volver a aplicar una actualización. (NB : No todas las actualizaciones se pueden volver a aplicar).

> **Important**
>
> Antes de una actualización, por defecto, Jeedom hará una copia de seguridad. En el caso de un problema al aplicar una actualización, Jeedom restaurará automáticamente la copia de seguridad realizada justo antes. Este principio solo es válido para las actualizaciones de Jeedom y no para actualizar complementos.

> **Tip**
>
> Puede forzar una actualización de Jeedom, incluso si no ofrece una..

## Pestañas Core y Plugins

La tabla contiene las versiones de Core y los complementos instalados..

Los complementos tienen una insignia al lado de su nombre, especificando su versión, verde en * estable *, o naranja en * beta * u otro.

- **Statut** : OK o NOK.
- **Nom** : Nombre y origen del complemento.
- **Version** : Indica la versión precisa del núcleo o complemento.
- **Options** : Marque esta casilla si no desea que este complemento se actualice durante la actualización global (Botón **Poner al día**).

En cada línea, puede usar las siguientes funciones:

- **Restablecer** : Reasentamiento forzado.
- **Supprimer** : La permite desinstalarlo.
- **Comprobar** : Consulte la fuente de actualizaciones para averiguar si hay una nueva actualización disponible.
- **Poner al día** : La permite actualizar el elemento (si tiene una actualización).
- **Changelog** : Permite el acceso a la lista de cambios en la actualización..

> **Important**
>
> Si el registro de cambios está vacío pero aún tiene una actualización, significa que la documentación se ha actualizado.. Por lo tanto, no es necesario solicitar cambios al desarrollador, ya que no necesariamente hay. (a menudo es una actualización de la traducción, de la documentación).
> El desarrollador del complemento también puede en algunos casos hacer correcciones de errores simples, que no necesariamente requieren actualizar el registro de cambios.

> **Tip**
>
> Cuando inicia una actualización, aparece una barra de progreso sobre la tabla. Evite otras manipulaciones durante la actualización..

## Pestaña de información

Durante o después de una actualización, esta pestaña le permite leer el registro de esta actualización en tiempo real..

> **Note**
>
> Este registro normalmente termina con * [FINALIZAR ÉXITO DE ACTUALIZACIÓN]*. Puede haber algunas líneas de error en este tipo de registro, sin embargo, a menos que haya un problema real después de la actualización, no siempre es necesario contactar al soporte para esto..

## Actualización de línea de comando

Es posible actualizar Jeedom directamente en SSH.
Una vez conectado, este es el comando para realizar :

``````sudo php /var/www/html/install/update.php``````

Los posibles parámetros son :

- **mode** : ``force``, para iniciar una actualización en modo forzado (ignora los errores).
- **version** : Seguimiento del número de versión, para volver a aplicar los cambios de esta versión.

Aquí hay un ejemplo de sintaxis para realizar una actualización forzada al volver a aplicar los cambios desde 4.0.04 :

``````sudo php  /var/www/html/install/update.php mode=force version=4.0.04``````

Atención, después de una actualización en la línea de comando, es necesario volver a aplicar los derechos en la carpeta Jeedom :

``````sudo chown -R www-data:www-data /var/www/html``````
