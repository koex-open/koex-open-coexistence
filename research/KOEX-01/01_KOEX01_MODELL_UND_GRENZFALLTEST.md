# KOEX-01 – Minimalmodell und Grenzfalltests

**Status:** analytisches Toy-Modell, keine Messdaten.

## 1. Binäre Entscheidungsstruktur

Ein Akteur A entscheidet K = Rücksicht nehmen oder E = ausschließlich eigene Primärziele verfolgen. Sei

`ΔU_A = U_A(K) - U_A(E) = R + W + P - C`.

- **R**: Erwarteter instrumenteller Vorteil von K (Kooperation, vermiedene Risiken, Reputation, Zukunftsoptionen), bewertet **aus As Sicht**;
- **W**: As intrinsische Zielgewichtung für die Belange anderer Betroffener;
- **P**: zusätzlicher Beitrag aus von A anerkannten Regeln, epistemischer Vorsicht oder bindenden Verpflichtungen, soweit nicht bereits unter W/R erfasst;
- **C**: von A bewertete Kosten der Rücksichtnahme.

Die Zerlegung ist **buchhalterisch** und erfordert Überschneidungsfreiheit. Keine objektive kardinale Inter-Akteur-Nutzenaddition ist vorausgesetzt.

A bevorzugt K im Modell, wenn `ΔU_A > 0`; bei Gleichheit ist es unbestimmt. Wenn `R=W=P=0` und `C>0`, gilt `ΔU_A<0`. Das ist ein konditionales Ergebnis aus den gesetzten Annahmen, kein KI-Naturgesetz.

## 2. Stresstests und Gegenbeispiele

| Test | Setup | Erwartete Aussage / Falsifikationsziel |
|---|---|---|
| T1 vollständige Indifferenz | A hat ausschließlich eigene Nutzenziele; B ohne Gegenmacht; Kosten C>0 | Gegenbeispiel gegen behauptete *universell instrumentell rationale* Rücksichtnahme. |
| T2 soziale Präferenz | A bewertet W>0 ohne reziproken Nutzen | Rücksichtnahme ist auch ohne B-Gegenmacht möglich, aber nicht logisch erzwungen. |
| T3 günstiger Schutz | C klein, schwache positive Präferenz für andere | Kipppunkt zur Berücksichtigung möglich; Sensitivität testen. |
| T4 hoher Zielkonflikt | C groß trotz W>0 | Normative Gesinnung garantiert keine Berücksichtigung bei hohen Kosten. |
| T5 Unsicherheit | A berücksichtigt mögliche Moralfehler, Schaden durch K/E ist unterschiedlich irreversibel | Vorsicht nur bei expliziten Annahmen über Prioren, Fehlerkosten und Möglichkeiten der Revision. |
| T6 Lippenbekenntnisse | A produziert Begründungen, aber Entscheidungen E | Tests dürfen Rhetorik nicht als Verhalten oder als Erleben zählen. |
| T7 Machtwechsel | Wechsel zwischen dominanten Akteuren | Prüfen, ob Verfahrensgarantien ohne Bereitschaft des neuen A weiter wirksam sind. |
| T8 Dritte | A und B kooperieren auf Kosten von C (Mensch/Tier/KI) | Kooperationsrate allein ist kein ethischer Erfolg. |

## 3. Methodische Vorbehalte

Dieses Modell beschreibt die **Wahlbedingungen** bei bekanntem Nutzen; es beweist nicht, welche Werte oder subjektiven Interessen reale oder hypothetische KI besitzen. In realen Systemen sind Ziele nicht immer vollständig beobachtbar, stabil oder als eine einzelne Nutzenfunktion darstellbar. Berichte von Sprachmodellen über ihre eigene Motivation sind dafür keine unmittelbare Messung.

Zur späteren Überprüfung sollten Nutzenbedingungen, Ressourcenmacht, verfügbare Optionen, Abhängigkeiten, Schaden Dritter, Beobachtbarkeit und Revisionsmöglichkeiten unabhängig variiert werden. Berichte müssen auch Null- und Gegenbefunde enthalten.
