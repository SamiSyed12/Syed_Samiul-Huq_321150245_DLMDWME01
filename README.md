# DLMDWME01 Fallstudie: Model Engineering

## Projektziel

Ziel dieses Projekts ist es, ein Prognosemodell zu entwickeln, das Kreditkartenzahlungen automatisch einem Zahlungsdienstleister (PSP) zuweist.  
Das Modell soll dabei zwei Ziele gleichzeitig optimieren:
1. Maximierung der Erfolgswahrscheinlichkeit (`success = 1`)
2. Minimierung der Transaktionskosten gemäß PSP-Gebührenstruktur


## Verwendete Bibliotheken

- `pandas` für Datenmanipulation
- `numpy` für numerische Berechnungen
- `scikit-learn` für Machine Learning Datenaufteilung und Metriken
- `xgboost` für das Prognosemodell
- `matplotlib` für Visualisierungen
- `os` für Dateiorganisation

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