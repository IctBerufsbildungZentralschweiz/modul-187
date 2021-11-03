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

