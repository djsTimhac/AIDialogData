# AIDialogData

KI-Dialog-Trainingsdaten: Die KI lernt, wann sie nachdenken muss und wann nicht.

- 22 Sprachen, je Datei 1000 Zeilen (+ Header)
- Spalten: `id,user,thinking,ai`
- `thinking` ist leer bei Smalltalk (Begruessung, Dank) und gefuellt bei
  Fakten, Rechnen, Erklaerungen, Vergleichen und Entscheidungen.
- Alle Fakten geprueft (Hauptstaedte, Geschichte, Mathe nachgerechnet).

Dateien: `dialog_allgemein_1000_<sprache>.csv`
(de, en, fr, es, it, tr, pt, nl, pl, ru, ar, zh, ja, uk, sv, ro, ko, hi, el, cs, hu, id)
