# SkyScope Radar – GitHub Pages

Statische Browser-Anwendung, mit Karte (OpenFreeMap) und Demo-Flugzeugen.

## Veröffentlichung
1. Neues **öffentliches** Repository `skyscope-radar` auf GitHub erstellen, optional `Add a README` wählen.
2. Im Repository **Add file → Upload files** und `index.html` sowie `.nojekyll` aus diesem Ordner hochladen, **Commit changes**. (Falls versteckte Dateien nicht gewählt werden können, genügt `index.html`.)
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. Nach erfolgreichem Deployment `https://kuhkuma.github.io/skyscope-radar/` direkt im Browser öffnen.
5. **Mein Standort** antippen und Standortberechtigung erteilen.

## Hinweise
- Die Webseite ist öffentlich. Standortkoordinaten werden nach Interaktion lokal genutzt und für Karten-/Flugzeugabfragen an jeweilige Dienste übermittelt.
- Demo-Modus läuft ohne Live-API. Live-Flugdaten benötigen eine funktionierende OpenSky-Anbindung bzw. einen sicheren Proxy; GitHub Pages ist nur statisches Hosting.
- Keine API-Schlüssel oder Tokens in die öffentlich verfügbaren Dateien schreiben.
- Die Karte lädt externe Ressourcen (MapLibre via unpkg, Karte via OpenFreeMap).
- Der Live-Modus ist nicht Ende-zu-Ende getestet.