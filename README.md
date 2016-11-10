# Vorlage und Beispiel für den Abschlussbericht im Modul Experimentelle Kognitionswissenschaft
Im Unterordner ``vorlage`` befindet sich eine LaTeX Vorlage für den Abschlussbericht im Modul Experimentelle Kognitionswissenschaften. Im Ordner ``beispiel`` befindet sich als Beispiel mein Abschlussbericht aus dem Wintersemester 2014/2015 mit dem Titel "Mechanismen der Aufmerksamkeitsaktivierung" in dem ich diese Vorlage verwendet habe.

## Verwendung
Die Vorlage ist so gestaltet, dass man nur wenig Kenntnis über LaTeX benötigt. Die einzelnen Schritte sind:
1. Eure Daten (Nachname, Vorname, BetreuerIn, Institut, Matrikelnummer, Fachbereich und Titel) in der Datei ``bericht.tex`` eintragen.  
2. Eure Grafiken in den Ordner ``grafiken`` speichern (Wie man diese erstellt, werden wir später in den Sitzungen zu R behandeln).
3. In den jeweiligen Dateien im Ordner ``abschnitte`` eure Abschnitte schreiben.
4. In der Datei ``references.bib``, die von euch zitierten Werke eintragen.
5. Grafiken einbinden (siehe dazu zum Beispiel mein Beispielbericht)
6. Kompilieren (entweder über eine IDE, z.B. Texstudio, oder per Commandline mittels ``make``)

## Ordnerstruktur
vorlage/  
├── bericht.tex  
├── references.bib  
├── abschnitte/  
│   ├── title.tex  
│   ├── abstract.tex  
│   ├── einleitung.tex  
│   ├── methode.tex  
│   ├── ergebnisse.tex  
│   ├── diskussion.tex  
│   └── erklaerung.tex  
├── grafiken/  
└── Makefile  
