BLUES TIMER PLUGIN V1.0 ab OBS v32.2.2
Installationsanleitung

Vielen Dank, dass du dich für das Blues Timer Plugin V1.0 von BlueScorpion71 entschieden hast.

Die Installation ist einfach und benötigt keine besonderen Kenntnisse.

Bitte beachte die folgenden Schritte.

1. ZIP-Archiv öffnen

Öffne das heruntergeladene ZIP-Archiv mit dem Windows-Datei-Explorer.

Du kannst das ZIP-Archiv direkt öffnen oder es vorher auf dem Desktop bzw. an einem anderen Ort deiner Wahl entpacken.

Beides ist möglich.

Öffne anschließend den Ordner:

BlueScorpion71_Timer_V1.0

Darin befinden sich die für die Installation benötigten Ordner:

data
obs-plugins
2a. INSTALLIERTE OBS-VERSION

Wenn du die normale, unter Windows installierte OBS-Version verwendest, befindet sich dein OBS-Installationsordner normalerweise hier:

C:\Program Files\obs-studio\

Falls du OBS bei der Installation an einem anderen Ort abgelegt hast, verwendest du entsprechend diesen Ordner.

Plugin-Datei – das Herzstück

Die Datei

Blues_Timer_Plugin_V1.0.dll

ist das Herzstück des Blues Timer Plugins.

Sie enthält die Funktionen des Timers und sorgt dafür, dass das Plugin in OBS verwendet werden kann.

Die Datei befindet sich im ZIP bereits im richtigen Ordner:

obs-plugins
└── 64bit
    └── Blues_Timer_Plugin_V1.0.dll

Kopiere den Ordner obs-plugins in den OBS-Installationsordner:

C:\Program Files\obs-studio\

Die vorhandene Ordnerstruktur bleibt dabei erhalten.

Der Ordner data

Der Ordner data enthält die zusätzlichen Dateien, die das Blues Timer Plugin für seine Funktionen benötigt.

Dazu gehören die Sounddateien für die Timer-Signale.

Die Struktur sieht so aus:

data
└── obs-plugins
    └── Blues_Timer_Plugin_V1.0
        ├── Horn_Dampfer_2.mp3
        └── timer_horn.mp3

Kopiere auch den Ordner data in den OBS-Installationsordner:

C:\Program Files\obs-studio\

Auch hier bleibt die vorhandene Ordnerstruktur erhalten.

Du musst die einzelnen Dateien nicht von Hand in die Unterordner verteilen.

2b. PORTABLE OBS-VERSION

Wenn du eine portable OBS-Version verwendest, öffne den Hauptordner deiner portablen OBS-Version.

Kopiere die Ordner data und obs-plugins aus dem Ordner

BlueScorpion71_Timer_V1.0

in diesen Hauptordner.

Die vorhandene Ordnerstruktur bleibt dabei erhalten.

Du musst die einzelnen Dateien nicht von Hand in die Unterordner verteilen.

Nach dem Kopieren befinden sich die Dateien entsprechend der vorhandenen OBS-Struktur unter:

obs-plugins\64bit\Blues_Timer_Plugin_V1.0.dll

und:
data\obs-plugins\Blues_Timer_Plugin_V1.0\


3. OBS starten und Plugin prüfen

Öffne in OBS die Quellen-Auswahl.

Suche dort nach:

Blues Timer Plugin V1.0

Wenn das Plugin dort angezeigt wird, ist die Installation erfolgreich abgeschlossen.

4. Installation abgeschlossen

Das Blues Timer Plugin V1.0 ist jetzt installiert.

Du kannst den Datei-Explorer schließen und das Plugin in OBS verwenden.

Eine separate Anleitung zur Einrichtung und Bedienung des Timers folgt unabhängig von dieser Installationsanleitung.

BlueScorpion71
Blues Timer Plugin V1.0
Copyright © 2026 BlueScorpion71