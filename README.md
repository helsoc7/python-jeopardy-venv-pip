# Jeopardy
Das ist ein einfaches Jeopardy-Spiel innerhalb eines Git-Repositories. Es sind verschiedene Aufgaben vorbereitet, die sich auf verschiedenen Branches dazu befinden. Die Aufgaben sind in Markdown-Dateien in den jeweiligen README-Dateien in den Branches beschrieben. 
Um den Branch zu wechseln, führe den Befehl `git checkout <branch-name>` aus.
Branches:
- `master`: Startpunkt des Spiels
- `feature/csv-with-pandas`: CSV-Dateien bearbeiten mit pandas (Schwierigkeitsgrad: leicht)
- `feature/randomized-numbers`: Zufallszahlen generieren mit random (Schwierigkeitsgrad: sehr leicht)
- `feature/json-data`: JSON-Daten verarbeiten mit json (Schwierigkeitsgrad: leicht)
- `feature/diagrams-with-seaborn`: Diagramme zeichnen mit seaborn (Schwierigkeitsgrad: mittel)
- `feature/textgame-with-pygame`: Textbasiertes Spiel mit Pygame (Schwierigkeitsgrad: schwer)
- `feature/gui-with-tkinter`: GUI mit Tkinter erstellen (Schwierigkeitsgrad: schwer)
- `feature/webscraping-with-request-beautifulsoup4`: Webscraping mit requests und BeautifulSoup4 (Schwierigkeitsgrad: mittel)
- `feature/excel-files-with-openpyxl`: Excel-Dateien bearbeiten mit openpyxl (Schwierigkeitsgrad: mittel)
- `feature/word-processing-with-nltk`: Textverarbeitung mit NLTK (Schwierigkeitsgrad: mittel)
- `feature/time-with-time`: Zeitfunktionen mit time (Schwierigkeitsgrad: sehr leicht)
- `feature/emails-with-smtplib`: E-Mails senden mit smtplib (Schwierigkeitsgrad: mittel)

Für alle Aufgaben gilt:
- Lese die Anweisungen in der README-Datei des jeweiligen Branches.
- Erstelle dir eine virtuelle Umgebung und installiere die benötigten Bibliotheken.
- Halte die Abhängigkeiten in einer `requirements.txt` Datei fest.
- Erstelle eine `.gitignore` Datei, um sensible oder temporäre Dateien  und die venv auszuschließen.
- Führe die Aufgaben aus und versuche, die gestellten Probleme zu lösen.
- Dokumentiere deine Lösungen und speichere sie in einem Git-Repository.

## `feature/csv-with-pandas` 
Ziel: Arbeite mit CSV-Daten, indem du die Bibliothek pandas verwendest, um Daten zu laden, zu filtern und einfache Berechnungen durchzuführen. 
1. Installiere pandas 
2. Erstelle eine csv-Datei mit Beispieldaten 
3. Lade die Daten in ein DataFrame 
4. Filtere die Daten nach bestimmten Kriterien 
5. Berechne einfache Statistiken (z.B. Durchschnitt, Summe) 
6. Gib die Ergebnisse aus