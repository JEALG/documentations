Sensor de movimiento Fibaro - FGMS-001 
===============================

\

-   **El módulo**

\

![module](images/fibaro.fgms001/module.jpg)

\

-   **El visual de Jeedom**

\

![vuedefaut1](images/fibaro.fgms001/vuedefaut1.jpg)

\

Resumen 
------

\

El detector de movimiento Fibaro es un detector multifunción Z-Wave.
Además de la detección de movimiento, este dispositivo mide la
temperatura e intensidad de luz. Este detector también incluye un
Acelerómetro incorporado para detectar cualquier intento de alterar el
dispositif.

El detector de movimiento Fibaro funciona con batería y está diseñado
para ser instalado rápida y fácilmente en cualquier
superficie El indicador LED indica movimiento, nivel de temperatura,
el modo de funcionamiento y se puede usar para ver si el dispositivo
está en la red Z-Wave.

El detector de movimiento se puede usar para iluminar escenas
y sistemas de vigilancia y / o seguridad.

\

Funciones 
---------

\

-   Detector de movimiento inalámbrico

-   Detecta movimiento usando un sensor infrarrojo pasivo

-   Medida de temperatura

-   Medida de intensidad de luz

-   Protección contra robos y robos

-   Alertas de movimiento y temperatura señaladas por parpadeo
    Diodo LED

-   Modo de detección de terremotos

-   Botón para incluir / excluir el detector

-   Detección de batería baja

-   Muy pequeño, dimensiones reducidas

-   Fácil instalación en una pared o cualquier otra superficie

\

Características técnicas 
---------------------------

\

-   Tipo de módulo : Transmisor de onda Z

-   Suministro : Batería CR123A 3,6VDC

-   Altura recomendada para la instalación : 2,4m

-   Rango de temperatura medido : -20 ° C a 100 ° C

-   Precisión de medición : 0,5°C

-   Rango de medición de brillo : 0-32000 LUX

-   Frecuencia : 868.42 Mhz

-   Distancia de transmisión : 50m de campo libre, 30m en interiores

-   Dimensions: 4.4 cm de diámetro

-   Temperatura de funcionamiento : 0-40 ° C

-   Certificaciones : LVD 2006/95 / WE EMC 2004/108 / WE R & TTE 1999/5 / WE RoHS
    II

\

Datos del módulo 
-----------------

\

-   Hacer : Grupo Fibar

-   Nombre : Fibaro FGMS-001 \ [Sensor de movimiento \]

-   ID del fabricante : 271

-   Tipo de producto : 2048

-   ID del producto : 4097

\

Configuración 
-------------

\

