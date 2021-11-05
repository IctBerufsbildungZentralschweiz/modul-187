# Testfälle

Das Schreiben von Testfällen hängt davon ab, was der Testfall misst oder testet. Dies ist auch eine Situation, in der das Teilen von Testressourcen zwischen Entwicklern und Testteams das Testen von Software oder Hardware beschleunigen kann. Aber alles beginnt damit, zu wissen, wie man einen Testfall effektiv und effizient schreibt.

Testfälle haben einige integrale Bestandteile, die in Feldern immer vorhanden sein sollten. Jeder Testfall kann jedoch in **8 grundlegende Schritte** unterteilt werden.

**Schritt 1:** Testfall-ID

Testfälle sollten alle eindeutige IDs tragen, um sie darzustellen. In den meisten Fällen hilft das Befolgen einer Konvention für diese Namens-ID bei der Organisation, Klarheit und dem Verständnis.

**Schritt 2:** Testbeschreibung

Diese Beschreibung sollte detailliert beschreiben, welche Einheit, Funktion oder Funktion getestet oder verifiziert wird.

**Schritt 3:** Annahmen und Voraussetzungen

Dies beinhaltet alle Bedingungen, die vor der Ausführung des Testfalls erfüllt sein müssen. Ein Beispiel wäre das Erfordernis eines gültigen Outlook-Kontos für eine Anmeldung.

**Schritt 4:** Testdaten

Dies bezieht sich auf die Variablen und ihre Werte im Testfall. Im Beispiel einer E-Mail-Anmeldung sind dies der Benutzername und das Kennwort für das Konto.

**Schritt 5:** Auszuführende Schritte

Dies sollten leicht wiederholbare Schritte sein, wie sie aus Sicht des Endbenutzers ausgeführt werden. Ein Testfall für die Anmeldung bei einem E-Mail-Server kann beispielsweise die folgenden Schritte umfassen:

1. Öffnen Sie die E-Mail-Server-Webseite.
2. Geben Sie den Benutzernamen ein.
3. Passwort eingeben.
4. Klicken Sie auf "Enter" oder "Login".

**Schritt 6:** erwartetes Ergebnis

Dies zeigt das Ergebnis an, das nach der Ausführung des Testfallschritts erwartet wird. Nach Eingabe der richtigen Anmeldeinformationen wäre das erwartete Ergebnis eine erfolgreiche Anmeldung.

**Schritt 7:** Tatsächliches Ergebnis und Nachbedingungen

Im Vergleich zum erwarteten Ergebnis können wir den Status des Testfalls bestimmen. Im Falle der E-Mail-Anmeldung würde der Benutzer entweder erfolgreich angemeldet sein oder nicht. Die Nachbedingung ist das, was als Ergebnis der Schrittausführung geschieht, z. B. wenn sie in den E-Mail-Posteingang umgeleitet wird.

**Schritt 8:** Pass / Fail

Die Bestimmung des Bestanden / Nicht Bestanden-Status hängt davon ab, wie das erwartete Ergebnis und das tatsächliche Ergebnis miteinander verglichen werden.

Gleiches Ergebnis = Bestanden\
Unterschiedliche Ergebnisse = Fehlschlagen

### Aufgabe

Versuch einen Testfall zu beschreiben für das Aufspielen der Firmware auf dem M5Stack, welches du ja bereits am 1.Tag gemacht hast. Du kannst dazu Word oder Excel verwenden.&#x20;
