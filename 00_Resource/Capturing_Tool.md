Das Videocapturing für die Speed-CAD-Championship soll ausschließlich mit OBS Studio stattfinden.
Man erhält es hier: 

https://github.com/obsproject/obs-studio/releases/download/29.1.3/OBS-Studio-29.1.3.zip

Diese ZIP muss nicht installiert werden, sondern nur entpackt. 
* Dann im BIN\64bit Unterordner die OBS64.exe ausführen. 
* Unten links bei Quellen die Bildschirmaufnahme wählen, 
* dann das Zahnrad für die Einstellungen. 
* Aufnahmemethode: Win10 und höher (wenn zutreffend) 
* dann den richtigen Bildschirm wählen, 
* Mauszeiger aufnehmen anklicken. 
* Okay

Dann unten rechts Einstellungen anpassen:
* Allgemein: Allgemein- OBS-Fenster vor Bildschirmaufnahmen verstecken anklicken. ggf. bestätigen
* Ausgabe: Aufnahme - Aufnahmepfad: Passenden Ordner für die Ausgabe wählen.
* Ausgabe: Aufnahmequalität: HoheQualität, mittelgroße Dateien
* Aufnahmeformat: MPEG-4
* Videoencoder:  Wenn möglich Hardware (NVENC.H.264) sonst Software
* Audioencoder: AAC
* Audio: Globale Audiogeräte: Gerne alle auf Deaktiviert. Es muss kein Ton mit hochgeladen werden.
* Video: Basis-Auflösung muss mit der eingestellten Auflösung des gefilmten Bildschirms übereinstimmen.
* Video: Skalierte Ausgabeauflösung: Hier reicht 1920x1080.
* Video: Skalierungsfilter: Bicubic reicht.
* Video: FPS Werte 60 FPS, 30 geht aber auch
* Mit OK bestätigen. Vorbereitungen fertig.
* 
* Dann beim Loslaufen: Aufnahme starten, OBS Fenster minimieren.
* Zum Stoppen wieder maximieren, unten rechts Aufnahme stoppen.

