<export_formate>

<content_note>
Alle Markdown-Blöcke unten sind **Output-Templates** – sie zeigen das Format, das in die idea2self-Datei geschrieben wird. Die Markdown-Headings darin sind gewollter Output, keine Strukturelemente dieser Referenzdatei.
</content_note>

<toc>
Enthaltene Templates:
1. idee_format – Discovery-Ergebnis
2. problem_statement_format – Problem + Zielgruppe
3. persona_format – Verhaltensbasierte Persona
4. recherche_report_format – Recherche-Report + Interview-Vorbereitung
5. experiment_card_format – Hypothesen + MVE-Design
6. prototyp_konzept_format – Lösungsideen + Konzept
7. action_plan_format – Aufgaben + WOOP
</toc>

<grundregel>
Alle Artefakte werden als Markdown-Abschnitte (`##` Heading) in die idea2self-Datei geschrieben. Ein Artefakt = ein Abschnitt. Die Datei wächst mit jedem Workflow.
</grundregel>

<idee_format>
```markdown
## Idee

_Erstellt am [Datum]_

### Kern
[1–3 Sätze: Was ist die Idee?]

### Problem
[Was ist der Schmerz/das Bedürfnis? Wie wird es heute gelöst?]

### Zielgruppe (grob)
[Wer hat das Problem? Erste Beschreibung.]

### Lösungsrichtung
[Erste Idee für einen Ansatz.]

### Differenzierung
[Was unterscheidet diesen Ansatz?]

### Persönliche Passung
- **Warum ich:** [Motivation, Fähigkeiten, Zugang]
- **Zeitbudget:** [Stunden/Woche]
- **Ambition:** [Hobby / Nebeneinkommen / Hauptberuf]

### Scope – Was bewusst NICHT
[Was wird nicht adressiert]

### Offene Fragen
- [ ] [Ungeklärte Punkte]
```
</idee_format>

<problem_statement_format>
```markdown
## Problem-Statement

> **„Wie können wir [Kontext] für [Zielgruppe] neu gestalten, damit [Bedürfnis] befriedigt wird – unter Berücksichtigung von [Einschränkungen]."**

_Version [V1/V2] vom [Datum]_

### Kontext – Was wird neu gestaltet?
[Zusammenfassung aus WAS?, WO?, WANN?, BISHERIGE ANSÄTZE?]

### Zielgruppe – Für wen?
[Zusammenfassung aus WER?]

### Bedürfnis – Welches Bedürfnis?
[Zusammenfassung aus WAS?, WARUM?, BISHERIGE ANSÄTZE?]

### Einschränkungen – Was muss berücksichtigt werden?
[Zusammenfassung aus WANN?, WO?, BISHERIGE ANSÄTZE?]

### Lösungsrichtung _(Hintergrund)_
[Zusammenfassung aus WIE? – nicht Teil des Problem Statements]

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</problem_statement_format>

<persona_format>
```markdown
## Zielgruppen-Persona

_Version [V1/V2] vom [Datum]_

### Persona-Profil

| Merkmal | Ausprägung |
|---------|-----------|
| Name | [Name] |
| Geschlecht | [Geschlecht] |
| Alter | [Alter] |
| Wohnort & Wohnsituation | [Beschreibung] |
| Familienstand | [Beschreibung] |
| Bildungsniveau | [Beschreibung] |
| Werte & Einstellungen | [Wert 1], [Wert 2], [Wert 3] |
| Wichtigster Glaubenssatz | [Glaubenssatz] |
| Verhaltensweisen | [Verhalten 1], [Verhalten 2], [Verhalten 3] |
| Eigenschaften & Widersprüche | [Eigenschaft 1], [Eigenschaft 2], [Eigenschaft 3] |
| Äußerliche Erkennungsmerkmale | [Merkmal 1], [Merkmal 2], [Merkmal 3] |

### Aufgaben (JTBD)
- **[JTBD-Frage 1]:** [Hypothesen-Antwort]
- **[JTBD-Frage 2]:** [Hypothesen-Antwort]
- **[JTBD-Frage 3]:** [Hypothesen-Antwort]

### Gewinne (Gains)
- **[Gains-Frage 1]:** [Hypothesen-Antwort]
- **[Gains-Frage 2]:** [Hypothesen-Antwort]
- **[Gains-Frage 3]:** [Hypothesen-Antwort]

### Kontext
**Lebenswelt:** [Zusammenfassung]
**Psychografie & Verhalten:** [Zusammenfassung]
**Problemverständnis:** _(Aus Problem-Statement übernommen)_

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</persona_format>

<recherche_report_format>
```markdown
## Recherche-Report

_Version V1 vom [Datum]_
_Stadt für Interviews: [Stadt]_

### Auf einen Blick
- **Problem:** [Wichtigste Erkenntnis, 1–2 Sätze]
- **Zielgruppe:** [Wichtigste Erkenntnis, 1–2 Sätze]

### Problem-Recherche
| Frage | Ergebnis _(Recherche)_ | Einfluss auf PS | Konkreter Vorschlag |
|-------|----------------------|-----------------|-------------------|
| [Frage 1] | [Ergebnis] | [Einfluss] | [Vorschlag] |
| [Frage 2] | [Ergebnis] | [Einfluss] | [Vorschlag] |
| [Frage 3] | [Ergebnis] | [Einfluss] | [Vorschlag] |

### Zielgruppen-Recherche
| Frage | Ergebnis _(Recherche)_ | Einfluss auf Persona | Konkreter Vorschlag |
|-------|----------------------|--------------------|-------------------|
| [Frage 1] | [Ergebnis] | [Einfluss] | [Vorschlag] |
| [Frage 2] | [Ergebnis] | [Einfluss] | [Vorschlag] |
| [Frage 3] | [Ergebnis] | [Einfluss] | [Vorschlag] |

### Interview-Vorbereitung
- **Physische Orte:** [Wo in [Stadt] die Zielgruppe anzutreffen ist]
- **Digitale Orte:** [Foren, Gruppen, Plattformen]
- **Proxy-Gruppen:** [Alternative befragbare Gruppen]
- **Erkennungsmerkmale:** [Woran man die Zielgruppe erkennt]
- **Ansprache-Strategie:** [Wie ansprechen]

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</recherche_format>

<experiment_card_format>
```markdown
## Experiment-Card

