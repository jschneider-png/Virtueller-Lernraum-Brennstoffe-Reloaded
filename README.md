# Virtueller Lernraum – Brennstoffe

GitHub-Pages-taugliche, rein statische Lernkontrolle für ca. 30–40 Minuten. Die Seite ist bewusst nüchtern gestaltet und enthält keine Lerntexte, sondern nur Aufgaben, Hinweise zur Arbeitsweise und Selbstkontrollen.

## Inhalte

- Brennstoffarten und Zusammensetzung
- Feuerdreieck und Verbrennung
- Heizöl: Rohöl, Raffinerie, Destillation, Flammpunkt, Cloud Point
- Erdgas: Odorierung, Gasgeruch, Energieabrechnung
- Schwefelpfad: Entschwefelung, H₂S, Claus-Anlage, elementarer Schwefel
- Heizwert `Hi` und Brennwert `Hs`
- Rechenaufgaben mit Tabellenbuch/Fachkunde
- Fach-Chat, Transfer- und Entscheidungssituationen
- Differenzierung: Basis → Standard → Profi → Weltklasse/Transfer

## Starten

Einfach `index.html` im Browser öffnen.

## Auf GitHub Pages veröffentlichen

1. Neues GitHub-Repository anlegen.
2. `index.html`, `styles.css`, `app.js` und `README.md` in das Repository laden.
3. In GitHub: **Settings → Pages**.
4. Unter **Build and deployment**: `Deploy from a branch` wählen.
5. Branch `main`, Ordner `/ (root)` auswählen und speichern.
6. Nach kurzer Zeit erscheint die veröffentlichte URL.

## Anpassung

- Arbeitszeit: in `app.js` die Zeile `let seconds=40*60` ändern.
- Texte/Aufgaben: direkt in `index.html` bearbeiten.
- Gestaltung: in `styles.css` über die Variablen am Anfang anpassen.
- Offene Aufgaben werden absichtlich nicht automatisch „inhaltlich benotet“. Die Seite kontrolliert dort Mindestumfang und Pflichtbegriffe; die fachliche Bewertung bleibt bei Lehrkraft/Selbstkontrolle.
- Beim Koks-Heizwert wird absichtlich kein Stoffwert vorgegeben, weil er aus der im Unterricht verwendeten Tabellen-/Fachquelle entnommen werden soll.

## Datenschutz

Keine externen Bibliotheken, kein Tracking, kein Server nötig. Der Button „Zwischenstand speichern“ nutzt nur `localStorage` im jeweiligen Browser.
