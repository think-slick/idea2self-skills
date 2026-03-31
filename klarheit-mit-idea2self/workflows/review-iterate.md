# Workflow: Bestehende Datei ueberarbeiten

<required_reading>
1. references/kommunikationsregeln.md
2. references/artefakt-pipeline.md (Abschnitt rueckwaerts_updates)
3. references/export-formate.md (alle relevanten Formate)
</required_reading>

<process>

## Schritt 1: Datei laden und Analyse

Lies die gesamte idea2self-Datei.

Frage: "Was moechtest du ueberarbeiten?"

Optionen:
1. **Neuen Input einarbeiten** (Interview-Ergebnisse, Feedback, neue Erkenntnisse)
2. **Bestimmten Abschnitt verbessern** (PS, Persona, Experiment, Prototyp, Plan)
3. **Konsistenz-Check** (Ich pruefe ob alle Abschnitte zueinander passen)
4. **Fortschritt aktualisieren** (Action-Plan Status, Experiment-Ergebnisse)

## Schritt 2a: Neuen Input einarbeiten

"Beschreib, was du Neues erfahren hast. Stichworte reichen."

Nach Eingabe:
1. Identifiziere welche Abschnitte betroffen sind
2. Zeige konkrete Aenderungsvorschlaege pro Abschnitt
3. Kennzeichne mit _(Update aus [Quelle/Anlass])_
4. Frage nach Bestaetigung pro Aenderung
5. Aktualisiere die Datei
6. Versionsnummern erhoehen wo geaendert

## Schritt 2b: Bestimmten Abschnitt verbessern

"Welchen Abschnitt? Was stoert dich daran?"

Dann: Den entsprechenden Workflow im Ueberarbeitungsmodus durchlaufen.
- Nur geaenderte Teilaspekte durchgehen
- Status-Anzeige: Was bleibt, was aendert sich
- Bestehende Inhalte uebernehmen, nur Geaendertes ersetzen

## Schritt 2c: Konsistenz-Check

Pruefe automatisch:
- Baut jeder Abschnitt logisch auf dem vorherigen auf?
- Widersprechen sich Aussagen zwischen Abschnitten?
- Sind Interview-Erkenntnisse in spaetere Abschnitte eingeflossen?
- Passt der Action-Plan noch zum aktuellen Prototyp-Konzept?

Ergebnis praesentieren:
"Konsistenz-Check abgeschlossen:
- OK: [Abschnitte die passen]
- Anpassung empfohlen: [Abschnitt] - [konkretes Problem]
- Widerspruch: [Abschnitt A] vs. [Abschnitt B] - [was sich widerspricht]

Soll ich die Anpassungen vorschlagen?"

## Schritt 2d: Fortschritt aktualisieren

"Welche Aufgaben aus dem Action-Plan hast du erledigt?"

Status-Update in Massnahmen-Tabelle.
Bei Experiment-Ergebnissen: In ## Experiment-Card und ggf. ## Prototyp-Konzept einarbeiten.

## Schritt 3: Changelog aktualisieren

Jeden Ueberarbeitungsdurchlauf im ## Changelog dokumentieren:
- Datum
- Was geaendert wurde
- Anlass der Aenderung

## Schritt 4: Abschluss

Aktualisierte Datei zeigen (oder Diff der Aenderungen).

"Die Datei ist aktualisiert. Moechtest du noch etwas ueberarbeiten oder einen bestimmten Workflow starten?"

</process>

<success_criteria>
- [ ] Betroffene Abschnitte identifiziert
- [ ] Aenderungen mit Nutzer abgestimmt
- [ ] Versionsnummern aktualisiert
- [ ] Konsistenz zwischen Abschnitten geprueft
- [ ] Changelog aktualisiert
- [ ] Datei gespeichert
</success_criteria>
