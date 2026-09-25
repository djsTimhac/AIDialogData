# AIDialogData

KI-Dialog-Trainingsdaten: Die KI lernt, wann sie nachdenken muss und wann nicht.

- 22 Sprachen, je Datei 1000 Zeilen (+ Header)
- Spalten: `id,user,thinking,ai`
- `thinking` ist leer bei Smalltalk (Begruessung, Dank) und gefuellt bei
  Fakten, Rechnen, Erklaerungen, Vergleichen und Entscheidungen.
- Alle Fakten geprueft (Hauptstaedte, Geschichte, Mathe nachgerechnet).

Dateien: `dialog_allgemein_1000_<sprache>.csv`
(de, en, fr, es, it, tr, pt, nl, pl, ru, ar, zh, ja, uk, sv, ro, ko, hi, el, cs, hu, id)

## Monologe (Selbstgespraeche beim Denken)

- 22 Sprachen, je Datei 1000 Zeilen (+ Header)
- Spalten: `id,user,monologue,ai`
- `monologue` ist das innere Selbstgespraech der KI zwischen User-Frage und
  Antwort: Einstieg + Ueberlegung + Fazit/Probe + Abschluss.
- Bei Smalltalk bleibt `monologue` leer (kein Selbstgespraech noetig).
- Dateien: `monolog_1000_<sprache>.csv` (gleiche Sprachen wie oben)
