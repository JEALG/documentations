Philio PST02 A - 4 in 1 
=======================

\.

-   **Das Modul**

\.

![module](images/philio.pst02a/module.jpg)

\.

-   **Das Jeedom Visual**

\.

![vuedefaut1](images/philio.pst02a/vuedefaut1.jpg)

\.

Zusammenfassung 
------

\.

Der Detektor ZIP-PSM02-EU bietet 4 verschiedene Funktionen : Erkennung von
Bewegung, Öffnungserkennung, Temperatursensor und Detektor
Helligkeit. Es besteht aus zwei Teilen : ein Detektor und ein Magnet.
Sie sind so konzipiert, dass sie an einer Tür oder einem Fenster mit angebracht werden können
Der Magnet ist an dem sich öffnenden Teil und der Detektor an dem Teil befestigt
fixe.

Durch Öffnen der Tür oder des Fensters wird der Magnet ferngehalten
Detektor, der den Detektor auslöst, der ein Z-Wave-Signal sendet
Alarm, wenn das System scharfgeschaltet ist (dieses Signal kann von a verwendet werden
Sirene oder von einer Hausautomationsbox zum Beispiel). Dieser Detektor kann sein
wird für Sicherheit oder Automatisierung verwendet. Wenn der Detektor
ist mit Sicherheitsgeräten verbunden, dient als Auslöser
Warnungen beim Erkennen von Änderungen der Strahlungswerte
Infrarot- oder Tür- / Fensteröffnung. Wenn eine Person einzieht
das Sichtfeld des Detektors oder öffnet eine Tür / ein Fenster, ein Signal
Radio wird gesendet, was einen Alarm auslöst, um abzuschrecken
intrus.

Der Detektor kann auch in Kombination mit a verwendet werden
Z-Wave-Controller für die Heimautomation, indem beide erkannt werden
Änderungen der Infrarotstrahlung (Vorhandensein) oder
Tür- / Fensteröffnung und Änderungen in der Höhe von
Helligkeit. Somit kann man während einer Erkennung eine Beleuchtung auslösen
Türbewegung oder Öffnung im Dunkeln.

Der Detektor erhöht auch die Helligkeit und die Temperatur, d.h
signifikante Änderung, und wann immer eine Bewegung oder
Öffnen / Schließen werden erkannt. Eine Z-Wave-Steuerung (Fernbedienung),
Dongle…) ist erforderlich, um diesen Detektor in Ihr Netzwerk zu integrieren
wenn Sie bereits ein vorhandenes Netzwerk haben. \

Funktionen 
---------

\.

-   4 in 1 Detektor: Bewegung, Blende, Temperatur, Licht

-   Nimmt den aktuellen Z-Wave 400series-Chip zur Unterstützung an
    Mehrkanalbetrieb und mehr Datendurchsatz
    hoch (9,6 / 40 / 100kbps)

-   Verwendet das Z-Wave 6.02 SDK

-   Optimierte Antennenreichweite

-   Verwendung für Hausautomations- oder Sicherheitsanwendungen

-   Taste zum Ein- / Ausschließen des Detektors

-   Autoprotection

-   Anzeige für niedrigen Batteriestand

-   Klein, diskret und ästhetisch

-   Benutzerfreundlichkeit und Installation

\.

Technische Daten 
---------------------------

\.

-   Modultyp : Z-Wave Sender

-   Versorgung : 1 CR123A 3V Batterie

-   Akkulaufzeit : 2 Jahre

-   Frequenz : 868.42 MHz

-   Übertragungsentfernung : 30m drinnen

-   Temperatursensor : -10 bis 70 ° C.

-   Helligkeitssensor : 0 bis 500 Lux

-   PIR-Erfassungswinkel : 90 °

-   PIR-Erfassungsbereich : 8 bis 10 m

-   Abmessungen :

-   Detektor : 28 x 96 x 23 mm

-   Magnet : 10 x 50 x 12 mm

-   Gewicht : 52g

-   Betriebstemperatur : -10 bis 40 ° C.

-   Betriebsfeuchtigkeit : 85% rF max

-   CE-Norm : EN300 220-1

-   Z-Wave-Zertifizierung : ZC08-13050003

\.

Moduldaten 
-----------------

\.

-   Machen Sie : Philio Technology Corporation

-   Name : PST02-A 4-in-1-Multisensor

-   Hersteller ID : 316

-   Produkttyp : 2

-   Produkt-ID : 12

\.

Konfiguration 
-------------

\.

