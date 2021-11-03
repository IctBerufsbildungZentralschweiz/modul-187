# WLAN

Wireless Local Area Network (kurz Wireless LAN oder W-LAN, meist WLAN oder drahtloses lokales Netzwerk) bezeichnet ein lokales Funknetz, wobei meist ein Standard der IEEE-802.11-Familie gemeint ist. Im Englischen und in weiteren Sprachen wird ein drahtloses Netzwerk umgangssprachlich als Wi-Fi bezeichnet. Technisch bezeichnen WLAN und Wi-Fi zwei verschiedene Dinge: WLAN bezeichnet das Funknetzwerk, Wi-Fi hingegen die Zertifizierung durch die Wi-Fi Alliance anhand des IEEE-802.11-Standards.

In unserem Alltag sind wir umgeben von vielen Funknetzen mit verschiedenen Funkbändern. Wir begegnen Installationen fast an jeder Ecke. Aber eben nur an fast jeder, denn physikalische Gesetzmässigkeiten, räumliche Gegebenheiten und gesetzliche Vorschriften verhindert eine uneingeschränkte Verbreitung.

Letztere lassen sich meist nicht verändern. Die optimale Ausnutzung der technischen Möglichkeiten kann allerdings eine Vielzahl von Problemen beseitigen, teilweise Wireless-Netze sogar erst ermöglichen.

**Betriebsarten**: WLANs werden je nach Hardwareausstattung und Bedürfnissen unterschiedlich angewendet.

#### Tethering / Hotspot

Tethering (deutsch: Anbinden) bezeichnet die Verbindung eines Smartphones mit einem Client, um diesem eine Internetverbindung über GSM/UMTS/LTE zu ermöglichen. Das Mobiltelefon übernimmt damit die Rolle eines Modems.

Die Anbindung erfolgt meist Kabelgebunden (USB) oder drahtlos (Bluetooth). Wird die Anbindung über das WLAN erstellt, spricht man von einem Hotspot. ![](../../.gitbook/assets/hotspot.jpg)

![Tethering / Hotspot](../../.gitbook/assets/wlan\_tethering\_hotspot.png)

#### Ad-hoc-Modus

Im Ad-hoc-Modus ist keine Station besonders ausgezeichnet, sondern alle sind gleichwertig. Ad-hoc-Netze lassen sich schnell und ohne grossen Aufwand aufbauen, für die spontane Vernetzung weniger Endgeräte sind allerdings andere Techniken (Bluetooth, Infrarot) eher gebräuchlich.

Die Voraussetzungen für den Ad-hoc-Modus sind dieselben wie für den Infrastruktur-Modus: Alle Stationen benutzen denselben Netzwerknamen („Service Set Identifier“, SSID) und optional dieselben Einstellungen für die Verschlüsselung. Da es in einem Ad-hoc-Netz keine zentrale Instanz (Access Point) gibt, muss deren koordinierende Funktion von den Endgeräten übernommen werden.

![Ad-hoc-Modus](<../../.gitbook/assets/wlan\_thetering\_ad hoc.png>)

#### Infrastruktur-Modus

Der Infrastruktur-Modus ähnelt im Aufbau dem Mobilfunknetz: Ein drahtloser Router oder ein\
Access Point übernimmt die Koordination aller anderen Netzknoten (Clients). Dieser sendet in einstellbaren Intervallen (üblicherweise zehnmal pro Sekunde) kleine Datenpakete, sogenannte\
„Beacons“ (engl. „Leuchtfeuer“), an alle Stationen im Empfangsbereich. Die Beacons enthalten\
u. a. folgende Informationen:

* Netzwerkname („Service Set Identifier“, SSID)
* Liste unterstützter Übertragungsraten
* Art der Verschlüsselung

![Infrastruktur-Modus](<../../.gitbook/assets/wlan\_Infrastruktur Modus.png>)

Dieses „Leuchtfeuer“ erleichtert den Verbindungsaufbau erheblich, da die Clients lediglich den Netzwerknamen und optional einige Parameter für die Verschlüsselung kennen müssen. Gleichzeitig ermöglicht der ständige Versand der Beacon-Pakete die Überwachung der Empfangsqualität – auch dann, wenn keine Nutzdaten gesendet oder empfangen werden. Beacons werden immer mit der niedrigsten Übertragungsrate (1 MBit/s) gesendet, der erfolgreiche Empfang des „Leuchtfeuers“ garantiert also noch keine stabile Verbindung mit dem Netzwerk.

Da WLAN auf der Sicherungsschicht (Schicht 2 im OSI-Modell) dieselbe Adressierung wie Ethernet verwendet, kann über einen Wireless Access Point mit Ethernet-Anschluss leicht eine Verbindung zu kabelgebundenen Netzen hergestellt werden. Eine Ethernet-Netzwerkkarte kann folglich nicht unterscheiden, ob sie mit einer anderen Ethernet-Netzwerkkarte oder (über einen Access Point) mit einer WLAN-Karte kommuniziert. Allerdings muss zwischen 802.11 (WLAN) und 802.3 (Ethernet) konvertiert werden.

