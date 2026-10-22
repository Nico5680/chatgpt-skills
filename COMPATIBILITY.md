# COMPATIBILITY - Was laeuft wo?

Grundsatz: Eine `SKILL.md` ist reiner Text mit Anweisungen. Sie funktioniert ueberall dort, wo das Modell die Datei lesen kann. Nur Skripte und Tools haengen an der Umgebung.

| Typ | Chat / Work (Handy) | Codex (CLI/Cloud) |
|---|---|---|
| Reine Text-Skills (nur SKILL.md) | ja, wenn Repo/Datei verfuegbar ist (Anhang, Projekt, verbundener Speicher) | ja |
| Skills mit Skripten (`scripts/*.py`, `.sh`) | nur eingeschraenkt (nur wenn Code-Ausfuehrung im Chat aktiv ist) | ja |
| Skills mit Netzwerk/CLI-Tools | meist nein | ja, je nach Sandbox |
| `agents/openai.yaml` | optional, Wirkung unsicher | ja (Codex liest es) |
| `AGENTS.md` | nicht automatisch, muss genannt oder geladen werden | wird automatisch gelesen |

Hinweis: Das ist mein Kenntnisstand und kann sich bei OpenAI aendern. Die Spalte "Chat / Work" bitte praktisch am Handy testen und hier korrigieren.

## Universell (ueberall nutzbar)
- preflight-routing
- deep-research-log
- weekly-dump-publisher

## Nur Codex - spaeter
(Wird beim ersten Lauf von MASTER_PROMPT.md befuellt.)

## Empfehlung
1. Universelle Skills hier im Repo sammeln und in Chat/Work testen.
2. Codex-lastige Skills getrennt vormerken, nicht mischen.
3. Am PC/Pi Codex mit demselben Repo verbinden. Dann gelten beide Listen.
