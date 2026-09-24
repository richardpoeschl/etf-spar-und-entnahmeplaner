ETF Spar- & Entnahmeplaner - PWA

Dateien:
- index.html: Anwendung und gesamte Berechnungslogik
- manifest.json: Installationsdaten der PWA
- service-worker.js: Offline-Cache
- icon-192.png und icon-512.png: App-Icons

Installation/Test:
1. Alle Dateien gemeinsam auf einem HTTPS-Webspace ablegen.
2. index.html im Browser aufrufen.
3. Im Browser "App installieren" bzw. "Zum Startbildschirm hinzufügen" wählen.

Wichtig:
Service Worker funktionieren aus Sicherheitsgründen normalerweise über HTTPS oder localhost, nicht beim direkten Öffnen per file://.
Die Eingaben werden ausschließlich lokal im Browser über localStorage gespeichert.
