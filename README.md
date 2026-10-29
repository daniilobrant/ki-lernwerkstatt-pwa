# KI-Lernwerkstatt

Eine kleine Lernwerkstatt für alle, die sich mit KI und betriebswirtschaftlichen Fragen beschäftigen möchten. Die Progressive Web App läuft direkt im Browser und kann auf dem Smartphone oder Computer installiert werden.

**[KI-Lernwerkstatt öffnen](https://daniilobrant-oss.github.io/ki-lernwerkstatt-pwa/)**

## Was bietet die App?

- **Karteikarten:** Zehn vorbefüllte Karten erklären unter anderem LLMs, RAG, Prompt Injection und den EU AI Act. Eigene Fragen und Antworten lassen sich ergänzen.
- **ROI- und Token-Rechner:** Mit eigenen Annahmen zu Nutzung, Modellpreisen und Einführungskosten lassen sich Frontier- und Mini- beziehungsweise lokale Modelle vergleichen. Die angezeigten Preise und der Wechselkurs sind Planungsannahmen.
- **Lernstand und Notizen:** Fortschritt, eigene Karten und Notizen werden lokal gespeichert. Eine JSON-Datei ermöglicht Sicherung und Übertragung auf ein anderes Gerät.

Nach dem ersten Laden stehen die zwischengespeicherten App-Dateien auch offline zur Verfügung. Es gibt keine externen Bibliotheken oder Tracker.

## Lokal testen

```bash
python3 -m http.server 4173
```

Danach `http://127.0.0.1:4173/` öffnen. Für Service Worker und Installation muss die App über `localhost` oder HTTPS ausgeliefert werden; ein direktes Öffnen der `index.html` reicht dafür nicht.

## GitHub Pages

Die App wird aus dem Branch `main` über GitHub Pages veröffentlicht: [Zur Live-App](https://daniilobrant-oss.github.io/ki-lernwerkstatt-pwa/). Die relativen Pfade ermöglichen den Betrieb im Repository-Unterordner.

## Daten

Lernstand, eigene Karten, Rechnerwerte und Notizen werden ausschließlich in `localStorage` gespeichert. Über den Bereich „Lernstand & Notizen“ kann eine JSON-Sicherung exportiert oder importiert werden.

## Smartphone-Installation

- iPhone/iPad: Seite in Safari öffnen → Teilen → „Zum Home-Bildschirm“ → Hinzufügen.
- Android: Seite in Chrome öffnen → Drei-Punkte-Menü → „Zum Startbildschirm hinzufügen“ bzw. „App installieren“.
- macOS/Windows: Seite in einem Chromium-basierten Browser öffnen → Installationssymbol in der Adressleiste oder Browsermenü → Installieren.
