OpenGarage es un objeto de tipo DIY pero también disponible montado en
usado en el garaje.

Ofrece la activación de un relé (para abrir el garaje) y un
sensor de distancia para verificar la presencia del automóvil.

<http://opengarage.io/>

Lectura de estados de OpenGarage 
===============================

Para recuperar el estado del relé y el sensor de distancia, la url para
uso es :

    http://addropengarage/jc

El resultado es un json. Así que usa equipo tipo
Script y comando de información de tipo json

Para el estado del relé, el nombre de la propiedad del json : door

Para el sensor de distancia : dist

Acción en OpenGarage 
========================

La dirección para la activación del relé es :

    http://addropengarage/cc?dkey=xxxx&click=1

dkey es la clave de la API, por defecto es opendoor

Mas información 
============

La documentación completa de la API está disponible en github :

<https://github.com/OpenGarage/OpenGarage-Firmware/tree/master/docs>