So konfigurieren Sie das OpenZwave-Plugin und wissen, wie Sie Jeedom einsetzen
Aufnahme beziehen sich darauf
[Dokumentation](https://jeedom.fr/doc/documentation/plugins/openzwave/de_DE/openzwave.html).

\.

> **Wichtig**
>
> Um dieses Modul in den Einschlussmodus zu versetzen, drücken Sie die Taste dreimal
> Einschlussknopf gemäß seiner Papierdokumentation.

\.

![inclusion](images/philio.pst02a/inclusion.jpg)

\.

Einmal enthalten, sollten Sie dies erhalten :

\.

![Plugin Zwave](images/philio.pst02a/information.jpg)

\.

### Befehle 

\.

Sobald das Modul erkannt wurde, werden die dem Modul zugeordneten Befehle ausgeführt
disponibles.

\.

![Befehle](images/philio.pst02a/commandes.jpg)

\.

Hier ist die Liste der Befehle :

\.

-   Präsenz : Es ist der Befehl, der eine Anwesenheitserkennung erkennt

-   Öffnung : Es ist der Befehl, der eine Erkennung auslöst
    d'ouverture

-   Temperatur : es ist der Befehl, der es erlaubt, die
    Temperatur

-   Helligkeit : Es ist der Befehl, der es ermöglicht, die Helligkeit zu erhöhen

-   Sabotage : Dies ist der Sabotagebefehl (er wird ausgelöst in
    herausreißen)

-   Batterie : Es ist der Batteriebefehl

\.

### Konfiguration des Moduls 

\.

> **Wichtig**
>
> Wecken Sie das Modul bei einer ersten Aufnahme immer gleich danach auf
> Einbeziehung.

\.

Dann, wenn Sie das Modul entsprechend konfigurieren möchten
Ihrer Installation müssen Sie durch die Schaltfläche gehen
"Konfiguration "des OpenZwave-Plugins von Jeedom.

\.

![Konfiguration plugin Zwave](images/plugin/bouton_configuration.jpg)

\.

Sie gelangen auf diese Seite (nachdem Sie auf die Registerkarte geklickt haben
Einstellungen)

\.

![Config1](images/philio.pst02a/config1.jpg)

![Config2](images/philio.pst02a/config2.jpg)

![Config3](images/philio.pst02a/config3.jpg)

\.

Parameterdetails :

\.

-   2: Ermöglicht das Anpassen des an die Module in der Gruppe gesendeten Signals
    Verein 2

-   3: Stellt die Empfindlichkeit des Anwesenheitssensors ein (0 :
    deaktiviert 99: maximale Empfindlichkeit)

-   4: Stellt die Helligkeitsstufe ein, ab der die
    Das in Parameter 2 definierte Signal wird an die Module gesendet, die dem zugeordnet sind
    Gruppe 2

-   5: Betriebsart (siehe die
    Herstellerdokumentation) Empfohlener Wert : 8

-   6: Multisensor-Betriebsart (siehe
    Herstellerdokumentation) Empfohlener Wert : 4

-   7: personalisierte Multisensor-Betriebsart (siehe
    auf der Dokumentation des Herstellers) Empfohlener Wert : 6 (für
    eine Rückkehr zu AUS der Anwesenheit haben)

-   8: Ermöglicht die Definition der Dauer in Schritten von 8 Sekunden für die erneute Erkennung
    der Bewegung

-   9: Ermöglicht die Festlegung, wie lange das AUS-Signal dauern soll
    wird an Module gesendet, die der Gruppe 2 zugeordnet sind

-   10: Mit dieser Option können Sie die Dauer zwischen zwei Batterieberichten definieren (einer
    Einheit = Parameter 20)

-   11: Mit dieser Option können Sie die Dauer zwischen zwei sich selbst öffnenden Berichten definieren
    (eine Einheit = Parameter 20)

-   12: Hier können Sie die Dauer zwischen zwei Auto definieren
    Helligkeit (eine Einheit = Parameter 20) Empfohlener Wert : 3

-   13: Hier können Sie die Dauer zwischen zwei Auto definieren
    Temperatur (eine Einheit = Parameter 20) Empfohlener Wert : 2

-   20: Dauer eines Intervalls für Parameter 10 bis 13 Wert
    empfohlen : 10

-   21: Temperaturänderungswert in ° F zum Auslösen von a
    rapport

-   22: Wert in% der Helligkeitsschwankung zum Auslösen von a
    Empfohlenen Wert melden : 10

\.

### Gruppen 

\.

Dieses Modul hat zwei Zuordnungsgruppen, nur die erste
indispensable.

\.

![Groupe](images/philio.pst02a/groupe.jpg)

\.

Gut zu wissen 
------------

\.

### Alternative visuelle 

\.

![vuewidget](images/philio.pst02a/vuewidget.jpg)

\.

Aufwachen 
------

\.

Um dieses Modul aufzuwecken, gibt es nur einen Weg :

-   Lassen Sie die Sabotage-Taste los und drücken Sie sie erneut

\.

Faq. 
------

\.

Dieses Modul wird durch Drücken der Sabotage-Taste aktiviert.

\.

Dieses Modul ist ein Batteriemodul, die neue Konfiguration wird sein
beim nächsten Aufwachen berücksichtigt.

\.

Wichtiger Hinweis 
---------------

\.

> **Wichtig**
>
> Sie müssen das Modul aufwecken : nach seiner Aufnahme, nach einer Änderung
> der Konfiguration, nach einer Änderung des Aufweckens, nach a
> Änderung der Assoziationsgruppen

\.

**@sarakha63**
