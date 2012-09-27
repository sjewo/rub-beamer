rub-beamer
==========

LaTeX Beamer Template for Ruhr-University Bochum
LaTeX Beamer Vorlage für die Ruhr-Universität Bochum

Installation
============

Der Ordner rub-beamer in den Ordner /tex/latex/ im texmf Verzeichnis des Benutzers kopieren.

Wenn die RUB Schriftarten  nicht verwendet werden sollen, kann dies durch das auskommentieren von 
"\usefonttheme{Rub}" in "tex/latex/rub-beamer/beamerthemerub.sty" erreicht werden.

Einbindung in eine Beamer-Präsentation
======================================

Die Vorlage kann einfach über den Befehl `\usetheme[optionen]{Rub}` eingebunden werden. 
*Das RUB-Logo (logo.pdf) und die Wortmarke (wortmarke.pdf) liegen noch nicht im Repository, da dies noch von der Pressestelle freigegebn werden muss.*

Es gibt drei Varianten für die Titelseite, die über ein optionales Argument ausgewählt werden können:
* alternativetitlepage=bild

 ![Titelseite bild](http://www.stat.rub.de/latex/bild.png)
* alternativetitlepage=normal

 ![Titelseite normal](http://www.stat.rub.de/latex/normal.png)
* alternativetitlepage=alternativ

 ![Titelseite alternativ](http://www.stat.rub.de/latex/alternativ.png)

Zusätzlich beinhaltet die Vorlage noch einen "aufgeräumten" Modus:
* `alternativetitlepage=bildempty`, ist eine Titelseite, bei der der Text direkt über das Hintergrundbild gelegt wird.
* `empty`,  schaltet den aufgeräumten Modus ein.

Mit `\titlegraphic{bild.jpg}` kann ein Bild für die Titelseite definiert werden. Ein mögliches weitere Logo lässt sich mit `\sponsorlogo[height=15mm]{logo.pdf}` einbinden.
