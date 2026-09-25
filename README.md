# AIDialogData

KI-Dialog-Trainingsdaten: Die KI lernt, wann sie nachdenken muss und wann nicht.

- 22 Sprachen, je Datei 1000 Zeilen (+ Header)
- Spalten: `id,user,thinking,ai`
- `thinking` ist leer bei Smalltalk (Begruessung, Dank) und gefuellt bei
  Fakten, Rechnen, Erklaerungen, Vergleichen und Entscheidungen.
- Alle Fakten geprueft (Hauptstaedte, Geschichte, Mathe nachgerechnet).

Dateien: `dialog_allgemein_1000_<sprache>.csv`
(de, en, fr, es, it, tr, pt, nl, pl, ru, ar, zh, ja, uk, sv, ro, ko, hi, el, cs, hu, id)

## Reine Texte (Faktenwissen)

- 22 Sprachen, je Datei 1000 Zeilen (+ Header)
- Spalten: `id,text`
- Reine Fakten-Texte ohne Dialog-Struktur: Hauptstaedte, Geschichte,
  Wissenschaft, Mathe, Alltag, Definitionen.
- Basis sind die geprueften Antworten der Dialog-Dateien plus
  Umformulierungen (Fakt:/Wusstest du schon?/Merke dir: ...).
- Dateien: `text_1000_<sprache>.csv` (gleiche Sprachen wie oben)

## Aufsaetze (Schreiben, Grammatik, Rechtschreibung)

- 22 Sprachen, je Datei 14-35 lange Texte (+ Header)
- Spalten: `id,title,text`
- Zusammenhaengende Sachtexte (200-400 Woerter) aus den geprueften Fakten:
  Hauptstaedte, Laender, Geschichte, Natur/Technik, Rechnen, Alltagstipps,
  Vergleiche und Begriffe. Mit Einleitung, Ueberleitungen und Schluss.
- Dateien: `aufsatz_<sprache>.csv` (gleiche Sprachen wie oben)
