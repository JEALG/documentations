Philio PST02 C - 3 in 1 Opening 
=================================

\

-   **The module**

\

![module](images/philio.pst02c/module.jpg)

\

-   **The Jeedom visual**

\

![vuedefaut1](images/philio.pst02c/vuedefaut1.jpg)

\

Summary 
------

\

The ZIP-PSM01 detector offers 3 different functions : detection
opening, temperature sensor and light detector. It is
consists of two parts : a detector and a magnet. They are designed
to be placed on a door or window with the magnet fixed on the
opening part and the detector on the fixed part.

Opening the door or window will keep the magnet away from
detector, which will trigger the detector which will send a Z-Wave signal
alarm, if the system is armed (this signal can be used by a
siren or by a home automation box for example). The sensor can also
be used for automatic lighting control, depending on the
brightness level. For example, the sensor will send a signal to
Z-Wave switch to turn on the light when the door opens
and the room is dark.

The detector will also raise the brightness and the temperature, i.e
in the event of a significant change, and each time the opening / closing
is detected.

A Z-Wave controller (remote control, dongle, etc.) is required in order to
integrate this detector into your network if you already have a network
existant.

\

Functions 
---------

\

-   3 in 1 detector: Aperture, temperature, light

-   Adopts the recent Z-Wave 400series chip to support
    multichannel operations and more data throughput
    high (9.6 / 40 / 100kbps)

-   Uses the Z-Wave 6.02 SDK

-   Optimized antenna range

-   Use for home automation or security applications

-   Button to include / exclude the detector

-   Autoprotection

-   Low battery indication

-   Small, discreet and aesthetic

-   Ease of use and installation

\

Technical characteristics 
---------------------------

\

-   Type of module : Z-Wave transmitter

-   Food : 1 CR123A 3V battery

-   Battery life : 3 years (for 14 trips per day)

-   Frequency : 868.42 MHz

-   Transmission distance : 30m indoors

-   Temperature sensor : -10 to 70 ° C

-   Brightness sensor : 0 to 500 lux

-   Dimensions :

-   Detector : 28 x 96 x 23 mm

-   Magnet : 10 x 50 x 12 mm

-   Weight : 52g

-   Operating temperature : -10 to 40 ° C

-   Operating humidity : 85% RH max

-   CE standard : EN300 220-1

-   Z-Wave certification : ZC08-13050003

\

Module data 
-----------------

\

-   Mark : Philio Technology Corporation

-   Name : PST02-C Door / Window 3 in 1 sensor

-   Manufacturer ID : 316

-   Product Type : 2

-   Product ID : 14

\

Setup 
-------------

\

To configure the OpenZwave plugin and know how to put Jeedom in
inclusion refer to this
[Documentation](https://jeedom.fr/doc/documentation/plugins/openzwave/en_US/openzwave.html).

\

> **IMPORTANT**
>
> To put this module in inclusion mode, press the button 3 times
> inclusion button, according to its paper documentation.

\

![inclusion](images/philio.pst02c/inclusion.jpg)

\

Once included you should get this :

\

![Plugin Zwave](images/philio.pst02c/information.jpg)

\

### Commands 

\

Once the module has been recognized, the commands associated with the module will be
disponibles.

\

![Commands](images/philio.pst02c/commandes.jpg)

\

Here is the list of commands :

\

-   Opening : it is the command which will raise a detection
    d'ouverture

-   Temperature : it is the command which allows to go up the
    Temperature

-   Brightness : it is the command which makes it possible to raise the brightness

-   Drums : it's the battery command

\

### Configuration of the module 

\

> **IMPORTANT**
>
> During a first inclusion always wake up the module just after
> inclusion.

\

Then if you want to configure the module according to
of your installation, you have to go through the button
"Configuration "of Jeedom's OpenZwave plugin.

\

![Setup plugin Zwave](images/plugin/bouton_configuration.jpg)

\

You will arrive on this page (after clicking on the tab
settings)

\

![Config1](images/philio.pst02c/config1.jpg)

![Config2](images/philio.pst02c/config2.jpg)

![Config3](images/philio.pst02c/config3.jpg)

\

Parameter details :

\

-   2: allows to adjust the signal sent to the modules in the group
    association 2

-   4: adjusts the brightness level from which the
    signal defined in parameter 2 will be sent to the modules associated with the
    group 2

-   5: operating mode (see the
    manufacturer documentation) Recommended value : 8

-   6: multi-sensor operating mode (see the
    manufacturer documentation) Recommended value : 4

-   7: personalized multi-sensor operating mode (see
    on the manufacturer's documentation) Recommended value : 20 (for
    have the functional opening)

-   9: allows to define after how long the OFF signal will be
    sent to modules associated with group 2

-   10: allows you to define the duration between two battery reports (one
    unit = parameter 20)

-   11: allows you to define the duration between two self-opening reports
    (one unit = parameter 20)

-   12: allows you to define the duration between two auto
    brightness (one unit = parameter 20) Recommended value : 3

-   13: allows you to define the duration between two auto
    temperature (one unit = parameter 20) Recommended value : 2

-   20: duration of an interval for parameters 10 to 13 Value
    recommended : 10

-   21: temperature variation value in ° F to trigger a
    rapport

-   22: value in% of brightness variation to trigger a
    Report Recommended value : 10

\

### Groups 

\

This module has two association groups, only the first is
indispensable.

\

![Groupe](images/philio.pst02c/groupe.jpg)

\

Good to know 
------------

\

### Alternative visual 

\

![vuewidget](images/philio.pst02c/vuewidget.jpg)

\

Wakeup 
------

\

To wake up this module there is only one way :

-   release the tamper button and press it again

\

Faq. 
------

\

This module wakes up by pressing its tamper button.

\

This module is a battery module, the new configuration will be
taken into account at the next wakeup.

\

Important note 
---------------

\

> **IMPORTANT**
>
> You have to wake up the module : after its inclusion, after a change
> of the configuration, after a change of wakeup, after a
> change of association groups

\

**@sarakha63**
