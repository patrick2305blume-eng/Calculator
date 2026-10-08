# Calculator
Calculator

CGM-Rechner
Statische Webseite: PDF/CSV/TXT mit CGM-Rohdaten hochladen, Kennzahlen berechnen (Mittelwert, SD, CV, GMI, Time in Range). Alles läuft lokal im Browser, keine Daten verlassen das Gerät.
Berechnungen
GMI (%) = 3,31 + 0,02392 × Mittelwert (mg/dl)
CV (%) = SD / Mittelwert × 100 (Ziel ≤ 36 %)
Bereiche: <54, 54–69, Zielbereich (Standard 70–180), 181–250, >250 mg/dl
mmol/l werden mit Faktor 18,016 umgerechnet
Nutzung
index.html im Browser öffnen oder per GitHub Pages veröffentlichen
(Settings → Pages → Branch main, Ordner /root).
Einschränkungen
Der PDF-Parser sucht Zeilen mit Datum, Uhrzeit und Wert. Berichte, die nur Zusammenfassungen/AGP-Grafiken enthalten, liefern keine Rohdaten. Parser pro Hersteller anpassen (RE und parse() in index.html).
Kein Medizinprodukt, keine medizinische Beratung.
