# LB 324

## Aufgabe 2 Wie installiert man 'pre-commit'
1. Als erstes braucht man Python auf dem Rechner. Python kann man auf der Webseite https://www.python.org/downloads/ herunterladen
2. Anschliessend braucht man ein Terminal, entweder der Command Prompt von Windows, GitBash oder ein Terminal von Visual Studio
3. Um pre-commit zu installieren braucht man den command line: ```pip install pre-commit```
4. Anschliessend muss man 'pre-commit' im Repository initialisieren mit ```pre-commit install``` mit diesem CMD wird gleichzeitig ein '.pre-commit-config.yaml' Datei erstell
   Im Falle, dass dies nicht passiert, muss man von Hand ein '.pre-commit-config.yaml' Datei erstellen
5. Im '.pre-commit-config.yaml' Datei muss man dann Hooks einschreiben
6. Zum Schluss kann muss man den pre-commit testen indem man irgendwas pushed mit ```git push "was man pushen möchte"```

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
1. Bevor man irgendwas machen kann, braucht man eine lokale `.env` Datei im lokalen Ordner zu erstellen und muss diese pushen
2. Danach erstellt man ein Azure App Service
3. Im Deployment Center der App Service muss man Azure mit dem GitHub Repositorie verbinden
4. Anschliessend muss man in der Konfiguration eine neue Application Setting erstellen mit dem namen PASSWORD und mit dem Wert gleich gesetzt wie der im .env Datei gespeicherten Passwort.
5. Sobald dieser gespeichert ist, kann man sich auf der Webseite einloggen

## URL für die Applikation
blattmannpatricklb-324.azurewebsites.net
