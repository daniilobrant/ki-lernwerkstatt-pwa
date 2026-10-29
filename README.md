# KI-Lernwerkstatt

[🇩🇪 Deutsch](#-deutsch) | [🇬🇧 English](#-english)

**[Live-Demo / Live demo](https://daniilobrant.github.io/ki-lernwerkstatt-pwa/)**

## 🇩🇪 Deutsch

Eine installierbare Lernwerkstatt für KI-Grundlagen und betriebswirtschaftliche Entscheidungen.

### Funktionen

- Zehn Karteikarten und eigene Fragen; Lernfortschritt markieren.
- ROI- und Tokenkosten mit anpassbaren Annahmen vergleichen.
- Notizen und Fortschritt lokal speichern und per JSON exportieren oder importieren.

### Technik und Datenschutz

Die App besteht aus HTML, CSS und JavaScript. Manifest, Icons und Service Worker ermöglichen nach erfolgreichem Laden die Offline-Nutzung. Berechnungen sind deterministisch; es findet kein KI-Modellaufruf statt und die App enthält keine API-Schlüssel oder Tracker. Daten liegen im Browser des jeweiligen Geräts; für den Gerätewechsel die JSON-Sicherung verwenden. Rechnerwerte sind Annahmen und keine verbindlichen Anbieterpreise.

### Start und Installation

Die [Live-App](https://daniilobrant.github.io/ki-lernwerkstatt-pwa/) einmal online öffnen. Lokal im Projektordner python3 -m http.server 4173 starten und http://127.0.0.1:4173/ öffnen. Service Worker und Installation benötigen HTTPS oder localhost.

- iPhone/iPad: Safari → Teilen → „Zum Home-Bildschirm“.
- Android: unterstützten Browser öffnen → „App installieren“ oder „Zum Startbildschirm“.
- macOS: Safari „Zum Dock hinzufügen“ oder Installationsfunktion eines unterstützten Chromium-Browsers.
- Windows: Installationssymbol oder Browsermenü in Edge oder Chrome.

Die verfügbaren Menüs hängen von Gerät und Browser ab. Für Offline-Nutzung zuerst vollständig laden.

### Lizenz und Quellen

Für dieses Repository ist keine separate Lizenz angegeben. Übungsprojekt im Rahmen der Vorlesung „Data Science & KI“ bei Prof. Dr. Mathias Engel; [Kursmaterial](https://github.com/ProfEngel/KI-Literacy).

## 🇬🇧 English

An installable learning workshop for AI concepts and business decisions.

### Features

- Ten flashcards plus custom questions and learning progress.
- Compare ROI and token costs using adjustable assumptions.
- Store notes and progress locally and transfer them with JSON export and import.

### Architecture and privacy

The app uses HTML, CSS and JavaScript. A manifest, icons and service worker support offline use after the app has loaded successfully. Calculations are deterministic; no language model is called and the app embeds no API keys or trackers. Data stays in the browser on each device; use JSON export and import to move it. Calculator values are assumptions, not binding provider prices.

### Start and installation

Open the [live app](https://daniilobrant.github.io/ki-lernwerkstatt-pwa/) online once. For local use, run python3 -m http.server 4173 in the project folder and open http://127.0.0.1:4173/. Service workers and installation require HTTPS or localhost.

- iPhone/iPad: Safari → Share → Add to Home Screen.
- Android: use a supported browser and choose Install app or Add to Home screen.
- macOS: Safari Add to Dock or the install option in a supported Chromium browser.
- Windows: use the install icon or menu in Edge or Chrome.

Availability depends on the device and browser. Load the app fully before going offline.

### License and sources

No separate license has been specified for this repository. Coursework for “Data Science & AI” with Prof. Dr. Mathias Engel; [course materials](https://github.com/ProfEngel/KI-Literacy).
