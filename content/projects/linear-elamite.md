+++
title = "Elamische Strichschrift"
+++


Seit rund hundert Jahren stellt die elamische Strichschrift für Sprachforscher ein unlösbares Rätsel dar. Bis vor kurzem waren kaum über zwanzig Texte bekannt, davon nur eine einzige Bilingue, d.h. eine in die verständliche altbabylonische Sprache übersetzte Inschrift. Bisher ist für acht Zeichen der Lautwert bekannt. Vor einiger Zeit kamen nun im Iran, wo M. Mäder 2014 eine selbstfinanzierte Studienreise durchführte, zahlreiche neue Fundstücke zum Vorschein, sodass sich der Textbestand mehr als verdoppelt hat und der erste Entzifferungsversuch seit 1969 neue Resultate verspricht.

2016 Konnte M. Mäder im Rahmen des offiziellen Kursangebotes am Institut für Sprachwissenschaft eine Einführung in das Thema geben. Der zweisemestrige Kurs "Eine unbekannte Schrift entziffern – die elamische Strichschrift" war sehr produktiv, und ein grosser Teil der Vorarbeiten wurde in Zusammenarbeit mit den Studenten durchgeführt.

## Die digitale Sequenzanalyse, angewendet auf die elamische Strichschrift
Die im letzten Jahr am ZEAS "Zentrum für die Entzifferung antiker Schriftsysteme" entwickelte Methode umfasst, nebst den Vorarbeiten wie Sammeln und Abzeichnen der Texte, folgende Teilschritte:
-  Erstellen einer  digitalen Schrift mit Vektorisierung aller Zeichen und bedeutenden Varianten im Programm "Font Forge"
-   Veröffentlichen der Zeichen im Unicode PRIVATE-USE Bereich
-  Programmieren des [Webbrowser-basierten Entzifferungstools](http://center-for-decipherment.ch/tool) zur Ermöglichung des Digitalen Durchsuchens der Texte, auch mittels spezifischer RegEx-Befehle. Kernstück ist das dynamische Syllabar, das es ermöglicht, die Aufteilung in Hauptzeichen und Varianten stetig anzupassen. Bisherige Entzifferungsversuche scheiterten meist daran, dass ohne Verständnis der Schrift nicht klar ist, welche Zeichen einen eigenen Wert haben und welche nur graphische Varianten sind. (Besonders in der kypro-minoischen Schrift, die über mehrere Jahrhunderte  gebraucht wurde und auch je nach Schriftträger andere Zeichenformen zeigt, ist ein dynamisches Syllabar vielversprechend, da man eine gewisse statistische Untersuchung für verschiedene Hauptzeichen-Varianten-Aufteilungen mehrmals durchlaufen lassen kann – ein Vorgehen, das ohne digitale Hilfsmittel nicht zu bewältigen wäre.)
Im weiteren Verlauf waren Dutzende von Anpassungen des Entzifferungstools vonnöten. Zahlreiche Optionen wurden hinzugefügt, wie Durchsuchbarkeit in beiden Richtungen (da die Leserichtung a priori nicht klar ist); Auslassen oder Berücksichtigen der Zeilenumbrüche; optionales Auslassen nicht schriftartiger Zeichen; Aufteilung des Gesamtkorpus in Untergruppen (um z.B. fälschungsverdächtige Gruppen auszuschliessen oder Teilkorpora veschiedener Epochen separat zu untersuchen); in Listen darstellbare Frequenzanalysen für einzelne Zeichen sowie Zeichensequenzen.
-  Sequenzanalyse: Mittels eines eigens entworfenen Regex-Befehls namens "Repetitions with omissions" suchten wir nun im digitalisierten Korpus nach teilkongruenten Sequenzen. Aus den Resultatlisten erstellten wir alsbald die sogenannten Slot-Tabellen (Kap. 5 der Arbeit [Sequenzanalysen zur elamischen Strichschrift](/pubs/Maeder%20et%20al%202018__Sequenzanalysen%20zur%20elamischen%20Strichschrift___Sequence%20Analysis%20in%20Linear%20Elamite.pdf)). Sie waren der eigentliche Durchbruch, da wir aufzeigen konnten, dass die Sequenzen, die im gleichen Slot stehen, die gleichen linguistischen Funktionen haben müssen.
-  Erstellen einer Wortende-Statistik: Einige der Zeichen kommen signifikant häufiger an Wortenden (die wir zuvor in den Slot-Tabellen definiert haben) vor als der Durchschnitt – ein Muster, das in allen menschlichen Sprachen zu erwarten ist.
-  Erkennen paradigmatischer Muster: Wenn sich an Wortenden verschiedene kurze Sequenzen an immer dieselbe längere Sequenz heften, sind erstere wohl Suffixe und zweitere wohl Stämme.
-  Vergleich mit bisher vorgeschlagenen Lautwerten: Aufgrund von Bilinguen oder "Bildunterschriften" (wenn z.B. ein Siegel oder eine Statue eine bekannte Persönlichkeit abbildet) existierten wie in den meisten unentzifferten Schriften Lautvorschläge für einzelne Zeichen. Für das Einsetzen dieser Lautwerte in den Fliesstext der Zeichen erstellten wir eine eigene Funktion im Elamicon-Entzifferungstool.
-  Vorschläge formulieren, Resultate zusammenfassen: Jeder aufgrund dieses Vorgehens gemachte Lautwert-Vorschlag machte eine Reihe von Nachuntersuchungen nötig. Genaue Kenntnisse der elamischen Keilschriftgrammatik waren nötig, sodass wir nun beweisen können, dass hinter der unbekannten Schrift die elamische Sprache steckt.

Bisher erledigte Arbeiten:
Sammeln und Abzeichnen aller Texte
Besichtigen und Abzeichnen zweier bisher unentdeckter beschrifteter Silberkessel in einer Privatsammlung in Genf.
Digitalisieren des elamischen Zeichenkorpus, erstellen einer Unicode-Schrift, um die Texte elektronisch zu durchsuchen.
Erstellen des [Online-Entzifferungstools](http://center-for-decipherment.ch/tool) in Zusammenarbeit mit dem ebenfalls unentgeltlich wirkenden Informatiker Stephan Balmer.
Erstellen von Sequenzanalysen, um Morpheme zu isolieren und die Sprache, die hinter den Inschriften steckt, benennen zu können. Die zurzeit noch in Entwicklung befindliche Methodik zur Erkennung von Wortgrenzenprobabilitäten (word end probability) und die im Elamicon Webtool anwendbaren Regex-Befehle wie z.B. "finden von teilkongruenten Zeichensequenzen" (repetitions with omissions) müssen auf eine mathematisch befriedigende theoretische Basis gestellt werden. Unicode-basierte Entzifferungsmethoden wurden bisher unseres Wissens noch nie auf alte, natürlich entstandene Schriften angewandt, deshalb muss unsere Methodik wasserdicht begründet werden.
Erstellen eines provisorischen, dynamischen Zeichenkatalogs, der bei neuen Erkenntnissen geändert werden kann.

Folgende Arbeiten sind in Zukunft zu erledigen:
Weitere statistische Untersuchungen durchführen, ständiges Anpassen des Elamicon Entzifferungstools.
Zusammenarbeit mit Archäologen aus der Region (es bestehen Kontakte mit Dr. Aliashgar Nouruzī von der Universität Hamedān, Iran).
Ausschau halten nach neuen Inschriften.
Fertigstellen des Fachartikels "Sequenzanalysen zur elamischen Strichschrift"
Zusammenfassung der Resultate in einer für die Öffentlichkeit lesbaren Publikation (Buch) in Europa sowie, mithilfe der Persischkenntnisse von Nabi Jaffari, im Iran. So können der iranischen Bevölkerung, die sich allgemein sehr für ihr kulturelles Erbe interessiert, unsere Resultate dargelegt werden. Es ist sehr schade, dass in Europa viel über die iranische Vergangenheit geforscht wird, von dem die Iraner aber gar nie etwas erfahren, weil ihnen deutsch- und Englischsprachige Fachartikel nicht im Ansatz zugänglich sind.
Vorträge vor einem nichtakademischen Publikum, Einbezug von Laien aller Interessensgebiete (sog. Open-Public-Ansatz), um möglichst viele Hirne in den Entzifferungsprozess einzubeziehen und Bern als Ganzes zu einem Kompetenzzentrum für die moderne, computergestützte Schriftentzifferung zu machen.
Wecken des öffentlichen Interesses (Interviews in Zeitschriften, guter Online-Auftritt), um dem Steuerzahler zu zeigen, welch spannende Tätigkeiten an der Universität Bern durchgeführt werden.

