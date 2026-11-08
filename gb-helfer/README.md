# GB Helfer

Öffentliche, signierte APK-Dateien. Quellcode und Signierschlüssel bleiben privat.

0.8.1: Nach dem Speichern einer Aufnahme und nach beendeter Wiedergabe öffnet GB Helfer die Android-App-Info des Zielpakets, betätigt die passende Schaltfläche „Stopp erzwingen“/„Beenden erzwingen“ oder „Force stop“ und bestätigt nur den zugehörigen Systemdialog. Anschließend wird der Android-Paketstatus FLAG_STOPPED kontrolliert. Eine verbliebene, eindeutig erkannte Zieltaskkarte wird gezielt aus „Letzte Apps“ entfernt. Keine Root-/ADB-Rechte; keine Datenlöschung oder Deinstallation.

Danach wird die vorherige App über ihre vorhandene Aufgabe fortgesetzt, soweit kein manueller App-Wechsel oder Sperrbildschirm dazwischenkommt. GB Helfer und der eingeschaltete Zehn-Minuten-Zeitplan bleiben im Hintergrund aktiv. Beim nächsten geplanten Start öffnet sich die Ziel-App wieder regulär.

Eine Benachrichtigung nennt App-Stopp und Taskprüfung getrennt. Bei nicht bestätigtem Stopp oder nicht bestätigter Taskentfernung erscheint „App-Abschluss prüfen“. Android-/Hersteller-Oberflächen müssen ihre passenden Bedienelemente über die Bedienungshilfe bereitstellen; die Erkennung arbeitet ohne Koordinatenklicks in Einstellungen. Wenn bereits keine Zielkarte mehr erkennbar ist, wird die vollständige Taskentfernung nicht behauptet. Benachrichtigungen für GB Helfer erlauben.

Ab 0.7.0 über „Nach Updates suchen“ installierbar. Vorhandene Makros und Signierschlüssel bleiben kompatibel. 72 Unit-Tests und Android Lint bestanden; Poco-/LDPlayer-Gerätetest steht aus.

Aus 0.8.0: überwachte Wiedergabe mit Zeitlimits, Warte-Countdown, kontrollierter App-Rückholung, Touchschutz und bunter verschiebbarer/einklappbarer Makroleiste. Für Bildschirm-Eingaben muss die Ziel-App sichtbar sein. Während Koordinatengesten ist eine kurze Freigabe im engen Gestenbereich nötig.
