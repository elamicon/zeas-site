+++
title = "Byblos"
+++

## Ausgangslage

Die Byblos-Schriftstücke stammen überwiegend aus Ugarit (heutiges Nordwest-Syrien) und sind bis heute unentziffert. Sie datieren in die Zeit des ausgehenden altägyptischen Königreichs, d.h. um 2200 v. Chr. (Hoch 1990:119). Aufgrund der Anzahl verschiedener Zeichen – je nach Zählweise zwischen 50 und 150 – nimmt man an, es handle sich um eine Silbenschrift. Es existieren 14 unterschiedlich lange Inschriften auf Bronze oder Stein, wobei vor allem die Inschriften auf Bronzetafeln (vgl. Abb. 1) ausreichend lang und gut leserlich sind, sodass Erfolge bei einem computergestützten Entzifferungsversuch im Bereich des Möglichen liegen. Es existieren einige auf Formähnlichkeit mit agyptischen Hieroglyphen beruhende Vorschläge für Silbenwerte (Lautwerte). Diese konnten aber bisher nicht auf eine befriedigende Grundlage gestellt werden.


## Die Bedeutung für die Herkunft der europäischen Alphabete

Dass unsere modernen Schriften auf das phönizische Alphabet zurückgehen, das um 1000 v. Chr. im heutigen Libanon und Syrien in Gebrauch war, ist bekannt. Doch eine weitere geschichtliche Rückverfolgung ist bisher nicht zweifelsfrei möglich, insbesondere kann die vermutete Abstammung von den ägyptischen Hieroglyphen nicht nachgewiesen werden. Die Byblos-Schrift spielt bei dieser Frage möglicherweise eine entscheidende Rolle, jedenfalls gilt sie als prominentester Kandidat für eine Übergangsphase zwischen Hieroglyphen und abstrahierter Alphabetschrift (Mendenhall 1985).


## Das Projekt

In den letzten fünf bis zehn Jahren hat die Entwicklung im IT-Bereich entscheidende neue Möglichkeiten in der Analyse unentzifferter antiker Schriftsysteme hervorgebracht. So kann im Private-Use-Bereich von Unicode eine beliebige Anzahl Schriftzeichen erstellt und elektronisch durchsuchbar gemacht werden. Mit entsprechenden Regular Expressions (Regex) können Einblicke in die phonotaktische Struktur der Texte gewonnen werden, die wiederum Auskunft über den Bau der zugrundeliegenden Sprache geben. Dies führt zu einer neuen Stossrichtung in der Entzifferungstechnik: Wir beabsichtigen nicht, wie in herkömmlichen Entschlüsselungsversuchen, Lautwerte zu postulieren, sondern wir gewinnen statistische Daten, die es uns zum Beispiel erlauben, Wortgrenzen zu erkennen, allfällige Prä- und Suffixe zu isolieren, zugehörige Verbal- und Nominalstämme zu benennen usw. Erst in einem zweiten Schritt werden wir bisherige Lautwertvorschläge auf ihre statistische Wahrscheinlichkeit hin überprüfen, d.h. mit der aus den existierenden Sprachen bekannten Häufigkeitsverteilung der Silben abgleichen.

## Das dynamische Syllabar

Mit einem entscheidenden Problem haben alle Analyseversuche unbekannter Schriftsysteme zu kämpfen: Es exisiteren unter sich ähnliche, aber nicht identische Schriftzeichen, und es ist a priori nicht möglich zu entscheiden, welche der Zeichen Haupttypen und welche nur grafische Varianten dieser Haupttypen sind. Bevor ein System vollständig entziffert ist, kann also nicht entschieden werden, ob zwei formähnliche Zeichen die gleiche Funktion haben oder nicht. Im Juli 2016 stellte eine Gruppe von Linguisten und Informatikern unter der Leitung von Michael Mäder ein eigens für dieses Problem programmiertes Entzifferungstool vor, das es erlaubt, ein Zeichen jederzeit einer beliebigen Haupttype oder es selber zu einer Haupttype zu machen. So können mit verschiedenen Versionen des Syllabars dieselben statistischen Untersuchungen durchgeführt werden, und aufgrund der neuen Erkenntnisse kann das Arbeitssyllabar (d.h. die momentan verwendete Einteilung in Haupttypen und Varianten) laufend angepasst werden.