# KI-Lernwerkstatt

Offline-first Progressive Web App für BWL, KI und Token-Ökonomie.

## Lokal testen

```bash
python3 -m http.server 4173
```

Danach `http://127.0.0.1:4173/` öffnen. Für Service Worker und Installation muss die App über `localhost` oder HTTPS ausgeliefert werden; ein direktes Öffnen der `index.html` reicht dafür nicht.

## GitHub Pages

Den Inhalt dieses Ordners in ein Repository `ki-lernwerkstatt-pwa` pushen und GitHub Pages aus dem gewünschten Branch bzw. `/root` veröffentlichen. Alle App-Pfade sind relativ und funktionieren dadurch auch unter:

`https://<username>.github.io/ki-lernwerkstatt-pwa/`

## Daten

Lernstand, eigene Karten, Rechnerwerte und Notizen werden ausschließlich in `localStorage` gespeichert. Über den Bereich „Lernstand & Notizen“ kann eine JSON-Sicherung exportiert oder importiert werden.

## Smartphone-Installation

- iPhone/iPad: Seite in Safari öffnen → Teilen → „Zum Home-Bildschirm“ → Hinzufügen.
- Android: Seite in Chrome öffnen → Drei-Punkte-Menü → „Zum Startbildschirm hinzufügen“ bzw. „App installieren“.
- macOS/Windows: Seite in einem Chromium-basierten Browser öffnen → Installationssymbol in der Adressleiste oder Browsermenü → Installieren.
