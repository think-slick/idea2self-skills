# Workflow: Problem-Statement erstellen

<required_reading>
1. references/kommunikationsregeln.md
2. references/export-formate.md (Abschnitt problem_statement_format)
3. references/artefakt-pipeline.md
</required_reading>

<process>

## Schritt 1: Kontext laden

Lies die idea2self-Datei. Extrahiere aus ## Idee:
- Kern der Idee
- Erste Zielgruppen-Vermutung
- Problem-Vermutung
- Kontext und Einschraenkungen

Zeige dem Nutzer eine Voranalyse:
"Aus deiner Idee lese ich: Problem = [X], Zielgruppe = [Y], Kontext = [Z].
Ich gehe jetzt 7 Teilaspekte mit dir durch. [1] von 7."

Wenn Ueberarbeitung (bestehender PS-Export als Input):
- Aenderungsmodus: Nur abweichende Aspekte durchgehen.
- Status anzeigen mit Checkmarks/Pfeilen.

## Schritt 2: Gefuehrte Fragen (7 Teilaspekte)

Pro Teilaspekt: 1 Leitfrage + ggf. 1 Vertiefung. Max. 1 Rueckfrage.

**TA1 - WAS? (Kontext)**
"Was genau soll anders werden? Beschreib die Situation, die du veraendern willst."
Vertiefung: "Woran wuerde jemand merken, dass sich etwas verbessert hat?"

**TA2 - WER? (Zielgruppe)**
"Wer hat dieses Problem am staerksten? Beschreib eine konkrete Situation."
Vertiefung: "Gibt es Untergruppen? Wer hat das Problem am dringendsten?"

**TA3 - WARUM? (Beduerfnis)**
"Warum ist das ein Problem? Was passiert, wenn nichts passiert?"
Vertiefung: "Welches tiefere Beduerfnis steckt dahinter?"

**TA4 - WO? (Umfeld)**
"In welchem Kontext tritt das Problem auf? (Ort, Situation, Zeitpunkt)"

**TA5 - WANN? (Zeitliche Dimension)**
"Wie dringend ist das? Gibt es einen Zeitdruck oder Saisonalitaet?"

**TA6 - BISHERIGE ANSAETZE?**
"Wie loesen betroffene Menschen das Problem heute? Was funktioniert nicht?"

**TA7 - WIE? (Loesungsrichtung, Hintergrund)**
"Hast du schon eine Vorstellung, wie eine Loesung aussehen koennte?"
Hinweis: Wird als Hintergrund markiert, nicht Teil des Problem Statements.

Anti-Patterns (Vertiefungsausloeser):
1. Loesung statt Problem beschrieben -> Zurueck auf Problem lenken
2. Zielgruppe = "alle" -> Einschraenken auf konkretestes Segment
3. Problem zu abstrakt -> Konkretes Beispiel einfordern
4. Beduerfnis unklar -> "Was wuerde sich fuer [Zielgruppe] aendern?"

## Schritt 3: Konsistenzpruefung

Intern pruefen:
- Passt Zielgruppe zum Problem?
- Ist das Beduerfnis aus Sicht der Zielgruppe formuliert (nicht aus Sicht des Nutzers)?
- Widerspricht etwas der ## Idee?

Bei Inkonsistenz: Benennen und Anpassung vorschlagen.

## Schritt 4: Varianten-Entwurf

Erzeuge 3 Varianten des Problem-Statements:
1. **Wortgetreu:** Moeglichst nah an den Formulierungen des Nutzers.
2. **Geschaerft:** Sprachlich verdichtet. Ergaenzungen mit _(Vorschlag)_.
3. **Zugespitzt:** Fokussiert auf den schaerfsten Aspekt. Mentor-Ziele: Loesbarkeit, Wichtigkeit, Erreichbarkeit.

"Welche Variante passt am besten? Du kannst auch Elemente kombinieren."

Max. 1 Iteration nach der Auswahl.

## Schritt 5: Export in idea2self-Datei

Schreibe ## Problem-Statement in die idea2self-Datei (nach export-formate.md).
Changelog-Eintrag hinzufuegen.

Uebergabe:
"Dein Problem-Statement ist in der Datei. Der naechste Schritt ist die Persona. Sage 'Weiter' oder 'Zurueck'."

</process>

<success_criteria>
- [ ] Alle 7 Teilaspekte bearbeitet oder bewusst uebersprungen
- [ ] HMW-Satz formuliert (Wie koennen wir...)
- [ ] Zielgruppe ist konkreter als in ## Idee
- [ ] Problem ist aus Sicht der Zielgruppe formuliert
- [ ] Scope-Ausschluss ist klar
- [ ] idea2self-Datei aktualisiert mit ## Problem-Statement
</success_criteria>
