# ⭐ Projektstart KNW

Nach dem schriftlichen Kompetenznachweis und beenden des Vorprojektes, starten wir nun mit der Projektarbeit.

Ihr bekommt für diese Aufgabe eine Projektvorlage:

{% file src="../.gitbook/assets/Projektarbeit_M216_Projekt-Vorlage.docx" %}
Projektvorlage
{% endfile %}

Bearbeitet dieses und gebt es zusammen mit den weiteren Daten auf der "IoT-Projektdaten" der Kursplattform (Moodle) am Tag 5 ab.\
Projektabgabe als **ZIP-File** "<mark style="color:red;">Projektname\_Lernender1+Lernender2.zip</mark>"

Bildet 2er Teams. Die Aufgaben sind in der Gruppe zu lösen und werden auch in der Gruppe bewertet.

### Ihr habt folgende Projektanforderungen:

* [ ] Wählt 2 Produkte (Sensor oder Aktor) für euer Projekt aus.
* [ ] Es müssen min. 2 Interaktionen eingebunden werden.
* [ ] Erstellt eine Kurzbeschreibung über euer Projekt.
* [ ] Definiert die Zielsetzung, Projektziel.
* [ ] Erstellt eine Visualisierung des Projektes.
* [ ] Erstellt ein Planungsfile mit Aufgaben.
* [ ] Erstellt einen UI (User Interface - Benutzeroberfläche auf dem M5Stack.
* [ ] Erstellt ein entsprechendes Dashboard auf io.adafruit.com.
* [ ] Ihr müsst eine technische Dokumentation erstellen.
* [ ] Es müssen mindestens 2 Testfälle vorhanden sein.
* [ ] Erstellt eine Securityanalyse, wie ihr euer Projekt schützen könnt.
* [ ] Erstellt ein Projektfazit am Ende
* [ ] Alle Projektdaten und Anhänge sind bis zum 5. Tag 15 Uhr abzugeben auf der Kursplattform:  [https://kurse.ict-bz.ch](https://kurse.ict-bz.ch).

Folgende Sensoren und Aktoren stehen zur Verfügung:

Sensoren:

* Integrierte Sensoren im M2Stack Core2 Controller (z.B. Mikrofon, 6-Achsen Lage-/Bewegungsmessung)
* ENV.III (Temperatur, Feuchtigkeit, Luftdruck) / PortA (rot)
* Ultrasonic (Distanz) / PortA (rot)
* Heart (Puls, Herzfrequenz) / PortA (rot)
* RFID / PortA (rot)
* Color (Farberkennung) / PortA (rot)
* Earth (Feuchtigkeit in Erde oder ähnlichen Materialien) / PortB (schwarz)
* PIR (Bewegungsmelder) / PortB (schwarz)
* GPS / PortC (blau)

Aktoren:

* Integrierte Aktoren im M2Stack Core2 Controller (z.B. Touchscreen, LED Bar, Lautsprecher, Vibromotor)
* Fan (Lüfter) / PortB (schwarz)
* RGB LED Streifen / PortB (schwarz)

Am I2C-Bus (PortA / rot) können mittels Pa.HUB mehrere Sensoren angeschlossen werden (ausser Heart Unit). An den anderen Anschlüssen (PortB, PortC) lässt sich jeweils nur 1 Sensor oder Aktor anschliessen.



{% hint style="danger" %}
ACHTUNG:

* Die Heart Unit kann nicht an Pa.HUB betrieben werden!
* Die GPS Unit funktioniert nur bedingt im Indoor-Bereich!
{% endhint %}

Das Projekt wird nach der Abgabe den anderen Lernenden vorgestellt mit einer Präsentation (Powerpoint etc.) von max. 2 Seiten und einer Live-Demo. Die Präsentation wird nicht bewertet, jedoch ist es eure Visitenkarte :clap:
