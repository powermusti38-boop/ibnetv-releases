# GB Helfer

Öffentliche, signierte APK-Dateien. Quellcode und Signierschlüssel bleiben privat.

0.8.3: Vor jeder neuen Aufnahme und Wiedergabe wird die Launcher-Activity der Ziel-App mit einer geleerten Android-Aufgabe neu gestartet (NEW_TASK + CLEAR_TASK). Das gilt auch für den Zehn-Minuten-Zeitplan. Der Ablauf wartet zunächst mindestens 1,5 Sekunden auf den Wechsel und danach auf ein stabiles sichtbares Zielfenster. Bei späterem Fokusverlust wird die bestehende Aufgabe zurückgeholt und das Makro am nächsten Schritt fortgesetzt, ohne einen erneuten Reset.

Keine automatische App-Info. Anmeldung, App-Daten und Makroformat bleiben erhalten. Dies ist ein neuer Activity-/Task-Start, kein erzwungener Neustart des gesamten Prozesses. Eine Ziel-App kann ihren eigenen gespeicherten Zustand wiederherstellen. Makros, die bisher auf einer geöffneten Unterseite begannen, bitte ab der neuen Startansicht aufnehmen.

Nach dem Speichern oder der Wiedergabe wird weiterhin die Zieltaskkarte gezielt geschlossen und die vorherige App fortgesetzt. GB Helfer und der eingeschaltete Zehn-Minuten-Zeitplan bleiben im Hintergrund aktiv. Die Abschlussmeldung nennt das tatsächliche Ergebnis der Taskentfernung. Bei fehlender eindeutiger Aktion, Sperrbildschirm oder App-Wechsel wird kein bestätigtes Entfernen behauptet.

Ab 0.7.0 über „Nach Updates suchen“ installierbar. Signierschlüssel und vorhandene Makros bleiben kompatibel. Benachrichtigungen für GB Helfer erlauben. 60 Unit-Tests und Android Lint bestanden; Poco-/LDPlayer-Gerätetest steht aus.
