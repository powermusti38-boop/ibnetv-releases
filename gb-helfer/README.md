# GB Helfer

Öffentliche signierte APK; Quellcode und Schlüssel bleiben privat.

0.8.4: Frei wählbares Wiederholungsintervall von 1–999 Minuten. Das Eingabefeld erlaubt maximal drei ASCII-Ziffern. Null und leere Eingaben werden abgelehnt. Mit „Intervall speichern“ wird der Wert übernommen und der nächste Start ab jetzt neu geplant. Beim Einschalten wird das Feld ebenfalls übernommen. Bestehende Installationen erhalten 10 Minuten als bisherigen Standard. Das Öffnen der App verschiebt einen vorhandenen Termin nicht. Status und Benachrichtigung zeigen das gewählte Intervall.

GB Helfer bleibt im Hintergrund. Die Ziel-App bleibt für die aufgezeichneten Bildschirmklicks sichtbar; sofortiges Verstecken während der Wiedergabe wird nicht unterstützt. Nach Abschluss wird der Zieltask gezielt geschlossen und die vorherige App fortgesetzt. Android kann besonders kurze Intervalle im Energiesparmodus verzögern.

Die Startansicht wird vor jedem neuen Makro wie in 0.8.3 neu aufgebaut; keine automatische App-Info. Anmeldung, App-Daten und Makros bleiben erhalten. Ein Activity-/Task-Neustart ist kein erzwungener Prozessneustart. Selbst gespeicherte Ansichten kann die Ziel-App wiederherstellen.

Ab 0.7.0 über den Update-Button installierbar. 64 Unit-Tests, Android Lint und GitHub-Build bestanden. Poco-/LDPlayer-Gerätetest steht aus.
