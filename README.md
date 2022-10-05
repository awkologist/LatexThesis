# LatexThesis
Vorlage für Protokolle, Belege und Abschlussarbeiten

## What's new?
In einer älteren Version konnte es zu dem LaTeX Error "File 'scrpage2.sty' not found." kommen. Infolgedessen wurde keine PDF-Datei erzeugt. Das *scrpage2*-Paket ist für die Beschriftung der Seitenköpfe zuständig und veraltet. Ich habe es durch das Paket *scrlayer-scrpage* in der Datei *hsmw-class.cls* ersetzt.

## Tipps

### Buchseiten in Literaturverzeichnis
Wenn Sie die das BibTex-Format *@book* verwenden, dann wird der Tag *pages* ignoriert:

- Wünschiers, R (2016). Wiley-Schnellkurs Bioinformatik – Datenmassen Richtig Fassen.
In: Wiley-VCH, ISBN: 978-3-527-53040-3.

Bei dem Format *@inbook* werden die Seiten dagegen angezeigt:

- Wünschiers, R (2016). Wiley-Schnellkurs Bioinformatik – Datenmassen Richtig Fassen.
In: Wiley-VCH, 72–89. ISBN: 978-3-527-53040-3.

Wenn Sie zu den Seitenzahlen noch Text voranstellen (`pages = {S. 72-89}`), wird dieser auch im Literaturverzeichnis angezeigt:

- Wünschiers, R (2016). Wiley-Schnellkurs Bioinformatik – Datenmassen Richtig Fassen.
In: Wiley-VCH, S. 72–89. ISBN: 978-3-527-53040-3.