Para configurar el complemento OpenZwave y saber cómo poner Jeedom en
inclusión refiérase a esto
[Documentación](https://jeedom.fr/doc/documentation/plugins/openzwave/es_ES/openzwave.html).

\

> **Importante**
>
> Para poner este módulo en modo de inclusión, presione el botón 3 veces
> botón de inclusión, de acuerdo con su documentación en papel.

\

![inclusion](images/fibaro.fgms001/inclusion.jpg)

\

Una vez incluido, deberías obtener esto :

\

![Plugin Zwave](images/fibaro.fgms001/information.jpg)

\

### Comandos 

\

Una vez que el módulo ha sido reconocido, los comandos asociados con el módulo serán
disponibles.

\

![Comandos](images/fibaro.fgms001/commandes.jpg)

\

Aquí está la lista de comandos :

\

-   Presencia : es el comando que detectará una detección de presencia

-   Temperatura : es el comando que permite subir el
    Temperatura

-   Brillo : es el comando que hace posible aumentar el brillo

-   Sabotaje : este es el comando de sabotaje (se activa en caso de que
    vibración)

-   Batería : es el comando de la batería

\

### Configuracion del modulo 

\

> **Importante**
>
> Durante una primera inclusión, siempre active el módulo justo después
> inclusión.

\

Entonces, si desea configurar el módulo de acuerdo con
de su instalación, debe pasar por el botón
"Configuración "del complemento OpenZwave de Jeedom.

\

![Configuración plugin Zwave](images/plugin/bouton_configuration.jpg)

\

Llegará a esta página (después de hacer clic en la pestaña
Configuraciones)

\

![Config1](images/fibaro.fgms001/config1.jpg)

![Config2](images/fibaro.fgms001/config2.jpg)

![Config3](images/fibaro.fgms001/config3.jpg)

![Config3](images/fibaro.fgms001/config4.jpg)

\

Detalles del parámetro :

\

-   Despertador : Este es el intervalo de activación del módulo (valor
    7200 recomendado)

-   1: ajusta la sensibilidad del sensor de presencia

-   2: ajusta la inercia del sensor de presencia

-   3: no se recomienda cambiar esta configuración

-   4: no se recomienda cambiar esta configuración

-   6: tiempo después del cual el sensor enviará la señal "más de
    movimiento "(valor recomendado 30)

-   8: activa el modo noche / día o ambos (valor
    recomendado : siempre activo)

-   9: le permite ajustar el umbral para cambiar al modo nocturno (útil si
    ha cambiado el parámetro 8)

-   12: cambiar solo si sabes por qué lo estás haciendo
    (asociación con un módulo por ejemplo)

-   14: idem

-   16: idem

-   20: sensibilidad del sensor giroscópico (valor recomendado 15)

-   22: tiempo después del cual el sensor enviará la señal "más de
    sabotaje "(valor recomendado 30)

-   24: le permite saber cómo se notifica el sabotaje (IMPORTANTE :
    valor recomendado : Sensor de sabotaje notificado a SensorAlarm
    clase de comando / Cancelación se notifica después del tiempo definido en
    parámetro 22)

-   26: cambiar solo si sabes por qué lo estás haciendo

-   40: digamos cuánto es el valor de
    brillo a enviar (valor recomendado 50)

-   42: permite dar una duración mínima entre dos envíos sucesivos
    incluso si el brillo no ha cambiado (valor recomendado 3600)

-   60: digamos cuánto es el valor de
    temperatura a enviar (valor recomendado 2 o 0.2 grados)

-   62: da la frecuencia de las mediciones de temperatura (valor
    recomendado 900)

-   64: permite dar una duración mínima entre dos envíos sucesivos
    incluso si la temperatura no ha cambiado (valor recomendado 2700)

-   66: permite ajustar la temperatura

-   80: permite elegir el color del led cuando hay detección de
    movimiento (ver para desactivar)

-   81: permite ajustar el brillo del led

-   82: ajusta el umbral de brillo mínimo para establecer el
    1% led (vinculado al parámetro 81)

-   83: ajusta el umbral de brillo máximo para establecer el
    100% led (vinculado al parámetro 81)

-   86: temperatura por debajo de la cual el LED se iluminará en azul
    (vinculado al parámetro 81)

-   87: temperatura por encima de la cual el LED se iluminará en rojo
    (vinculado al parámetro 81)

-   89: permite que el LED parpadee en azul / blanco / rojo en caso de
    sabotage

\

### Grupos 

\

Este módulo tiene tres grupos de asociación, solo el tercero es
indispensable.

\

![Groupe](images/fibaro.fgms001/groupe.jpg)

\

Bueno saber 
------------

\

### Específicos 

\

> **Punta**
>
> Este módulo es muy complicado al despertar y está muy mal configurado
> fabrica. Es esencial despertarlo bien después de la inclusión
> (varias veces son mejores que uno), para configurarlo de acuerdo a su
> deseos, y despertarlo bien para que la configuración se tenga en cuenta
> Cuenta.

\

### Visual alternativo 

\

![vuewidget](images/fibaro.fgms001/vuewidget.jpg)

\

Despertador 
------

\

Para activar este módulo, solo hay una forma :

-   presione el botón de inclusión 3 veces (la luz se enciende
    en azul). Incluso si la luz se enciende, puede ser necesario
    hazlo varias veces seguidas (2 o 3)

\

Faq. 
------

\

Este módulo se activa presionando 3 veces en su botón de inclusión.

\

Este módulo es muy meticuloso. Es recomendable incluir
más cerca de tu caja y recógela varias veces.

\

Este módulo es un módulo de batería, la nueva configuración será
tomado en cuenta en el próximo despertar.

\

Nota importante 
---------------

\

> **Importante**
>
> Tienes que despertar el módulo : después de su inclusión, después de un cambio
> de la configuración, después de un cambio de activación, después de un
> cambio de grupos de asociación

\

**@sarakha63**
