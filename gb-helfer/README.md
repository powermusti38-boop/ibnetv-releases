# GB Helfer

Öffentliche, signierte APK-Dateien. Quellcode und Signierschlüssel bleiben privat.

0.8.2: Nach dem Speichern einer Aufnahme oder beendeter Wiedergabe wird direkt die Zieltaskkarte aus „Letzte Apps“ geschlossen. Der automatische App-Info-/Force-Stop-Ablauf aus 0.8.1 ist vollständig entfernt. Anschließend kehrt GB Helfer zur vorherigen App in ihrer vorhandenen Aufgabe zurück. Die Aufnahme wird vor dem Schließen auf erfolgreichen Speichervorgang geprüft.

GB Helfer und der eingeschaltete Zehn-Minuten-Zeitplan bleiben im Hintergrund aktiv. Die Abschlussmeldung nennt das tatsächliche Ergebnis der Taskentfernung. Das gezielte Schließen hängt von der durch Android/LDPlayer bereitgestellten Bedienungshilfe-Aktion ab. Bei fehlender eindeutiger Aktion, Sperrbildschirm oder App-Wechsel wird kein bestätigtes Entfernen behauptet. Task-Schließen ist kein erzwungener Stopp aller Hintergrundprozesse.

Ab 0.7.0 über „Nach Updates suchen“ installierbar. Vorhandene Makros und Signierschlüssel bleiben kompatibel. Benachrichtigungen für GB Helfer erlauben. 60 Unit-Tests und Android Lint bestanden; Poco-/LDPlayer-Gerätetest steht aus.

Aus 0.8.0: überwachte Wiedergabe mit Zeitlimits, Warte-Countdown, kontrollierter App-Rückholung, Touchschutz und bunter verschiebbarer/einklappbarer Makroleiste. Für Bildschirm-Eingaben muss die Ziel-App sichtbar sein. Während Koordinatengesten ist eine kurze Freigabe im engen Gestenbereich nötig.
