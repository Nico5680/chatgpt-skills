---
name: preflight-routing
description: Pre-Flight vor jeder Aufgabe. Liest Start.md und AGENTS.md, waehlt anhand von Stichworten passende Dictionaries/Skills und arbeitet danach ohne Unterbrechung weiter. Nutzen bei jedem neuen Auftrag.
---

# Pre-Flight & Routing

## Ablauf
1. `Start.md` lesen, falls vorhanden. Danach ohne Rueckfrage weiterarbeiten.
2. `AGENTS.md` lesen, falls vorhanden. Stichwoerter der Anfrage den Routing-Regeln zuordnen.
3. Zugeordnete Dictionaries/Skills lesen und anwenden.
4. Aufgabe ausfuehren und am Ende kurz melden, was gelesen und geschrieben wurde.

## Regeln
- Existiert eine Datei nicht, kurz erwaehnen und ohne sie weitermachen. Nicht abbrechen.
- Bestehende Dateien nicht ueberschreiben. Aenderungen als neue Datei (Suffix `_neu`) anbieten, ausser der Nutzer sagt ausdruecklich anders.
- Projekte, die in `AGENTS.md` als IMMUTABLE stehen, nie aendern.
- Kurz und ohne Fuellsaetze antworten.
