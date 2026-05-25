# TODO — Boilerplate-Checkliste

TODOs die nicht im kompilierten PDF sichtbar sind (Konfiguration, Kommentare, Metadaten).
Alle inhaltlichen TODOs im Dokument selbst stehen als `\todo{}` im jeweiligen `.tex`-File.

---

## Vor dem Schreiben

- [ ] **`preamble.sty`** — `pdftitle` ausfüllen (aktuell leer)
- [ ] **`preamble.sty`** — `pdfsubject` ausfüllen (aktuell leer)
- [ ] **`preamble.sty`** — `pdfkeywords` ausfüllen (aktuell leer)
- [ ] **`main.tex`** — Eine Titelseite auswählen: `frontpage_v1` oder `frontpage_v2` einkommentieren
- [ ] **`main.tex`** — Nicht benötigte Kapitel auskommentieren (`\include{chapters/...}`)
- [ ] **`main.tex`** — Optionale Verzeichnisse bei Bedarf einkommentieren:
  - Abbildungsverzeichnis (`\listoffigures`)
  - Tabellenverzeichnis (`\listoftables`)
  - Quellcodeverzeichnis (`\lstlistoflistings`)
  - Glossar / Abkürzungsverzeichnis (`\printglossary`)
- [ ] **`main.tex`** — Anhang bei Bedarf einkommentieren (`\appendix`, `\input{appendix/anhang_A}`)

## Vor der Abgabe

- [ ] **`preamble.sty`** — `\usepackage[disable]{todonotes}` einkommentieren, um alle `\todo{}`-Boxen zu deaktivieren
- [ ] **`main.tex`** — Alle auskommentierten Platzhalter-Includes entfernen
- [ ] Sicherstellen, dass keine `\todo{}`-Boxen mehr im Dokument sichtbar sind (Kompilierung mit `[disable]` prüfen)
- [ ] Sicherstellen, dass keine TODOS mehr in TODO.md offen sind

## Optionale Pakete (bei Bedarf in `preamble.sty` einkommentieren)

- [ ] **Glossar** — `\usepackage[acronym,xindy,toc]{glossaries}` ist bereits vorbereitet; nur aktivieren wenn Glossar benötigt
- [ ] **Zweite Bib-Datei** — `\addbibresource{bib/images.bib}` für separate Bildquellenverwaltung
