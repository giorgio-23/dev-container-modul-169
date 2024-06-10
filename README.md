<h1>Projektübersicht</h1>

<p>Dieses Projekt ist eine einfache Webanwendung, die mit Node.js entwickelt wurde. Die Entwicklungsumgebung ist in einem Docker Dev-Container konfiguriert, um eine konsistente und reproduzierbare Entwicklungsumgebung zu gewährleisten. Diese Anleitung beschreibt, wie das Repository in einem Dev-Container geöffnet und die Anwendung gestartet wird.</p>

<h2>Voraussetzungen</h2>

<p>Bevor Sie beginnen, stellen Sie sicher, dass die folgenden Softwarekomponenten auf Ihrem Computer installiert sind:</p>

<ul>
  <li>Docker Desktop (inkl. Docker und Docker Compose)</li>
  <li>Visual Studio Code</li>
  <li>Dev - Containers Extension für Visual Studio Code</li>
</ul>

<h2>Schritte zum Starten der Anwendung</h2>

<ol>
  <li><strong>Repository klonen</strong></li>
  <p>Klonen Sie dieses Repository auf Ihren lokalen Rechner:</p>
  <pre><code>git clone https://github.com/giorgio-23/dev-container-modul-169.git
cd dev-container-modul-169</code></pre>

  <li><strong>Visual Studio Code öffnen</strong></li>
  <p>Öffnen Sie Visual Studio Code und laden Sie das geklonte Repository.</p>

  <li><strong>Dev-Container öffnen</strong></li>
  <p>Öffnen Sie die Kommando-Palette (mit <kbd>F1</kbd> oder <kbd>Ctrl+Shift+P</kbd>). Geben Sie <code>Dev-Containers: Reopen in Container</code> ein und wählen Sie diesen Befehl aus.</p>
  <p>Visual Studio Code wird nun die Docker-Umgebung einrichten und das Projekt im Dev-Container öffnen. Dies kann einige Minuten dauern.</p>

  <li><strong>Anwendung starten</strong></li>
  <p>Sobald der Dev-Container eingerichtet ist, können Sie die Anwendung starten:</p>
  <p>Öffnen Sie ein neues Terminal in Visual Studio Code (Terminal &gt; Neues Terminal). Geben Sie den folgenden Befehl ein, um die Anwendung zu starten:</p>
  <pre><code>npm start</code></pre>

  <li><strong>Anwendung im Browser anzeigen</strong></li>
  <p>Öffnen Sie Ihren Webbrowser und navigieren Sie zu <a href="http://localhost:3000">http://localhost:3000</a>, um die laufende Anwendung zu sehen.</p>
</ol>

<h2>Entwicklungswerkzeuge</h2>

<p>Im Dev-Container sind folgende Erweiterungen für Visual Studio Code installiert, um die Entwicklung zu unterstützen:</p>

<ul>
  <li>ESLint (<code>dbaeumer.vscode-eslint</code>)</li>
  <li>Prettier - Code formatter (<code>esbenp.prettier-vscode</code>)</li>
</ul>

<p>Diese Erweiterungen helfen, den Code konsistent und fehlerfrei zu halten.</p>

<h2>Anpassungen und Erweiterungen</h2>

<p>Sie können die Konfiguration des Dev-Containers nach Bedarf anpassen, indem Sie die Dateien <code>devcontainer.json</code> und <code>Dockerfile</code> im Verzeichnis <code>.devcontainer</code> bearbeiten.</p>
