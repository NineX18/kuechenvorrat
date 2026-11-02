# Küchenvorrat für iPad (GitHub Pages)

Diese Dateien sind eine statische Web-App. GitHub Pages kann sie direkt aus dem Repository bereitstellen.

## Auf GitHub Pages veröffentlichen

1. Auf GitHub ein neues Repository erstellen, zum Beispiel `kuechenvorrat`.
2. Die Dateien aus diesem Paket in das Hauptverzeichnis des Repositorys hochladen: `index.html`, `vorrat.html`, `manifest.webmanifest`, `service-worker.js` und `icon.svg`.
3. In den Repository-Einstellungen unter **Pages** die Veröffentlichung von **Deploy from a branch** aktivieren und den Branch `main` sowie den Ordner `/(root)` auswählen.
4. Warten, bis GitHub Pages die Adresse anzeigt. Die App startet direkt unter dieser Adresse.
5. Diese Adresse auf dem iPad in Safari öffnen. Über **Teilen → Zum Home-Bildschirm** lässt sie sich wie eine App ablegen.

## Daten

Die App speichert den Vorrat lokal im Browser auf dem Gerät. Die Bestandsdaten werden nicht an GitHub übertragen und synchronisieren sich nicht automatisch mit anderen Geräten. Löschen der Safari-Websitedaten kann auch den gespeicherten Bestand entfernen.
