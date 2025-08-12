Installation:

es werden folgende iobroker Adapter benötigt:
- VIS2
- Material Design Widgets for IoBroker VIS
- timeandweather - Time and weather widgets

- entpacke die Zip-Datei in einen temporären Ordner
- Falls noch kein VIS2 Projekt besteht, ein neues Projekt anlegen.
- mit dem VIS2 Dateimanager:
  - einen Ordner mit dem Namen des Projekts als Unterordner des Ordners Vis-2.0
    - in den neu erstellten Ordner wechseln und dort folgende Ordner erstellen
      - img
      - fonts
	- in diese Ordners jeweils die Dateien aus den gleichnamigen Ordnern des oben erstellten temporären Ordners kopieren
- Kopiere den Text der Datei "view.txt" in die Zwischenablage
- klicke im Vis2 Editor links oben auf "Seiten"
- klicke auf die Schaltfläche "importieren"
- entferne den Inhalt der Box und den Text aus dem Zwischenspeicher ein
- vergib einen Namen für das view
- öffne im temporären Ordner die Datei css.txt
- ersetze die beiden Stellen mit ##projektname## mit Deinem Projektnamen (ohne die Rauten!) 
- kopiere den kompletten Code in die Zwischenablage
- klicke im rechten Bereich des Vis2 Editors unter "Attribute" auf "CSS"
- wähle darunter "Für dieses Projekt",
- füge Inhalt der Zwischenablage ein
- öffne im rechten Bereich des Vis2 Editors unter "Attribute" im Tab "Seite" CSS-Hintergrund (background-...)
- klicke bei "Bild" rechts auf die 3 Punkte
- wähle die Datei "Bresser_back arbeit.png" im Unterordner img aus