_Version [V1/V2] vom [Datum]_

### Hypothesen-Tabelle

| # | Hypothese | Risikostufe | Evidenz-Stufe aktuell |
|---|-----------|------------|---------------------|
| H1 | [Hypothese] | [hoch/mittel/niedrig] | [schwach/mittel/stark] |
| H2 | [Hypothese] | [hoch/mittel/niedrig] | [schwach/mittel/stark] |
| H3 | [Hypothese] | [hoch/mittel/niedrig] | [schwach/mittel/stark] |

### Primäre Hypothese (höchstes Risiko)
**H[X]:** [Hypothese ausformuliert]

### Experiment-Design (MVE)
- **Typ:** [Interview / Landing Page / Smoke Test / Concierge / etc.]
- **Zielgruppe:** [Wer wird befragt/getestet]
- **Sample-Größe:** [Minimum]
- **Dauer:** [Zeitrahmen]
- **Ablauf:** [Konkreter Ablauf in 3–5 Schritten]

### Metriken & Entscheidungsschwelle
| Metrik | Messmethode | Schwelle für „bestätigt" | Schwelle für „widerlegt" |
|--------|-----------|------------------------|------------------------|
| [Metrik 1] | [Wie messen] | [Wert] | [Wert] |

### Interview-Leitfaden (falls Interview-basiert)
**Einstieg:** [Gesprächseröffnung, 1–2 Sätze]
**Kernfragen:**
1. [Offene Frage zu Verhalten/Situation]
2. [Offene Frage zu Problem/Bedürfnis]
3. [Offene Frage zu bisherigen Lösungen]
4. [Offene Frage zu Zahlungsbereitschaft/Aufwand]
5. [Abschlussfrage]

**Regeln:** Keine Suggestivfragen. Keine Ja/Nein-Fragen. Verhalten fragen, nicht Meinungen.

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</experiment_card_format>

<prototyp_konzept_format>
```markdown
## Prototyp-Konzept

_Version [V1/V2] vom [Datum]_

### Interview-Feedback-Synthese
[Was haben die Interviews bestätigt? Was infrage gestellt? Was Neues ergeben?]

### Lösungsideen (Top 3)

| # | Idee | Kurzbeschreibung | Passung zur Persona | Machbarkeit |
|---|------|-----------------|-------------------|-------------|
| 1 | [Titel] | [Beschreibung] | [hoch/mittel] | [hoch/mittel] |
| 2 | [Titel] | [Beschreibung] | [hoch/mittel] | [hoch/mittel] |
| 3 | [Titel] | [Beschreibung] | [hoch/mittel] | [hoch/mittel] |

### Gewähltes Konzept
**Idee:** [Titel]
**Prototyp-Typ:** [Konzept / Landing Page / Mockup / Concierge / etc.]

### Scope
**IN:** [Was das Konzept beinhaltet]
**OUT:** [Was bewusst NICHT enthalten ist]

### Kernfunktionalitäten
1. [Funktion 1 – was sie für die Zielgruppe tut]
2. [Funktion 2]
3. [Funktion 3]

### User Flow
[Schritt-für-Schritt: Was passiert aus Sicht der Zielgruppe]

### Technische Umsetzung _(Konzept)_
[Grober Ansatz – welche Tools, Plattformen, Formate. Kein Bau.]

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</prototyp_konzept_format>

<action_plan_format>
```markdown
## Action-Plan

_Version V1 vom [Datum]_

### Umsetzungsziel (14 Tage)
[1 Satz: Was in 14 Tagen erreicht sein soll]

### Massnahmen-Katalog

| # | Aufgabe | Priorität | Deadline | Abhängigkeit | Status |
|---|---------|----------|----------|-------------|--------|
| 1 | [Aufgabe] | [P0/P1/P2] | [Tag X] | [—/Aufgabe Y] | Offen |
| ... | ... | ... | ... | ... | ... |
| 10 | [Aufgabe] | [P0/P1/P2] | [Tag X] | [—/Aufgabe Y] | Offen |

### Risiken & Gegenmassnahmen

| Risiko | Wahrscheinlichkeit | Gegenmassnahme |
|--------|-------------------|---------------|
| [Externes Risiko] | [hoch/mittel/niedrig] | [Konkrete Handlung] |

### Persönlicher Obstacle-Plan (WOOP)

**Wish:** [Was in 14 Tagen erreicht sein soll]
**Outcome:** [Bestes realistisches Ergebnis]
**Obstacle:** [Größtes inneres Hindernis]
**Plan:**

| Wenn... | Dann werde ich... |
|---------|-------------------|
| [Hindernis 1 auftritt] | [Konkrete Handlung] |
| [Hindernis 2 auftritt] | [Konkrete Handlung] |
| [Hindernis 3 auftritt] | [Konkrete Handlung] |

**Stärke für die schwierigste Aufgabe:** [Welche persönliche Stärke hilft am meisten]

### Nächster Kontrollpunkt
[Wann, wie, wer überprüft den Fortschritt?]

### Offene Punkte
- [ ] [Nur wenn geparkte Gedanken vorhanden]
```
</action_plan_format>

</export_formate>
