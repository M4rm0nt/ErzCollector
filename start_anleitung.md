# Anleitung zum Starten von "ErzCollector"

Um "ErzCollector" zu starten, befolge bitte die folgenden Schritte. Diese Anleitung setzt voraus, dass du Python auf deinem Computer installiert hast und ein grundlegendes Verständnis von Terminals oder Kommandozeileninterfaces besitzt.
### Python Installation (falls nicht vorhanden):
- **Unter Linux:**
  Falls Python noch nicht installiert ist, kannst du es in den meisten Linux-Distributionen über das Paketverwaltungssystem installieren. Zum Beispiel kannst du in Ubuntu oder Debian folgenden Befehl im Terminal ausführen:

**sudo apt update**

**sudo apt install python3**

 Falls du Fedora Linux gebnutzt, kannst du folgenden Befehl ausführen:

**sudo dnf update**

**sudo dnf install python3**

  Überprüfe die Installation, indem du `python3 --version` im Terminal ausführst.

- **Unter MacOS:**
  MacOS wird mit einer Version von Python vorinstalliert. Du kannst prüfen, ob Python bereits installiert ist, indem du im Terminal den Befehl `python3 --version` ausführst. Wenn nicht, kannst du Python über Homebrew oder den offiziellen Python-Installer installieren.

- **Unter Windows:**
- Du kannst Python von der offiziellen Website herunterladen und den Installationsprozess durchführen. Stelle sicher, dass du das Kontrollkästchen "Add Python to PATH" während der Installation aktivierst, um Python im Terminal verfügbar zu machen.
- Alternativ kannst du Python über den Microsoft Store oder Chocolatey installieren.

Überprüfe die Installation, indem du `python --version` im Terminal ausführst.

## Schritte zum Starten des Spiels:
### Öffne das Terminal:
- **Unter Windows:** Drücke Win + R, tippe `cmd` ein und drücke Enter.
- **Unter MacOS:** Öffne Spotlight, suche nach "Terminal" und starte es.
- **Unter Linux:** Drücke Ctrl + Alt + T oder suche nach "Terminal" in deinen Anwendungen.

### Navigiere zum Spielordner:
Im Terminal navigierst du zum Verzeichnis, in dem sich dein Spiel befindet, indem du den Befehl `cd` (Change Directory) verwendest. Basierend auf deinem Beispiel würde der Befehl so aussehen:

**cd ~/ErzCollector**

Stelle sicher, dass du den Pfad entsprechend deiner Verzeichnisstruktur anpasst.

### Hinweise:
Stelle sicher, dass du alle benötigten Abhängigkeiten installiert hast. Das kann Module oder Bibliotheken umfassen, die das Spiel benötigt. In der Regel werden diese in einer Datei namens `requirements.txt` aufgelistet und können mit folgendem Befehl installiert werden:

**pip install -r requirements.txt**

Die oben genannten Befehle können je nach Betriebssystem oder Python-Konfiguration variieren. Die Befehle sind typisch für Linux und MacOS. Windows-Nutzer müssen eventuell Anpassungen vornehmen.

### Aktiviere die virtuelle Umgebung (optional):
Wenn du eine virtuelle Umgebung verwendest (was in deinem Beispiel der Fall zu sein scheint), aktiviere sie mit dem folgenden Befehl:

**source .venv/bin/activate**

Unter Windows könnte der Befehl leicht variieren:

**.venv\Scripts\activate**

Wenn du die virtuelle Umgebung erfolgreich aktiviert hast, siehst du ihren Namen in Klammern am Anfang der Terminalzeile (z.B. `(.venv)`).

### Starte das Spiel:
Nachdem du dich im richtigen Verzeichnis befindest und die virtuelle Umgebung aktiviert hast, starte das Spiel mit folgendem Befehl:

**python main.py**

Wenn du mehrere Python-Versionen installiert hast, musst du möglicherweise `python3` statt `python` verwenden.
Auf manchen Systemen musst du eventuell `py` statt `python` verwenden.

### Spielanleitung:
Eine ausführliche Spielanleitung findest du in der Datei `spiel_anleitung.md`. Du kannst sie mit einem Texteditor deiner Wahl öffnen oder direkt im Terminal anzeigen lassen:

**cat spiel_anleitung.md**

oder, um durch den Text zu scrollen:

**less spiel_anleitung.md**

Sobald das Spiel läuft, folge den Anweisungen auf dem Bildschirm, um zu spielen. Viel Spaß beim Sammeln des Erzes!

