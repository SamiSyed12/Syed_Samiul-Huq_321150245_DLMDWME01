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