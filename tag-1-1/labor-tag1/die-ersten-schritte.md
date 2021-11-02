# Die ersten Schritte

Als Einstieg bekommt ihr von eurem Instruktor einen Sensor "ENV III" Dieser kann die Temperatur, Luftfeuchtigkeit und Luftdruck messen kann, ist somit ein 3 in 1 Sensor.&#x20;

![](<../../.gitbook/assets/ENV III Sensor.png>)

Schliesst den Sensor am Port <mark style="color:red;">**A **</mark>an und ladet folgende Beispieldatei herunter.

{% file src="../../.gitbook/assets/WeatherStation.m5f" %}

Öffnet diese auf der Web-Programmieroberfläche [https://flow.m5stack.com](https://flow.m5stack.com) und schaut was passiert.

Versucht den Programmcode zu verstehen, somit könnt ihr bereits eure ersten Erfahrungen sammeln.

Fällt euch was auf?

![WeatherStation](../../.gitbook/assets/M5Flow\_WeatherStation.png)

{% hint style="warning" %}
Dieses Programm wurde für einen M5Stack Basic erstellt! Einige Labels können somit nicht angepasst werden, da es diese mit dem M5Stack Core 2 so nicht gibt auf der UI.
{% endhint %}

Ok, kopieren kann jeder, lasst uns nun mit einem eigener Aufgabe beginnen.

### Ihr habt nun folgende Aufgaben:

* [ ] Erstellt für jeden Sensorwert ein Anzeige, damit ihr die Werte auf dem LCD-Screen sehen könnt.
* [ ] Fügt eine Funktion ein, damit wenn ein bestimmter Wert über- oder unterschritten wird der Bildschirmhintergrund die Farbe wechselt. Ihr könnt dazu aber auf die RGB-Bar verwenden.
* [ ] Wie wäre es wenn der Wert über einen "slider" interaktiv verändert werden könnte? Versucht es.
* [ ] Speichert die Messdaten der auf eine microSD-Karte, welche ihr vom Instruktor erhält.
* [ ] Versucht die Messdaten mit Excel auszuwerten und erstellt eine Grafik dazu.
* [ ] Wenn ihr gut in der Zeit seit, könnt ihr noch weitere Funktionen austesten.

{% hint style="warning" %}
Speichert eurer Programm zwischen durch ab, nicht das ihr jeweils von vorne beginnen müsst.
{% endhint %}
