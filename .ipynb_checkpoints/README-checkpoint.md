# DLMDWME01 Fallstudie: Model Engineering

## Projektziel

Ziel dieses Projekts ist es, ein Prognosemodell zu entwickeln, das Kreditkartenzahlungen automatisch einem Zahlungsdienstleister (PSP) zuweist.  
Das Modell soll dabei zwei Ziele gleichzeitig optimieren:
1. Maximierung der Erfolgswahrscheinlichkeit (`success = 1`)
2. Minimierung der Transaktionskosten gemäß PSP-Gebührenstruktur


 Woche 1: Daten verstehen und erstes Modell

Tag 1–2: Projektstruktur & Datenexploration
Git-/Ordnerstruktur anlegen (CRISP-DM oder MS-Style)
Excel-Daten laden, Spalten verstehen
Datenqualität prüfen: fehlende Werte, Duplikate, Datentypen
Zahlungsversuche identifizieren (zeitnah, gleicher Betrag, gleiches Land)
🧠 Ziel: Datensatz vollständig verstanden, Datenprobleme erkannt

Tag 3–4: Explorative Analyse & Visualisierungen
Erfolgsquoten nach PSP, Land, Betrag, 3D-secured etc. visualisieren
Transaktionskosten nach PSP darstellen
erste Hypothesen formulieren (z.B. „3D secured erhöht Erfolgsrate“)
📊 Ziel: Businessverständnis durch EDA aufbereitet

Tag 5–6: Baseline-Modell
Einfache Klassifikation z. B. nach Mehrheit der erfolgreichen PSPs
Oder Entscheidungsregel: „Wähle PSP mit niedrigsten Fehlkosten“
Modell aufteilen: Training/Test
⚙️ Ziel: Vergleichspunkt für späteres Modell

Tag 7: Fortgeschrittenes Modell (1. Version)
z. B. Random Forest, XGBoost oder logistische Regression
Ziel: Wahrscheinlichkeit für „success = 1“ vorhersagen
Trainingsdaten ggf. anpassen (z. B. gewichtete Kostenfunktion)
🤖 Ziel: Modell steht technisch und läuft auf echten Daten

🔷 Woche 2: Optimierung, Interpretation & Dokumentation

Tag 8–9: Modell bewerten & verbessern
Feature Importance analysieren
Metriken vergleichen: Accuracy, Precision, Recall, Cost
Hyperparameter-Tuning (GridSearch, falls Zeit)
🧪 Ziel: Gutes Modell mit nachvollziehbaren Entscheidungen

Tag 10–11: Fehleranalyse & Interpretation
Fehler nach PSP, Land, Betrag etc. analysieren
Missklassifikationen und Kostenfolgen beleuchten
Welche Features beeinflussen das Ergebnis am stärksten?
🧠 Ziel: Ergebnisinterpretation für Fachbereich

Tag 12: Anwendungskonzept & GUI-Idee
Wie kann das Modell genutzt werden (z. B. API, Batch-Prozess)?
Skizze oder Beschreibung einer GUI zur PSP-Auswahl
Empfehlungen zur Integration in die Fachabteilung
🧩 Ziel: Praktische Anwendung klar und durchdacht

Tag 13: Finales Dokument schreiben
CRISP-DM/Projektstruktur beschreiben
Analyse, Modell, Visualisierungen, Interpretation einbauen
Alles verständlich & businessgerecht formulieren
📄 Ziel: Rohfassung des Berichts steht

Tag 14: Korrektur & Abgabevorbereitung
Bericht Korrekturlesen
Code/Notebook sauber dokumentieren
Ein PDF für Turnitin erzeugen inkl. Screenshots & Ergebnisse
✅ Ziel: Fertiges, prüfbares Endprodukt mit Dokumentation