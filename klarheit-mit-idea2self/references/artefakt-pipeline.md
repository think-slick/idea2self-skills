<artefakt_pipeline>

<sequenz>
Die Artefakte bauen aufeinander auf. Jeder Workflow nutzt die Outputs der vorherigen als Input:

1. Discovery-Interview -> Idee (Kern, Motivation, Kontext)
2. Problem-Statement v0.1 -> Problem, Betroffene, aktuelle Loesung, Nutzenversprechen
3. Persona v0.1 -> Verhalten, Kontext, Ziele, Frustrationen, JTBD, Gains
4. Recherche-Report -> v0.2 (PS + Persona), Recherche-Ergebnisse, Interview-Impulse
5. Experiment-Card v0.1 -> Hypothese, Risikostufe, MVE-Design, Metriken, Entscheidungsschwelle
6. Prototyp-Konzept v0.1 -> Typ, Kernfunktionen, Scope IN/OUT, User Flow
7. Action-Plan + Obstacle-Plan -> 10 Aufgaben/14 Tage, Risiken, WOOP

Pipeline:
  Discovery -> PS v0.1 -> Persona v0.1 -> Recherche (v0.2) -> Experiment -> Prototyp -> Action-Plan
</sequenz>

<kontextweitergabe>
Im asynchronen Skill-Modus (anders als im Workshop):
- Die idea2self-Datei IST der Kontext. Kein manuelles Copy-Paste noetig.
- Vor jedem Workflow: Aktuelle idea2self-Datei lesen.
- Nach jedem Workflow: Neuen Abschnitt in die Datei schreiben.
- Kumulativer Kontext: Ab Workflow 5 enthaelt die Datei umfangreichen Kontext.
</kontextweitergabe>

<versionierung>
- v0.1 = Erstversion aus Workflow-Durchlauf
- v0.2 = Ueberarbeitete Version nach Recherche, Feedback oder Iteration
- Versionsnummer wird im Abschnitts-Header gefuehrt
- Bei Ueberarbeitung: Aenderungen mit Datum kennzeichnen

Versions-Header-Format:
_Version V[X] vom [Datum]_
_Vorgaengerversion: V[X-1] vom [Datum] / Keine - Neuerstellung_
</versionierung>

<dateistruktur>
Die idea2self-Datei hat folgende Struktur (waechst mit jedem Workflow):

```markdown
# Idea2Self: [Kurztitel]
## Idee                    <- Discovery
## Problem-Statement       <- Workflow 2
## Persona                 <- Workflow 3
## Recherche-Report        <- Workflow 4
## Experiment-Card         <- Workflow 5
## Prototyp-Konzept        <- Workflow 6
## Action-Plan             <- Workflow 7
## Offene Punkte           <- Geparkte Gedanken aus allen Workflows
## Changelog               <- Aenderungshistorie
```
</dateistruktur>

<rueckwaerts_updates>
Wenn ein spaeterer Workflow Erkenntnisse liefert, die fruehere Abschnitte betreffen:
1. Den betroffenen Abschnitt identifizieren.
2. Den Nutzer informieren: „Die Recherche zeigt, dass dein Problem-Statement angepasst werden sollte: [konkreter Punkt]."
3. Aenderung vorschlagen mit _(Update aus [Workflow])_ Kennzeichnung.
4. Nur nach Bestaetigung aendern.
5. Im Changelog dokumentieren.
</rueckwaerts_updates>

</artefakt_pipeline>
