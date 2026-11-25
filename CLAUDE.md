# ZFA Lern-App

Lern-App für Lina (Ausbildung Zahnmedizinische Fachangestellte). Lina ist keine Programmiererin; Patrick (GitHub: over-code) hilft mit. Erklärungen für Lina einfach halten.

## Aufbau

- `index.html` (Startseite + Wirtschaft), `patienten.html` (LF 2 + 3) und `kariestherapie.html` (LF 4 + 5) und `pruefung.html` (Prüfungsstil: Operatoren + Prüfungsfälle), jeweils eine eigenständige Datei (HTML, CSS, JS inline), keine Abhängigkeiten außer Google Fonts, kein Build-Schritt. Alle verlinken aufeinander.
- Muss per Doppelklick und über GitHub Pages laufen. Kein Framework einführen, ohne zu fragen.
- Mobile-first: Lina lernt hauptsächlich am Handy.
- Inhalte liegen als Daten im Script: `TOPICS` (learn/cards/quiz), `CASES`, `RATES`; in `pruefung.html` `OPQ` und `FAELLE`. Neue Themen dort ergänzen, die Views bauen sich daraus.
- Fortschritt in `localStorage` (Präfix `zfaWi_` bzw. `zfaLF_`), immer in try/catch.

## Inhaltliche Regeln

- Sprache: Deutsch, freundlich, duzen.
- Jedes Thema erklärt zuerst das "Warum" (Box `why`), dann Stoff, dann Prüfungsfallen (Box `trap`) und Eselsbrücken (Box `tip`).
- Keine Gedankenstriche (—) in Texten.
- Fachlich korrekt bleiben (BGB-Paragraphen etc. prüfen). Sozialversicherungs- und Steuersätze ändern sich jährlich: im Rechentrainer nur als Beispielwerte kennzeichnen.
- Jede Quizfrage hat eine Erklärung (`w`), warum die Antwort stimmt.

- Prüfungsaufgaben selbst formulieren (Stil der Zahnärztekammer Niedersachsen), keine Originalaufgaben der Kammern kopieren.

## Prüfen

Nach Änderungen das Script auf Syntaxfehler prüfen (z. B. Script-Teil extrahieren und `node --check`).
