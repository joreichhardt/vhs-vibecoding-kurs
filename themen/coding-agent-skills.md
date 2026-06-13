# Coding-Agent Skills und wiederverwendbare Workflows

## Ziel

Die Teilnehmer verstehen, dass Coding-Agents nicht nur einzelne Prompts ausfuehren. Wiederverwendbare Skills koennen typische Arbeitsweisen als klare, abrufbare Workflows beschreiben.

## Was ist ein Skill?

Ein Skill ist eine gespeicherte Anleitung fuer eine wiederkehrende Aufgabe. Er sagt dem Agenten nicht nur, was er tun soll, sondern auch wie er dabei vorgehen soll.

Beispiele:

- eine Idee gruendlich hinterfragen
- einen Fehler systematisch diagnostizieren
- testgetrieben entwickeln
- Code reviewen
- Architektur verbessern
- ein Projekt in Issues zerlegen
- eine Uebergabe fuer einen anderen Agenten schreiben

## Unterschied zu einem normalen Prompt

Ein Prompt ist ein einzelner Arbeitsauftrag.

Ein Skill ist wiederverwendbar und beschreibt einen Ablauf:

- wann der Skill eingesetzt wird
- welche Schritte der Agent befolgen soll
- welche Fragen er stellen soll
- welche Ergebnisse erwartet werden
- wann die Aufgabe als erledigt gilt

## Beispiele aus der Praxis

Das Repository `mattpocock/skills` zeigt typische Skills fuer echte Softwarearbeit:

- `grill-me`: Idee oder Plan kritisch hinterfragen
- `diagnose`: Fehler reproduzieren, eingrenzen, beheben und absichern
- `tdd`: Red-Green-Refactor als Test-Workflow
- `zoom-out`: Code im groesseren Zusammenhang erklaeren
- `improve-codebase-architecture`: Architekturprobleme finden und verbessern
- `to-issues`: aus einem Plan umsetzbare Issues machen

## Nutzen im Kurs

Skills helfen, wenn ein Projekt groesser wird oder sich Aufgaben wiederholen:

- weniger lange Prompts schreiben
- konsistent arbeiten
- bessere Rueckfragen bekommen
- nicht zu schnell in Code springen
- Tests, Reviews und Diagnose nicht vergessen

## Kursregel

Im Kurs muessen keine eigenen Skills installiert werden. Wichtig ist zuerst das Prinzip: Gute Agent-Arbeit besteht aus wiederholbaren Arbeitsweisen, nicht nur aus spontanen Einzelprompts.

Wer bereits mit Codex, Claude Code oder einem anderen Agenten arbeitet, kann spaeter eigene Skills, Slash-Commands, Projektregeln oder Agent-Anweisungen fuer die eigenen Arbeitsablaeufe anlegen.

## Merksatz

Prompts starten einzelne Aufgaben. Skills machen gute Arbeitsweisen wiederholbar.
