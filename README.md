Projektübersicht

Dieses Projekt ist eine einfache Webanwendung, die mit Node.js entwickelt wurde. Die Entwicklungsumgebung ist in einem Docker Dev-Container konfiguriert, um eine konsistente und reproduzierbare Entwicklungsumgebung zu gewährleisten. Diese Anleitung beschreibt, wie das Repository in einem Dev-Container geöffnet und die Anwendung gestartet wird.
Voraussetzungen

Bevor Sie beginnen, stellen Sie sicher, dass die folgenden Softwarekomponenten auf Ihrem Computer installiert sind:

    Docker Desktop (inkl. Docker und Docker Compose)
    Visual Studio Code
    Dev - Containers Extension für Visual Studio Code

Schritte zum Starten der Anwendung
1. Repository klonen

Klonen Sie dieses Repository auf Ihren lokalen Rechner:

sh

git clone https://github.com/giorgio-23/dev-container-modul-169.git
cd dev-container-modul-169

2. Visual Studio Code öffnen

Öffnen Sie Visual Studio Code und laden Sie das geklonte Repository.
3. Dev-Container öffnen

    Öffnen Sie die Kommando-Palette (mit F1 oder Ctrl+Shift+P).
    Geben Sie Dev-Containers: Reopen in Container ein und wählen Sie diesen Befehl aus.

Visual Studio Code wird nun die Docker-Umgebung einrichten und das Projekt im Dev-Container öffnen. Dies kann einige Minuten dauern.
4. Anwendung starten

Sobald der Dev-Container eingerichtet ist, können Sie die Anwendung starten:

    Öffnen Sie ein neues Terminal in Visual Studio Code (Terminal > Neues Terminal).
    Geben Sie den folgenden Befehl ein, um die Anwendung zu starten:

sh

npm start

5. Anwendung im Browser anzeigen

Öffnen Sie Ihren Webbrowser und navigieren Sie zu http://localhost:3000, um die laufende Anwendung zu sehen.
Entwicklungswerkzeuge

Im Dev-Container sind folgende Erweiterungen für Visual Studio Code installiert, um die Entwicklung zu unterstützen:

    ESLint (dbaeumer.vscode-eslint)
    Prettier - Code formatter (esbenp.prettier-vscode)

Diese Erweiterungen helfen, den Code konsistent und fehlerfrei zu halten.
Anpassungen und Erweiterungen

Sie können die Konfiguration des Dev-Containers nach Bedarf anpassen, indem Sie die Dateien devcontainer.json und Dockerfile im Verzeichnis .devcontainer bearbeiten.
