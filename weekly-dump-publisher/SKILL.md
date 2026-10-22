---
name: weekly-dump-publisher
description: Sortiert die Ergebnisse der Woche in grosse visuelle Dateien (fuer Google Site) und kleine Logs (bleiben im Drive-Ordner) und erstellt einen Wochen-Index. Nutzen bei "Wochen-Dump", "Weekly Upload".
---

# Woechentlicher Dump

## Sortierregeln
- Gross oder visuell (Diagramme, Grafiken, Videos, lange Berichte): Kandidat fuer Google Site.
- Klein (Research-Logs, Notizen, Zwischenstaende): bleibt in `Research/Logs/`.
- IMMUTABLE-Projekte nie anfassen.

## Ablauf
1. Neue Dateien der letzten 7 Tage auflisten.
2. In "Upload" und "Bleibt in Drive" einteilen.
3. Tabelle zeigen: Datei, Groesse, Ziel.
4. Index `Weekly/YYYY-WW_index.md` mit Titel, Link, Datum erstellen.
5. Upload nur ausfuehren, wenn eine Verbindung zur Google Site besteht. Sonst Upload-Liste als fertige Checkliste ausgeben.
