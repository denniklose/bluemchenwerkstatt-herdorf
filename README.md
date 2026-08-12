# Blümchenwerkstatt Herdorf

Öffentliche Sicherung des aktuell veröffentlichten Herdorf-Auftritts.

## Lokal ansehen

```bash
python3 -m http.server 4173
```

Danach im Browser `http://localhost:4173` öffnen. Die Unterseiten werden über Hash-Routen geöffnet, zum Beispiel:

- `/#/blumen-straeusse`
- `/#/restposten`
- `/#/blumenwissen`
- `/#/leistungen`
- `/#/ueber-uns`
- `/#/kontakt`

Die Dateien unter `assets/` sind der veröffentlichte Browser-Build; die Bilddateien unter `images/` sind die dafür verwendeten öffentlichen Stimmungsbilder. Preise, Bestände und Rechtstexte auf der Website sind entsprechend der sichtbaren Hinweise keine Echtzeit- oder finalen Geschäftsdaten.

Der mobile Header-Fix richtet den Hamburger-Button in der rechten Grid-Spalte aus, ohne Logo oder Markennamen zu verschieben.
