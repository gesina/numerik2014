# Vorlesungsmitschrift Numerik
Dies sind die Quellen einer Vorlesungsmitschrift der Vorlesung
*Numerik* an der Universität Regensburg im Wintersemester 2014/2015,
gehalten von [Frau Prof. Dr. Blank](http://www.mathematik.uni-regensburg.de/Mat8/Blank/).

## Urheberrecht
Urheber des Inhalts dieser Mitschrift ist 
[Frau Prof. Dr. Blank](http://www.mathematik.uni-regensburg.de/Mat8/Blank/). 
Dies ist nur eine genehmigte Vorlesungsmitschrift und 
unterliegt dem deutschen Urheberrecht, jegliche nicht rein private
Verwendung muss demnach vorher mit Frau Blank abgesprochen werden.

Alle Grafiken, die mit © gekennzeichnet sind, stehen unter dem
Urheberrecht von Josef Wimmer.

## Dateiübersicht
- Hauptdatei: `numerik_script.tex`
- reguläre Kapitel: `chapters/numerik_chap0[1-9].tex`
- Literatur: `numerik_script.bib`
- LaTeX-Konfigurationen/-Definitionen: `numerik_config.tex`
- Bilder und Quelldateien für TikZ-Grafiken: `images/*`

## Bilder
Herzlichen Dank an **Joseph Wimmer**, der für die beachtliche
Sammlung an Illustrationen gesorgt hat. 
Anstelle der wenigen fehlenden Bilder ist das Bild `images/image_missing.jpg`
eingebunden.

## Kompilieren
(Getestete) Systemvoraussetzungen: `TeXLive 2016`-Distribution

Zum Kompilieren folgende Befehle (in dieser Reihenfolge) ausführen:

```bash
pdflatex numerik_script.tex
makeindex numerik_script
biber numerik_script
pdflatex numerik_script.tex
```
