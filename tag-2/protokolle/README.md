# Protokolle

Drahtgebundene Protokolle können in verschiedene Kategorien unterschieden werden. Grundsätzlich fliesst ein Strom (>=zwei Drähte, geschlossener Stromkreis ;-)) zwischen mindestens 2 Geräten.

#### Analoge Signale

Analoge Signale werden für Audioübertragung und direkte Signalmessungen verwendet.

Zum Beispiel kann so anhand eines elektrischen Widerstands eine Temperatur gemessen werden.

#### Digitale Signale

übertragen Daten in form von Bits. Die meisten Sensoren werden direkt mit einem einfachen Chip gekoppelt, dass Messwerte in digitale Signale umwandelt.

Es gibt folgende Eigenschaften / Unterschiede digitaler Signalübertragung.

* Synchron vs. Asynchron: Synchrone Datenübertragung benötigt eine Uhr. Asynchrone Kommunikation wird normalerweise mit speziellen Anfangs- und Endbits umschlossen.
* Richtung: Eine Richtung, abwechselnd oder gleichzeitig in beide. Man spricht auch von Simplex, Half-Duplex und Full-Duplex.
* Seriell vs. Parallel: Werden Daten in Reihenfolge oder gleichzeitig übertragen. Das habt ihr bereits im ersten ÜK gelernt. Erinnert ihr euch daran, dass die Kommunikation zwischen CPU und RAM parallel stattfindet und deswegen die Leitungen genau gleich lang sein müssen?

Die Unterscheidung in Master und Slave beschreibt jeweils, wer die Kommunikation steuert und beginnt bzw. wer "nur" reagiert. Es können mehrere Master oder Slave existieren.