#### Frequenzen und Spezifikationen

Für drahtlose Netzwerke sind bisher zwei lizenzfreie Frequenzblöcke (2,4 und 5GHz) aus den ISM-Bändern (**I**ndustrial, **S**cience, **M**edical – Band) freigegeben worden.\
Neu wird für den 802.11ad Standard auch das 60 GHz Band benutzt.

![IMS Band](<../../.gitbook/assets/Wlan IMS Band.png>)

Das 2,4GHz Band geht von 2,400 bis 2,4840 GHz und ist in 13 Kanäle (ETSI) unterteilt. Betreibt man ein WLAN mit mehreren Access Points in einer Site, so müssen die Kanäle mit einem Abstand von min. 4 Kanälen zueinander vergeben werden, optimal (Ch.1 - Ch.6 - Ch.11) bzw. (Ch.1 - Ch.7 - Ch.13). Diese Verfahrensweise rührt daher, dass sich benachbarte Kanäle zu einem Drittel überlagern. Dies gilt für den 802.11b Standard genau sowie für den 802.11g Standard.

![WLAN Bandbreiten](<../../.gitbook/assets/WLAN Bandbreiten.jpg>)

Das 5GHz Band ist definiert von 5,150 bis 5,825 GHz. In Europa werden die Frequenzen 5,15 GHz - 5,35 GHz (innerhalb von Gebäuden) und 5,47 GHz - 5,735 GHz (innerhalb und ausserhalb von Gebäuden) verwendet (nach Standard 802.11h).

![WLAN Kanalfrequenzen](<../../.gitbook/assets/WLAN Kanalfrequenzen.jpg>)

**Datenübertragungsraten**

Seit 1997 gibt es die Ethernet-Variante IEEE 802.11, die eine verbindliche Luftschnittstelle darstellt. Davor war der breite Einsatz drahtloser Datennetze wegen der fehlenden Standardisierung und der geringen Datenübertragungsrate undenkbar.

IEEE 802.11 ist keine Neuerfindung. Der Standard baut auf den anderen Standards von IEEE 802 auf. IEEE 802.11 ist, vereinfacht ausgedrückt, eine Art schnurloses Ethernet.

![Tabelle IIE 802.11](<../../.gitbook/assets/wlan IEEE 802.11.png>)

Die Kanalbandbreite beträgt bei 802.11a, b und g 20 MHz und bei 802.11n 40 MHz. 802.11ac verwendet Kanäle mit 20, 40, 80 MHz und 160MHz optional.

Bei der Betrachtung der Datenübertragungsraten ist zu berücksichtigen, dass sich alle Geräte im Netz die Bandbreite für Up- und Download teilen. Weiterhin sind die angegebenen Datenübertragungsraten Bruttowerte, und selbst unter optimalen Bedingungen liegt die erreichbare Nettoübertragungsrate nur wenig über der Hälfte dieser Angaben.

**802.11ax / WiFi 6**

802.11ax ist die nächste Generation des Wi-Fi-Standards, der seit Jahren kontinuierlich weiter-entwickelt wird und mit dieser auch als **Wi-Fi 6** bezeichneten Version einmal mehr eine Innovation einführt. Der Standard baut auf den Vorteilen von 802.11ac auf und erweitert sie um Effizienz, Flexibilität und Skalierbarkeit. So ermöglicht er höhere Geschwindigkeiten und Kapazitäten für Anwendungen der nächsten Generation, sowohl in neuen als auch in bereits vorhandenen Netzwerken.

Relevanz: Wi-Fi kann jetzt in prall gefüllten Stadien oder Flughäfen implementiert werden – mit Hunderten oder Tausenden von Geräten, die um die verfügbare Bandbreite kämpfen und die der aktuelle Standard 802.11ac nur mit Mühe unterstützen kann. In Szenarios mit hoher Benutzerdichte verbessert 802.11ax den durchschnittlichen Durchsatz pro Benutzer um den Faktor 4.

**GHz- und Netzwerk-Reichweite**

Je höher die Frequenz eines drahtlosen Signals ist, desto kürzer seine Reichweite. So decken 2,4 GHz Netzwerke eine wesentlich grössere Reichweite ab als 5 GHz Wireless-Netzwerke. Insbesondere durchdringen die höheren Signale von 5 GHz-Netzwerken, feste Gegenstände nicht so gut, wie 2,4-GHz-Signale. Dies Begrenzt ihre Reichweite in Häusern. ð Vorteil: 2,4 GHz

&#x20;**GHz- und Netzwerk-Störungen (Network Interference)**

Sie können feststellen, dass Ihr schnurloses Telefon, automatische Garagentoröffner oder andere Haushaltsgeräte meistens auf dem 2,4 GHz Band betrieben werden. Störenden Interferenzen von Geräten sind deshalb in diesem Frequenzbereich häufiger anzutreffen als in einem 5-GHz-Heimnetzwerk. ð Vorteil: 5 GHz
