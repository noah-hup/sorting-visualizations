# sorting-visualizations

Interaktive Animationen von Sortier- und Suchalgorithmen als statische Webseiten, gehostet über GitHub Pages. Gedacht zum Einbetten in Notion (Embed-Block) oder anderswo per iframe.

## Live-Seiten

- Übersicht: https://noah-hup.github.io/sorting-visualizations/
- Binary Search: https://noah-hup.github.io/sorting-visualizations/binary-search/

## In Notion einbetten

1. Seite in Notion öffnen, `/embed` eingeben.
2. Die URL der gewünschten Animation einfügen (z. B. die Binary-Search-URL oben).
3. Größe des Embed-Blocks per Ziehen anpassen.

## Neue Algorithmen hinzufügen

Für jeden Algorithmus einen eigenen Ordner mit eigener `index.html` anlegen (siehe `binary-search/`), dann in der Wurzel-`index.html` verlinken.

## Lokal ansehen

Kein Build-Schritt nötig – einfach die `index.html`-Dateien im Browser öffnen, oder lokal servieren:

```bash
python3 -m http.server 8000
```
