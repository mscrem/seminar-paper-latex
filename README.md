# seminar-paper-latex
Template für Seminararbeiten in LaTeX

## Referenzen
In diesem Template wird als Bibliotheksverwaltung bibtex verwendet.

Unter \addbibresource{.../.bib} muss die jeweilige .bib Datei mit der Literaturliste angegeben werden.

Es wurde eine Funktion erstellt, welche es ermöglicht "Kurzzitate" anzugeben. Dies ist z.B. beim Zitieren von Aristoteles hilfreich.
Im Text wird hierfür \shortcite verwendet.
Wichtig ist, dass in der .bib Datei dafür ein weiteres Attribut angegeben werden muss, z.B:
shorttitle = {Arist. De an.}

Das Literaturverzeichnis wird dann automatisch auf Basis der zitierten Literatur erstellt.
