---
title: "Textbausteine zur Begutachtung von Seminar- und Abschlussarbeiten"
author: "Sebastian Sauer"
date: "2020-01-08"
numbersections: TRUE 
lang: de-De
output:
  html_document:
    highlight: pygments
    keep_md: yes
    number_sections: yes
    toc: yes
  md_document:
    toc: true
    variant: gfm
---



# CHECKLISTE -- SEMINARARBEIT (xxcheckseminar) {#checkseminar}

## Formalia (Checkliste Seminararbeit **checkform**)

1. WICHTIG Titel  [optisch prägnant?](#titelformatierung) und [präzise?](#titelinhalt)
2. WICHTIG [Abstract: vorhanden und korrekt?](#abstract)
2. Gliederung [optisch prägnant?](#gliederungformat) und [passend zum Titel/Forschungsfrage?](#gliederunginhalt)
4. Textsatz [allgemein ok?](#typo)
5. [Silbentrennung ok?](#silbentrennung)
6. [Absatzformatierung ok?](#absatz)
7. [Rechtschreibung ok?](#rechtschreibung), z. B. [Fremdwörter](#fremd) und [Kopplung](#rechtkommentare)?
8. [Zitieren im Text ok?](#zitieren)
9. WICHTIG [Literaturverzeichnis ok?](#litverzzitieren)
10. [Referenzieren ok?](#referenzieren)


## Methoden (Checkliste Seminararbeit **checkmeth**)


### Methoden -- QUANTITATIV


1. WICHTIG [Reproduzierbarkeit](#repro)
2. [Design der Studie](#studiendesign)
3. WICHTIG [Messinstrumente und Stimuli](#measurement)
4. WICHTIG [Stichprobe](#sample)
5. WICHTIG [Hypothesen](#hypothesen)
6. WICHTIG [Datenauswertung](#datenanalyse)



### Methoden -- Qualitativ

1. [Zusammenstellung der Stichprobe begründet?](#stiprozusammenstellung)
2. [Ethik expliziert und korrekt durchgeführt?](#ethik)
2. [Kodierregeln expliziert?](#kodierregeln)
3. [Qualität und Menge der Kategorien](#kategoriensystem)
4. [Ergebnisdarstellung der Inhaltsanalyse korrekt?](#ergebnissequali)


### Methoden -- Qualitativ - Summarisch 

Summarisch: [Sehr gute qualitative Methoden](#sehrgutequalimeth)

Summarisch: [Keine Kodierregeln defniert](#schlechtequalimeth)

## Inhalt (Checklist Seminararbeit **checkinhalt**)

1. [Forschungsfrage expliziert?](#fofrage)
2. WICHTIG [Roter Faden erkennbar?](#roterfaden)
3. WICHTIG [Literaturmenge ok?](#literaturmenge)
4. [Güte der Quellen ok?](#fachartikelverwendet)
5. [Sprachlicher Ausdruck ok?](#sprache)
6. [Limitationen diskutiert?](#limitationen)






# CHECKLISTE -- DATENANALYSE (xxcheckdat) {#check}


## Formalia (Checkliste Datenanalyse)


1. Werden alle angeforderten Arbeitsschritte abgeleistet (z. B. genug Hypothesen geprüft, Datensatz beschrieben, Skalenniveaus benannt)? [Vollständigkeit](#vollstaendig), [Skalenniveau](#skalenniveau), [Datensatz-Beschreibung](#datasetdescription)

2. Wurden Syntax, Schriftsatz und R-Ausgabe übersichtlich gestaltet? [Syntax-Formatierung](#syntaxformatierung), [R-Ausgaben](#routput), [RMarkdown](#rmarkdown), [Typografie](#typo), [Rrring](#rrring), [Lesbarkeit](#lesbarkeit)

3. Sind die Abbildung korrekt/optisch ansprechend gestaltet (z. B. Achsen beschriftet, nicht pixelig)? [Daten-Abbildungen](#datadiagrams)

## Methodik (Checkliste Datenanalyse)

4. Wurden passende Verfahren der Inferenzstatsistik ausgewählt und angewendet? [Verfahrensauswahl](#auswahlverfahren), [Verfahren anwenden/bewerten](#ergbewertung)

5. Wurden passende Verfahren der Deskriptivstatistik ausgewählt und angewendet? [Deskriptivstatistik](#deskriptivstatistik), [Effektstärke](#effsize), [Konfidenzintervalle](#ki)

6. Sonstiges? (z. B. [Nachkommastellen](#Nachkommstellen))


## Theorie und Diskussion (Checkliste Datenanalyse)

7. Wurden die Ergebnisse der Inferenzstatistik korrekt interpretiert? [p-Wert](#pvalue), [Hypothesentesten](#hyptests)


8. Wurden Forschungsfragen oder Hypothesen sinnvoll formuliert? [Hypothesen](#hypothesen)

9. Passen Forschungsfrage, Hypothesen und Analyse zueinander? [Roter-Faden](#roterfaden)

10. Ist die Analyse breit angelegt? Ist der Anspruch hoch? [Breite](#analyse-allgemein), [Anzahl der Hypothesen](#anzhyps)

11. Wurde das Vorgehen kritisch reflektiert? [Diskussion](#diskussion), [Overcertainty](#overcertainty)


<br>
<br>
<br>


# LINKS ZU ZENTRALEN ABSCHNITTEN

1. [..FORMALES..](#formales)

    1. [Zitieren und Referenzieren](#zitieren)
    1. [Rechtschreibung](#rechtschreibung)
    
    
3. [..METHODEN..](#methoden)

    1. [Datenanalyse](#datenanalyse)

    2. [Qualitative Inhaltsanalyse](#quali)

6. [..INHALT..](#inhalt)

    1. [Literaturnutzung und Sachkenntnis](#fachkenntnis)

    2. [Reflexion, Diskussion](#diskussion)

9. [..PLAGIATE..](#plagiate)

10. [..KOMMENTARE..](#kommentare)

<br>
<br>
<br>

# FORMALES (*xxform**) -------------------------------------------- {#formales}

## Formalia (xxformal) {#formalia}
### Formalia - Beurteilung
- \+ Formalia (wie Titelblatt entsprechend der Richtlinien gestaltet; Verzeichnisse vorhanden etc.) wurden angemessen umgesetzt.

- \- Formalia (wie Titelblatt entsprechend der Richtlinien gestaltet; Verzeichnisse vorhanden etc.) wurden nicht vollständig oder nicht angemessen umgesetzt.

- \- Es finden sich gravierende formale Mängel.
- \- Aufgrund von formalen Mängeln ist die Arbeit als mangelhaft beurteilt.

- \- Es finden sich formale Mängel.
- \- Es finden sich kleinere formale Mängel.



### Formalia - Kommentare

- \- Entgegen den formalen Vorgaben wurde kein ausgedrucktes Exemplar dem Gutachter vorgelegt.
- \- Entgegen den formalen Vorgaben wurde die Arbeit nicht mit LaTeX oder `RMarkdown` erstellt. 
- \- Die Wortzahl wurde nicht angegeben: Entgegen den formalen Vorgaben wurde die Anzahl der Wörter (des Hauptteiles) nicht oder nicht an richtiger (und direkt einsehbarer) Stelle angegeben.

- \- Es wurde kein Thema angegeben im Online Campus.

- \- Bitte nutzen Sie keine Klebebindung für Ihre Arbeit, da das Umblättern auf diese Art erschwert ist.

- \- Es finden sich formale Fehler auf der Titelseite (z.B. falsches Datum).
- \- Das Tabellen- und Abbildungsverzeichnis sollte sich vor der Gliederung befinden.


## Vollständigkeit {#vollstaendig}

- \+ Die Arbeit ist vollständig insofern, als dass alle (wesentlichen) geforderten Arbeitsschritte ausgeführt wurden.
- \+ Die Arbeit ist vollständig insofern, als dass alle (wesentlichen) geforderten Arbeitsschritte ausgeführt wurden. Diese Schritte beinhalten z. B. die Beschreibung relevanter Aspekte des Datensatzes wie die Skalenniveaus, Visualisierung der Datenlage, Durchführen von deskriptiver und schließender statistischer Verfahren sowie eine Diskussion der Befunde.

- \- Die Arbeit ist unvollständig insofern, als dass nicht alle (wesentlichen) geforderten Arbeitsschritte ausgeführt wurden. Es fehlen wesentliche Aspekte, die Teil der Aufgabenstellung waren, aber nicht (vollständig) umgesetzt wurden.




## Typografie und Erscheinungsbild (xxtypo) {#typo}

### Schriftsatz und Erscheinungsbild - Beurteilung
`+++`


- \+ Die Arbeit macht einen *sehr guten äußeren Eindruck*; Schriftsatz und -bild sind sehr ansprechend gestaltet.
- \+ Die Arbeit macht insgesamt einen *guten äußeren Eindruck*; Schriftsatz und -bild sind insgesamt ansprechend gestaltet.
- \+ Die Arbeit macht insgesamt einen *guten (aber nicht sehr guten) äußeren Eindruck*; Schriftsatz und -bild sind insgesamt ansprechend gestaltet.
- \+ Die Gestaltung der Arbeit ist insgesamt *optisch ansprechend*.

- \+ Das mit \TeX gestaltete Schriftbild hebt sich positiv vom Standard-MS-Word-Schriftsatz ab.

`++--`


- \+- Die Gestaltung der Arbeit ist *weitgehend optisch ansprechend*.
- \+- Der äußere Eindruck der Arbeit ist von *mittlerer Güt*e.
- \+- Weite Teile der Arbeit sind äußerlich ansprechend, allerdings gibt es ein paar *gestalterische Schwächen*.

- \- Die Arbeit macht insgesamt *keinen* ansprechenden äußeren Eindruck; z. B. sind Schriftsatz und -bild nicht ansprechend (genug) gestaltet.




### Schriftsatz und Erscheinungsbild - Kommentare {#typokommentare}

`+++`

- \+ *Typografische Elemente* wie Kerning, Ligaturen und intelligentes Trennen wurden in hoher Qualität umgesetzt.

- \+- Hier finden sich *Hinweise*, wie der Schriftsatz (Kerning, Ligaturen, schöne Schriften, Trennung, etc.) schöner gestaltet werden kann: <http://nitens.org/taraborelli/latex>.
- \+- Es wurde linksbündig formatierter Text ("Flattersatz") verwendet, was typographisch nicht unumstritten ist, aber aus Sicht dieses Gutachters typographisch nicht schlechter ist als der Schriftsatz, der durch die Silbentrennung von MS Word erzeugt wird.
  
  
- \+ Ein *Zitat* oder mehrere Zitate wurden in gewinnbringender, schmückender Form verwendet.

`---`


- \- Das Schriftbild wirkt teilweise "*verwaschen*" oder "verlaufen" (evtl. nur im Ausdruck).





- \- *Unterstreichungen* als Emphasis sollten vermieden werden, da gestalterisch und ästhetisch suboptimal; Unterstreichungen sind ein Überbleibsel auf der Schreibmaschinen-Ära.

- \- Gedruckter, längerer Text sollte besser in einer *Serifen*-Schriftart (z. B. Times) gesetzt sein (nicht in einer serifenlosen Schriftart wie Arial). Das wurde in der vorliegenden Arbeit nicht berücksichtigt (vgl. einschlägige Leitfäden und Literatur).
- \- Es finden sich einige *Fehler im Textsatz* (z. B. fehlerhafte Einrückungen, fehlerhafte Trennungen, Schusterjungen, etc.).

- \- In einem wissenschaftlichen Bericht dieser Art sollte keine R-Syntax bzw. kein unformartierter R-Output aufgeführt sein.
- \- Es wurden* Ziffern als Zahlzeichen* geschrieben ("2"), die besser ausgeschrieben worden wären ("zwei").

- \- *Fettdruck* gilt zur Hervorhebung bzw. Betonung einzelner Passagen in Fließtexten als wenig geeignet, da zu dominant im Textfluss.
- \- *Neue Kapitel beginnen auf einer neuen Seite* und werden nicht, wie in der vorliegenden Arbeit zu finden, auf der gleichen Seite fortgeführt.
- \- Es finden sich einige *Inkonsistenzen im Textsatz* (z. B. einige Male wurde vor Gleichheitszeichen Leerzeichen gesetzt; in anderen Fällen nicht).
- \- Innerhalb feststehender Ausdrücke wie "p = .04" oder "42 %"  sollten Zeilenumbrüche vermieden werden; die Leerzeichen in solchen Ausdrücken sollten als "geschützte Leerzeichen" formatiert sein. Dieser Punkt wurde in der vorliegenden Arbeit nicht durchgängig berücksichtigt.
- \- Die *optimale Lesbarkeit liegt bei ca. 65 Zeichen/Buchstaben pro Zeile* oder sogar darunter. In der vorliegenden Arbeit liegt die Zeilenlänge deutlich darüber. 
- \- Die *Laufweite der Schrift (d. h. der Abstand zwischen den Buchstaben)* ist teilweise unpassend (zu groß oder zu klein). 
- \- Die *Seitenränder sind zu klein gewählt*; d. h. nicht günstig gewählt. Größere Seitenränder wirken optisch ansprechender; lange Textzeilen sind nicht gut lesbar. Allgemein wird von einer optimalen Lesbarkeit von etwa 66 Zeichen pro Zeile ausgegangen.
- \- Es wurde an einer oder mehreren Stellen ein *typografisch falsches Apostroph-Zeichen* verwendet. Das korrekterweise zu setzende Apostroph-Zeichen "'" wird häufig mit einem der Betonungszeichen Akut (´) oder Gravis (`) verwechselt -– beide eingebbar über die Taste "´". Wenn sich die Zeichen auch optisch ähneln mögen, sind sie doch nicht gleich in ihrer Bedeutung. 



- \- Zwischen *Abkürzungen* wie *"d. h."*, "S. 42" oder "z. B." ist ein *Leerzeichen* zu setzen; das gleiche gilt für *Prozentzahlen*: z. B. 95 %. Diese Formatierung entspricht der Rechtschreibung laut Duden und DIN 5008. Idealerweise ist es ein sog. \*geschütztes Leerzeichen\* zu verwenden (so dass Trennung zwischen den Bestandteilen vermieden wird). Besser noch sollte es sich um ein "kurzes" bzw. schmales (geschütztes) Leerzeichen handeln (in der Typografie spricht man in dem Fall von einem Achtel-Geviert). Dieser Punkt wurde in der vorliegenden Arbeit nicht komplett berücksichtigt; allerdings handelt es sich um ein Detail.





- \- Im Allgemeinen sollten *Zahlen kleiner als zehn in Ziffern* ausgedrückt werden laut APA/DGPs (z. B. 7, 8, 9); Zahlen größer als 10 in Ziffern. Es gibt einige Ausnahmen von dieser Regel (s. Richtlinien der APA/DGPs); eine davon lautet, dass Sätze nicht mit Ziffern zu beginnen sind. Diese Regel wurde in der vorliegenden Arbeit nicht ausreichend berücksichtigt.

- \- Fußnoten sind ohne Leerzeichen an das letzte Wort zu setzen; sie sind vor dem Punkt, der das Satzende markiert, zu setzen. Dieser Punkt wurde in der vorliegenden Arbeit nicht durchgängig berücksichtigt.

- \- Es finden sich überflüssige *Leerseiten* im Dokument (u. U. nur im Ausdruck).

- \- Nach der  *hintersten* Ziffer in der Nummerierung einer Überschrift* sollte kein Punkt gesetzt werden (falsch: "2.2.2. Theorie X"; richtig: "2.2.2 Theorie X").

- \- Es finden sich "komische" Zeichen (Glyphen) im Schriftsatz (Z. B. "QualitÃ¤"t), die vermutlich auf Enkodierungsfehler zurückzuführen sind. Textdokumente müssen mit der richtigen Enkodierung (z. B. UTF8 oder Latin1) geladen werden und sollten mit der Enkodierung UTF8 gespeichert werden.




### Paginierung

`---`


- \- Der Hinweis "Seite" vor der Angabe der Seitenzahl birgt wenig Zusatznutzen; daher sollte auf diesen Zusatz verzichtet werden.

- \- Auf der Titelseite soll keine Seitenzahl ausgewiesen werden.

- \- Der Hauptteil einer Arbeit soll mit arabischen, nicht römischen, Zahlen ausgewiesen werden.



### Kursivsatz vs. Anführungszeichen
`+++`

- \+ Kursivdruck wurde korrekt (im Sinne der Vorgaben der APA) eingesetzt.


`---`



- \- *Kursivdruck* ist für die *erstmalige Verwendung neuer Fach- bzw. Schlüsselbegriffe* zu verwenden, nicht aber (doppelte) Anführungszeichen (vgl. APA, 2009, S. 104). Beispiel: "Die Bedingung *negative Verstärkung* wird operationalisiert, indem XXX".

- \- Für die Einführung neuer Begriffe ist der Begriff kursiv zu setzen (beim ersten Auftreten des Begriffes im Text), aber nicht in Anführungsstriche zu setzen. Dieser Punkt wurde in der vorliegenden Arbeit nicht (durchgängig) berücksichtigt.

- \- *Fachbegriffe*, die neu im Text eingeführt werden, sind beim *ersten* Anführen *kursiv* zu setzen, aber nicht in Anführungsstriche zu setzen. Dies wurde in der vorliegenden Arbeit nicht durchgängig umgesetzt.

- \- Erwähnt man den Namen eines Messinstruments, etwa *Mindfulness Attention and Awareness Scale*, so sollte der Name beim ersten Anführen kursiv gesetzt sein.

- \- *Antwortoptionen* einer *psychometrischen Skala sollen kursiv gesetzt* sein, etwa: "Die Items waren mittels einer vierstufigen Likertskala zu beantworten mit den Stufen von 1 (*stimme überhaupt nicht zu*) bis 4 (*stimme voll und ganz zu*).

- \- *Statistische Symbole* wie $n = 200$ oder $SD = 1.23$ sollten *kursiv* gesetzt sein; für griechische Buchstaben gilt dies nicht. Dies wurde in der vorliegenden Arbeit nicht durchgängig umgesetzt.










### Silbentrennung {#silbentrennung}

`+++`

- \+ Die Silbentrennung wurde in sinnvoller Weise verwendet, um "Löcher" im Textsatz zu reduzieren.

- \- Um ein schöneres Schriftbild mit besserem Abstand zwischen den Wörtern zu erreichen, empfiehlt es sich, stets eine Silbentrennung zu verwenden. Dieser Punkt wurde in der vorliegenden Arbeit nicht berücksichtigt.

- \- Der Blocksatz weist unschöne "Löcher" auf (evtl. wg. fehlender Silbentrennung).

- \- Auch beim linksbündigem Text ("Flattersatz") sollte die Silbentrennung eingeschaltet sein, um die Zeilenenden nicht zu unruhig werden zu lassen.  In der vorliegenden Arbeit wirkt der linksbündige formatierte Text daher "flattrig" (aufgrund fehlender Silbentrennung).





### Kapitel-, Absatzwechsel-Formatierung und Absatzlänge {#absatz}

`+++`

- \+ Ein *Absatzwechsel* wurde typographisch sinnvoll kenntlich gemacht.

- \+ Nicht alle Absatzwechsel wurden typographisch sinnvoll kenntlich gemacht (d.h. mit vertikalem Raum oder mit Einrückung der ersten Zeile des Folgeabsatzes).


`---`


- \- Nach einer *Überschrift* sollte weniger vertikaler Abstand gelassen werden als vor einer Überschrift. Der Grund dafür ist, dass vor der Überschrift ein Sinnabschnitt endet und daher vergleichsweise viel Platz angezeigt ist. Nach der Überschrift wird der in der Überschrift angekündigte Inhalte aufgeführt; die inhaltliche Nähe von Überschrift zu Ausführung sollte durch vergleichsweise wenig vertikalem Abstand kenntlich gemacht werden. Dieser Punkt wurde in der vorliegenden Arbeit nicht ausreichend berücksichtigt.

- \- Der *erste Absatz eines Kapitels* sollte nicht eingerückt sein, da es nicht nötig bzw. nicht sinnvoll ist, einen Absatzwechsel anzuzeigen. Dies wurde in der vorliegenden Arbeit nicht berücksichtigt. Allerdings handelt es sich hierbei eher um eine typografische Feinheit, der keine große Bewertungsrelevanz zukommt. 



- \- Ein *Abschnitt* (z. B. "2.1") sollte nicht kürzer sein als eine *halbe Seite*.

- \- Es bieten sich zwei Formate um, um Absätze optisch im Textfluss voneinander zu trennen: Durch vertikalen Abstand oder durch Einrücken der ersten Zeile des Folgeabsatzes. Beide Methoden sind gleich legitim. Hat man sich aber für eine Methode entschieden, so ist sie konsequent einzuhalten. Nicht sinnvoll ist, Absätze ohne einer der beiden gerade genannten Methoden zu trennen. Ebenso sollten nicht beide Methoden gleichzeitig verwendet werden (Leerraum plus Einrücken). Diese Aspekte finden in der vorliegenden Arbeit nicht ausreichend Berücksichtigung.
- \- Verwendet man vertikalen Leerraum zur Trennung von Absätzen, so sollte man den Abstand nicht zu groß (und nicht zu klein) setzen; eine halbe (zusätzliche) Leerzeile ist ein vertretbares Maß. Das Ziel sollte sein, einen Absatz kenntlich zu machen mit so wenig Zusatzabstand wie möglich. Allerdings muss der Abstand größer sein als eine normale Leerzeile (sonst würde kein Absatzwechsel kenntlich sein). In der vorliegenden Arbeit ist der vertikale Abstand nicht durchgehend passend (d. h. zu groß oder zu klein).

- \- Der erste Absatz nach einer Überschrift ist nicht einzurücken (oder durch vertikalen Abstand zur Überschrift kenntlich zu machen). 



- \- Absätze sollten *länger als ein Satz sein*; in der vorliegenden Arbeit gibt es einen oder mehrere Absätze, die nur aus einem Satz bestehen, was typografisch nicht wünschenswert ist. Vermeiden Sie solch kurze Absätze.


- \- Jedes (Haupt-)kapitel beginnt auf einer neuen Seite. Das Gleiche gilt für Abstract, Anhang und Verzeichnisse inklusive dem Literaturverzeichnis. Dieser Punkt wurde in der vorliegenden Arbeit nicht ausreichend berücksichtigt.



### Lesbarkeit  {#lesbarkeit}

`+++`

- \+ Die Arbeit verwendet vergleichsweise kurze Zeilen im Sinne von wenig Buchstaben/Zeichen pro Zeile. Das erhöht die Lesbarkeit des Textes in sinnvoller Weise.

`---`



- \- Seitenzahlen fehlen; das erschwert die Orientierung bzw. den Überblick zu behalten.



### Klammersetzung und Auslassungszeichen

- \- Zu Beginn oder zum Ende eines Zitats sind keine *Auslassungszeichen* zu setzen (und auch nicht in Klammern).
- \- Möchte man *innerhalb eines Zitats* eine Auslassung markieren, so verwendet man Auslassungszeichen (...). Diese sind laut APA/DGPs *ohne eckige oder runde Klammern* zu setzen.
- \- Runde Klammern sind laut APA primär für Einschübe im Text zu verwenden.
- \- Eckige Klammern sind laut APA primär für Konfidenzintervalle zu verwenden. Außerdem können Sie für Erklärungen innerhalb eines Zitats verwendet werden. Schließlich können eckige Klammern verwendet werden, um schon mit Runden Klammern eingefasste Stellen zu kennzeichnen (Ausnahme: Statistiken, die Klammern enthalten, werden nicht durch weitere Klammern eingefasst).






## Umfang

Der Gutachter beziffert seine Anforderung an das grobe Mengengerüst im Hinblick auf die Seiten- bzw. Wortzahl einer Abschlussarbeit wie folgt (vgl. Hinweise für Abschlussarbeiten auf der OC-Seite des Gutachters): 1. Bachelor: ca. 12000 Wörter (40-60 Seiten); 2. Master: ca. 18000 Wörter (ca. 60-80 Seiten).

`+++`

- \+ Der Umfang der Arbeit (an Text) ist genau passend.
- \+ Der Umfang der Arbeit (an Text) ist hoch.
- \+ Der Umfang (an Text) der Arbeit ist vergleichsweise hoch.

- \+ Der Umfang der Arbeit (z. B. Seitenanzahl) ist angemessen.

- \+- Der Umfang der Arbeit (z. B. Seitenanzahl) ist (gerade noch) angemessen.


`---`


- \- Der Umfang der Arbeit ist insgesamt (zu) kurz.
- \- Der Umfang der Arbeit ist insgesamt (zu) lang.
- \- Der Gutachter (Professor Sauer) hat einen Seitenumfang von ca. 12000 Wörtern gefordert. Weiter unten gibt er an, dass Arbeiten, die kürzer als 20% des geforderten Umfangs betragen, als "nicht bestanden" bewertet werden (können). 
- \- Die vorliegende Arbeit umfasst ca. 10000 Wörter; 10/12 entspricht ca. 83%. Damit liegt die Arbeit knapp über der Länge, die zum Bestehen in den formalen Vorgaben angegeben wird. Details finden sich auf der Hinweis-Seite des Gutachters: https://campus.bildungscentrum.de/nfcampus/Course.do?action=read&n=5220&m=854502.
- \- Die Wortanzahl der Arbeit ist nicht oder nicht an geeigneter Stelle dokumentiert.

## Abstract (xxabstract) {#abstract}

`+++`

- \+ Ein Abstract, der das Überblicken der Arbeit unterstützt, ist *vorhanden.*
+ \+ Der Abstract enthält die nötigen Informationen; er ist *präzise* und stringent formuliert.
+ \+ Der Abstract ist *insgesamt sinnvoll aufgebaut* und geht auf einige wesentliche Aspekte der Studie ein.


`000`

- \+- Ein Abstract ist vorhanden, der auf einiges relevantes Material eingeht, jedoch von Präzisierung profitiert hätte.


`---`



- \- Ein Abstract, der das Überblicken der Arbeit unterstützt, *fehlt*, wäre aber sinnvoll gewesen.



- \- Der Abstract ist *nicht (durchgängig) präzise* genug formuliert.

- \- Der Abstract *enthält nicht alle nötigen Informationen* (z. B. Methode oder Ergebnisse der Studie sind bruchstückhaft dargestellt).
- \- Der Abstract enthält *unnötige* Informationen; er ist nicht (durchgängig) prägnant formuliert.
- \- Der Abstract ist *zu lang* gemessen an der Zahl der Wörter.

- \- Der Abstract *sollte direkt nach der Titelseite*, noch vor den Verzeichnissen, eingeordnet sein. Dies ist in der vorliegenden Arbeit nicht der Fall.
- \- Der Abstract sollte sich in *Abfolge und Inhalt am Haupttext* orientieren; die Aufgabe des Abstracts ist es, das Verständnis des Textes im Überblick zu erleichtern. Dieser Aufgabe wird der Abstract im vorliegenden Fall nicht oder nicht in gutem Maße gerecht.
- \- Der Abstract sollte eine *"eigene" Seite* in Anspruch nehmen; das nächste Kapitel beginnt auf einer neuen Seite; das gilt für alle Hauptabschnitte wie Kapitel und Verzeichnisse der Arbeit.
- \- Der Abstract ist recht *knapp* gehalten und hätte von ausführlicherer Darstellung profitiert.

- \- Die erste Zeile des Abstracts ist *nicht einzurücken*; dies entspricht der Regel, dass der erste Absatz eines Abschnittes/Kapitels grundsätzlich nicht einzurücken ist.

- \- Der Abstract soll *nicht in der Gliederung* erscheinen.

- \- *"Meta-Aussagen"* folgender Art sind (im Abstract und auch andernorts) zu vermeiden: "Es wird das Design begründet", "Es werden die Hypothesen vorgestellt" etc. Viel besser ist es, die Inhalte dieser Aussagen anzugeben, etwa "Die zentrale Hypothese lautet, dass X zu Y führt" oder "Es handelt sich um ein kontrolliertes, randomisiertes Experiment", "Im Anschluss wurden die Daten analysiert", "Die Literatur wurde anfangs gesichtet". Zugespitzt formuliert: Aussagen der Art "Diese Studie hat eine Hypothese" sind *inhaltsarm* und daher in einer wissenschaftlichen Arbeit fehl am Platz. In einer wissenschaftlichen Arbeit sollten Sie stets auf präzise, inhaltsdichte Formulierungen achten. Etwa "Diese Arbeit beruft sich auf Theorie XYZ, die besagt ABC", "Frauen parkten im Schnitt 10 Sekunden schneller ein als Männer", "Die zentrale Hypothese besagt, dass Lernen die Klausurnote erhöht".

- \- Die *Forschungsfrage* geht aus dem Abstract nicht (klar) genug hervor. Da die Forschungsfrage vermutlich der wichtigste Teil des bzw. die wichtigste Information zum wissenschaftlichen Berichts darstellt, sollte die Forschungsfrage auf jeden Fall klar formuliert werden. Ein Fehler der Forschungsfrage in diesem Sinne ist ein klarer Fehler.

- \- Der Abstract versäumt es, auf die *zugrundeliegende Theorie *(d.h. die Erklärung im Sinne von Ursachen und/oder Randbedingungen) der Forschungsfrage einzugehen. Forschungsfragen und/oder Hypothesen sollten aber nicht im "*luftleeren*" Raum stehen, sondern durch eine Theorie erklärt werden. Lautet zum Beispiel die Forschungsfrage "A führt zu B", so sollte eine Theorie herangezogen werden, um zu erklären, warum A zu B führt, unter welchen Umständen (Randbedingungen) A zu B führt oder vermittelt über welche Prozesse A zu B führt. Die Theorie zu detaillieren (und mit empirischen Belegen glaubhaft zu machen) ist dann Aufgabe des Theorieteils. Dieser Punkt wurde in der vorliegenden Arbeit nicht (ausführlich genug) berücksichtigt.

- \- Hinweise in der Diskussion oder im Abstract der Art *"weitere Forschung ist sinnvoll"*, "das Thema sollte weiter untersucht werden" etc. sind gering informativ; es gibt kaum eine Studie, bei der sich dieser Passus nicht anböte. Daher sollte dieser Hinweis unterbleiben bzw. (besser) durch eine *Präzisierung* der nun angeratenen Forschung ersetzt werden.



## Ethik (xxethik) {#ethik}

- \+ Ethische Aspekte in Bezug auf die Datenerhebung wurden diskutiert und angemessen umgesetzt.


`---`


- \- Ethische Aspekte in Bezug auf die Datenerhebung (wie Anonymität und Rechte der Versuchsperson) wurden *nicht (ausreichend)* oder nicht an der richtigen Stelle im Text diskutiert und/oder nicht angemessen umgesetzt.
- \- So wurde zwar in sinnvoller Weise auf Anonymität der Untersuchung eingegangen, allerdings fehlen weitere Hinweise wie Aufklärung der Versuchspersonen über Ziele und über etwaige Risiken und Nebenwirkungen der Teilnahme. Außerdem wären weitere Hinweise zum Datenschutz sinnvoll gewesen, fehlen aber.








## Rechtschreibung/Grammatik (xxrecht) {#rechtschreibung}

### Rechtschreibung/Grammatik -- Bewertung

`+++`


- \+ Die Rechtschreibung, die Interpunktion und der Satzbau sind tadellos.
- \+ Die Rechtschreibung, die Interpunktion und der Satzbau weisen wenig Fehler auf.
- \+ Die Rechtschreibung, die Interpunktion und der Satzbau sind fast fehlerfrei.
- \+ Die Orthografie ist weitgehend fehlerfrei.


- \+ Es finden sich nur wenig Rechtschreibefehler.

- \+ Orthografie und Interpunktion sind weitgehend fehlerfrei.
- \+ Orthografie und Interpunktion sind insgesamt in Ordnung.

`---`


- \- Einige Fehler in Orthografie und/oder Interpunktion sind vorhanden.
- \- Ein substanzielle Zahl an Fehlern in Orthografie und/oder Interpunktion ist vorhanden.
- \- Einige Fehler in der Rechtschreibung, vor allem in der Interpunktion, sind vorhanden.
- \- Einige Fehler in der Interpunktion sind vorhanden.
- \- Deutliche Fehler in der Interpunktion sind vorhanden.

- \- Die Grammatik bzw. der Satzbau weist deutliche Fehler auf.


### Rechtschreibung/Grammatik -- Kommentare {#rechtkommentare}

`---`


- \- Der Satzbau (Grammatik) ist teilweise *elliptisch*; es finden sich Sätze ohne Verben.
- \- Der + im Deutschen (und im Englischen) wird ohne *Apostroph* am S gebildet.
- \- Der *Genitiv* wird im Deutschen ohne *Apostroph* gebildet (nicht Cohen's d", sondern Cohens d, nicht Spearman's Korrelationstest, sondern Spearmans Test).
- \- *Fremdsprachige Wörter* oder Neologismen sollten nicht in Anführungsstriche gesetzt werden, sondern *kursiv* gedruckt werden (nicht: "predictive modeling", sondern \*predictive modeling\*).
- \- Ganze Sätze sollten immer mit einem Punkt beendet werden; das gilt auch für Aufzählungen.
- \- Die unterschiedliche Verwendung von **Bindestrich** (- kurz) und **Gedankenstrich**(-- lang) wurde nicht (immer) korrekt erkannt.
- \- Kein *Komma* vor "sowie" kommt, wenn "sowie" anstelle von "und" verwendet wird. 
- \- Verwendet man den *Schrägstrich* um (zusammengehörige) Wörter zu gruppieren (z.B. CSU/CDU, Männer und/oder Frauen,  Wintersemester 2016/2017), so sollte zwischen den Wörter kein Leerzeichen gelassen werden (Duden D 156). Auf keinen Fall sollte nur an einer Seite des Schrägstrichs ein Leerzeichen gelassen werden (falsch ist also: "CSU/CDU" oder "CSU /CDU").
- \- Formuliert man eine Frage, so muss diese mit einem Fragezeichen abschließen.


### Hinweise zu Komposita

+ \+  *Komposita*  (zusammengesetzte Nomen) wurden korrekt geschrieben, nämlich gekoppelt d.h. entweder mit Bindestrich oder in einem Wort (z. B. richtig: "Software-Standard", "R-Syntax", "Desktop-Publishing", "Influencer-Marketing", "BFI-Skala", "Between-Subject-Design" oder "Master-Thesis"; falsch: "R Befehl", "Multiple Choice Aufgabe" oder "Fugen Reiniger"). Es gilt die Regel: Wörter, die zusammen einen Begriff bilden, werden gemäß der geltenden Rechtschreibung entweder zusammengeschrieben oder es wird ein Bindestrich gesetzt.



`---`


- \- *Komposita*  (zusammengesetzte Nomen) werden im Deutschen zusammen- oder mit Bindestrich geschrieben -- aber nicht in einzeln Wörter aufgetrennt, was in der vorliegenden Arbeit nicht durchgehend beachtet wurde (z. B. richtig: "Software-Standard", "R-Syntax", "Desktop-Publishing", "Influencer-Marketing", "BFI-Skala", "Between-Subject-Design" oder "Master-Thesis"; falsch: "R Befehl", "Multiple Choice Aufgabe" oder "Fugen Reiniger"). Es gilt die Regel: Wörter, die zusammen einen Begriff bilden, werden gemäß der geltenden Rechtschreibung entweder zusammengeschrieben oder es wird ein Bindestrich gesetzt.

- \- *Koppelt* man Komposita  (zusammengesetzte Nomen) mit *Bindestrich*, so ist vor oder nach dem Bindestrich kein Leerzeichen zu setzen (richtig: "R-Syntax", falsch: "R - Syntax").



### Hinweise zu Fremdwörtern {#fremd}

`---`


- \- Wörter aus dem *Englischen* werden den *Rechtschreiberegeln des Deutschen* unterworfen. Besteht der Ausdruck aus zwei Substantiven, so wird zusammengeschrieben oder gekoppelt (d. h. mit Bindestrich geschrieben) also z. B. "Shoppingcenter" oder "Shopping-Center" ist korrekt, aber nicht "shopping center". Ist das erste Wort ein Adjektiv, so kann auch auseinander geschrieben werden, aber die Großschreibung ist auf jeden Fall zu verwenden: "Hot Spot", "Top Ten", "High Fidelity". Bei Verbindungen von Verb und Partikeln sind Zusammen- oder Bindestrichschreibweise möglich: "Hang-over" (nicht: "Hang over") oder "Blackout". Wird ein englisches Wort oder eine Wortgruppe mit deutschen Wörtern gekoppelt, so ist der Bindestrich zu verwenden: "Multiple-Choice-Aufgabe", "Add-on-Indikator".
- \- Die Rechtschreiberegeln von aus dem Englischen entlehnten Wörtern können z. B. hier nachgelesen werden: <https://www.duden.de/sprachwissen/sprachratgeber/Schreibung-von-Fremdwortern-aus-dem-Englischen>.


### Rechtschreibung -- Empfehlungen

- \> Eine große Zahl an Rechtschreibfehlern muss nicht sein; durch etwas Recherche, Übung und Sorgfalt lässt sich diese Fehlerquelle leicht in den Griff kriegen. Ich empfehle Ihnen, sich künftig gut mit der Orthographie Ihrer Texte auseinander zu setzen. Von einer guten Orthographie werden Sie vielfältig profitieren, nicht nur, aber auch in hohem Maße, in wissenschaftlichen Arbeiten. Nach meiner Erfahrung achten Gutachter sehr genau auf die Güte von Rechtschreibung und insbesondere auch Zeichensetzung. 

- \> Tipp: Gerade die Grundlagen der Kommasetzung lassen sich schnell lernen - ein halbes Dutzend einfacher Regeln klärt 95 % der Fälle. Es finden sich viele Hinweise dazu online, z.B. hier: https://www.duden.de/sprachwissen/rechtschreibregeln/komma.  

## Zitieren und Referenzieren  (xxzit) {#zitieren}

### Zitierweise im Text
#### Zitierweise im Text - Beurteilung

- \+ Die Zitationsweise im Text ist in hohem Maße konsistent und fehlerfrei.
- \+ Die Zitationsweise im Text ist insgesamt konsistent und fehlerfrei.
- \+ Die Zitationsweise im Text ist ist fast immer konsistent und fehlerfrei. Gleiches gilt für das Literaturverzeichnis.
- \+ Die Zitationsweise im Text ist ist insgesamt konsistent und fehlerfrei.
- \+ Die Zitationsweise im Text ist insgesamt gut.
Gleiches gilt für das Literaturverzeichnis.
- \+ Abbildungen und/oder Tabellen wurden korrekt referenziert (nach APA oder Hochschul-Richtlinien).


- \+- Die Zitationsweise im Text ist befriedigend bis gut.

`---`


- \- Die Zitationsweise im Text weist einige Fehler auf.
- \- Es findet sich eine substanzielle Zahl an Fehlern in den Zitationen im Text.
- \- An einigen Textstellen fehlen die Zitationen.
- \- Die Zitationsweise im Text weist eine große Zahl an Fehlern auf bzw. ist insgesamt von großen Mängeln gekennzeichnet.

#### Zitierweise im Text - Hinweise (zu Fehlern)


`+++`



- \+ Die APA empfiehlt, bei Zitaten von Büchern eine *Seitenzahl* anzugeben; das ist eine sinnvolle Praxis, auch wenn sie von vielen Autoren nicht berücksichtigt wird. Dies wurde in der vorliegenden Arbeit umgesetzt.
- \+ Laut APA sind Quellen mit *3-5 Autoren ab dem zweiten Zitieren* in der Form "Erstautor et al. (Jahr)" zu zitieren. Diese Regel wurde in der vorliegenden Arbeit beachtet, was auf eine hohe Durchdringung der formalen Regeln des Zitierens hindeutet.

`---`


- \- Der Zitationsstil der APA sieht vor, dass* Zitationen im Text vor dem Punkt*, der das Satzende markiert, eingefügt werden: "Eile mit Weile (Weiss-Ois, 2017)". Falsch ist: "Eile mit Weile. Weiss-Ois (2017)".
- \- *Direkte* Zitate müssen (laut APA) mit *Seitenzahlen* versehen sein; dass wurde in der vorliegenden Arbeit nicht (durchgehend) berücksichtigt.
- \- Auslassungen zu Beginn eines direkten Zitats brauchen (sollen) nicht durch explizite Auslassungszeichen markiert werden.
- \- Es finden sich einige oder mehrere Zitationsfehler der Art "(Bond, J., 2007)". Nach den anzuwendenden Zitierregeln sind keine Vornamen bzw. deren Anfangsbuchstaben bzw. Initialen anzuführen. Gewöhnlich liegt dieser Fehler darin begründet, dass in der *Literaturdatenbank mehrere Varianten des Autorennamens* vorhanden sind (z. B. "Bond, J.", "Bond, James" und "Bond, James J."). In diesem Fall versucht die Literatursoftware diese verschiedenen Namen im Text kenntlich zu machen (zu disambiguieren). Das wäre korrekt, wenn es sich tatsächlich um verschiedene Autoren handelte; dies ist aber vermutlich nicht der Fall in der vorliegenden Arbeit. Es handelt sich stattdessen um inkorrektes Einpflegen der Autorennamen in die Literaturdatenbank.
- \- *Akademische Titel sind nicht in Zitationen* (oder überhaupt) im Text anzuführen. Diese Regel wurde in der vorliegenden Arbeit nicht durchgängig berücksichtigt. Man schreibe besser nicht : "Prof. Dr. Feistersack bewies mit seiner Interview-Studie blablabla"; auch nicht "Bla bla bla (Prof. Dr. Feistersack, 2018)". Diese Regel gilt auch für das Literaturverzeichnis.
- \- Das Zitieren elektronischer Quellen kann z. B. hier überblickt werden: <https://owl.english.purdue.edu/owl/resource/560/10/>.
- \- Diese Zitationsweise ist falsch: "Schon Bandura (Bandura, 2012) blablabla"; richtig wäre: "Schon Bandura (2012) blablabla". Dieser Fehler findet sich in der vorliegenden Arbeit.
- \- Zitiert man zwei Arbeiten, so ist diese Zitationsweise (laut APA) falsch: "Eile mit Weile (Weiss, 2017) (Ois, 2015)"; richtig ist: "Eile mit Weile (Weis, 2017; Ois, 2015)". Diese Regel wurde in der vorliegenden Arbeit nicht durchgehend berücksichtigt.
- \- Es finden sich *schwere Zitationsfehler*: In mehrfacher Weise wurden Textstelle direkt zitiert, aber nur als indirektes Zitat - und damit als eigener Wortlaut - ausgegeben. Die Unschuldsvermutung wird hier angewandt; ein Plagiatsvorwurf wird in diesem Fall nicht erhoben.
- \- Die Arbeit macht übermäßigen Gebrauch von *direkten Zitaten*, so dass die Eigenständigkeit der Leistung dadurch gemindert erscheint bzw. in Zweifel zu ziehen ist.
- \- Angelehnt an die Vorgaben der APA sind Abbildungen in folgendem Format zu zitieren: *Eigene Darstellung angelehnt an "Titel des Artikels", von A. Autor und B.C. Autor, Jahr, Name der Zeitschrift, Ausgabe, Seite. Copyright Jahr American Psychologisch Association.*
- \- Laut APA ist diese Art des Zitierens falsch "Sauer & Lustig (2018) schreiben blablabla"; richtig wäre "Sauer und Lustig (2018) schreiben blablabla". Hingegen wäre es korrekt zu schreiben "Die Antwort lautet 42 (Sauer & Lustig, 2018)". Im Text ist bei einer Zitation also nicht das "*Ampersand*" (&-Zeichen) zu verwenden, sondern das ausgeschriebene Wort "und". In der Klammer einer Zitation verhält es sich umgekehrt. In der vorliegenden Arbeit wird dies nicht (durchgängig) korrekt umgesetzt.

- \- Initialen oder Vornamen sind i. A. nicht zu zitieren laut APA/DGPs; falsch: "Wie H. Durven (2009) schreibt...", richtig: "Wie Durven (2009) schreibt...". Eine Ausnahme von dieser Regel ist, wenn ohne das Initial mehrere Autoren für die Zitation in Frage kämen (z. B. Heiner Durven und Heidi Durven).


- \- Es werden Quellen im Text zitiert, die sich nicht im Literaturverzeichnis finden (oder umgekehrt).

- \- *Auslassungszeichen* ("...") zu *Beginn* eines Zitates sind laut APA nur dann nötig, wenn das Weglassen den Sinn des Zitats entstellen würde. Im Allgemeinen kann hier auf Auslassungszeichen verzichtet werden. 

- \- Am *Ende* eines Zitates kann laut APA auf Auslassungszeichen ("...") verzichtet werden; man muss nicht kenntlich machen, dass der Satz im Original noch weitergehen, sofern keine Sinnentstellung zu befürchten ist.



### Literaturverzeichnis (xxlitverz) {#litverzzitieren}

#### Literaturverzeichnis - Beurteilung

`+++`

- \+ Das Literaturverzeichnis enthält kaum/keine Fehler.
- \+ Das Literaturverzeichnis ist formal als gut bis sehr gut zu bewerten.
- \+ Das Literaturverzeichnis enthält wenig Fehler.

`---`


- \- Es finden sich einige Fehler im Literaturverzeichnis (z. B. bei Herausgeber-Werken oder beim Ort des Verlags).
- \- Es finden sich eine substanzielle Zahl an Fehlern im Literaturverzeichnis (z. B. bei Herausgeber-Werken oder beim Ort des Verlags).


- \- Das Literaturverzeichnis enthält eine große Zahl oder einen großen Anteil an Fehlern.
- \- Jede oder fast jede Quelle im Literaturverzeichnis ist falsch zitiert. Das ist als gravierender Mangel der vorliegenden Arbeit zu sehen.


- \- Es werden Quellen im Text zitiert, die sich nicht im Literaturverzeichnis finden (oder umgekehrt).






#### Literaturverzeichnis - Kommentare/Hinweise zu Fehlern

`+++`

- \+ *DOIs* wurden berichtet, was nicht nur den Vorgaben der APA entspricht, sondern eine hilfreiche Ergänzung zur Identifikation von Literatur darstellt.
- \+ Schön ist, dass *URLs* im Literaturverzeichnis am Zeilenende *getrennt/umgebrochen* wurden, um hässliche Lücken im Textsatz zu vermeiden. Häufig wird das vernachlässigt.
- \+ Es ist positiv anzumerken, dass *Verlagsnamen* in der von der APA vorgeschlagenen Form berichtet wurden (nämlich "Heidelberg: Springer." anstelle von z.B. "Berlin, Heidelberg: Springer Medien Verlag.").

`---`


- \- *DOIs* wurden nicht (durchgehend) berichtet, sind aber eine sinnvolle Ergänzung in Zitationen.

- \- Auch bei Werken von Google Books ist Autor, Verlag etc. im Literaturverzeichnis aufzuführen.
- \- *NN-Zitierungen* (ohne Angabe des Autors) sollten vermieden werden.
- \- *Internetquellen* sollten - wie jede Quelle - mit Namen des Autors und dem Erscheinungsjahr zitiert werden.
- \- *Online-Fachzeitschriften* sind *nicht* als *Internetquelle*, sondern als Fachzeitschrift zu führen, da sie alle Vorgaben einer Fachzeitschrift erfüllen und letztere die stärkere Quellenart darstellt.
- \- Im *Literaturverzeichnis* finden sich *nicht zitierte Quellen*, was als deutlicher formaler Fehler zu werten ist.  
- \- *Akademische Grade sind nicht anzuführen* (dies gilt auch für das Literaturverzeichnis).
- \- Es ist nach APA nur ein Literaturverzeichnis für alle Arten von Quellen zu erstellen, nicht mehrere Verzeichnisse. Dies wurde in der vorliegenden Arbeit nicht beachtet.
- \- *Typische Fehler in Literaturverzeichnissen* beinhalten das Auslassen des Verlagortes, der Seitenzahl, falsche Groß- und Kleinschreibung, falsche Darstellung von Kapiteln in Herausgeberwerken. 
- \- Im Literaturverzeichnis sind *genau die zitierten Literaturstellen anzuführen (nicht mehr, nicht weniger)*. Es sollen keine nicht-zitierten Werke im Literaturverzeichnis erscheinen; es sollen keine zitierten Werke nicht im Literaturverzeichnis erscheinen. Die vorliegende Arbeit hält dies nicht ein.
- \- Laut den Richtlinien zur Manuskriptgestaltung der DGPs (2016) wird die *"Heftnummer nur dann,* wenn die Paginierung jedes Heftes mit der Seitenzahl Eins beginnt, unmittelbar nach der Bandangabe in Klammern (im Literaturverzeichnis() hinzugefügt" (S. 116).
- \- Bei der Zitation von Kapiteln aus Herausgeberwerken im Literaturverzeichnis sind die Editoren zu benennen; das wurde in der vorliegenden Arbeit nicht (durchgehend) berücksichtigt.

- \- Laut APA/DGPs ist  ein *Verlag* im Literaturverzeichnis nur kurz als z. B. "Thieme" oder "Hogrefe" aufzuführen, nicht aber als z. B. "Karl F. Haug Verlag" etc.

- \-  Laut APA/DGPs ist im Literaturverzeichnis bei der Zitation eines Buches nur *ein Ort* (der zuerst genannte im Quellmaterial) anzugeben, nicht mehrere, also z. B. "Heidelberg: Springer".

- \- Laut APA/DPGs ist ab der zweiten Zeile einer Zitation im Literaturverzeichnis einzurücken (5-7 Leerzeichen; *"hängender Einzug"*). Das wurde in der vorliegenden Arbeit nicht berücksichtigt.

- \- Laut APA/DGPs sind *Seitenzahlen* im Literaturverzeichnis bei Monografien nicht anzugeben; bei *Buchkapiteln* aus Herausgeberwerken, bei Zeitschriftenartikeln oder Zeitungsartikeln hingegen schon. Dieser Unterscheidung wird in der vorliegenden Arbeit nicht durchgehen korrekt getroffen.

- \- Laut APA/DGPs ist im Literaturverzeichnis die *Abkürzung "S." für Seite* (bzw. "p") nicht bei Fachartikeln anzugeben; bei Buchkapiteln aus Herausgeberwerken oder bei Zeitungsartikeln hingegen schon. Dieser Unterscheidung wird in der vorliegenden Arbeit nicht durchgehen korrekt getroffen.

- \- Laut APA (6. Auflage) ist das *Abrufdatum einer Online-Quelle* nicht zu nennen. Gerade bei einem nachprüfbaren Publikation wie einem Fachartikel spielt das Abrufdatum keine Rolle (genauso wenig wie das Ausleihdatum eines gedruckten Buches aus einer Bücherei von Relevanz ist).

- \- Laut APA (6. Auflage) sind in der Zitation im *Literatverzeichnis* beim Titel (neben dem ersten Wort) *nur Eigennamen großzuschreiben*. Beispiel: "Tu, H.-W., & Hampton, R. R. (2014). Control of working memory in rhesus monkeys (Macaca mulatta). *Journal of Experimental Psychology: Animal Learning and Cognition, 40*, 467–476. http://dx.doi.org/10.1037/xan0000030".

- \- Das Literaturverzeichnis ist mit "Literaturverzeichnis" (formatiert als Titel) zu überschreiben, aber *nicht zu nummerieren*.


#### Literaturverzeichnis - Beispiele/Blaupausen von Zitaten nach Typen

`---`


- \- Beispiele für korrekte Zitationen (laut APA/DGPs) für *Monografien* sind die Folgenden (Kursivdruck ist durch Sternchen gekennzeichnet): 

  - American Psychological Association. (2010). *\Publication manual of the American Psychological Association\* (6th ed.). Washington, DC: Author.
  
  - Bredenkamp, J. (1972). *Der Signifikanztest in der psychologischen Forschung*. Frankfurt am Main: Akademische Verlagsgesellschaft.
  
  - Cohen, J. (1988). *\Statistical power analysis for the behaviaral sciences\* (2nd ed.). Hillsdale, NJ: Erlbaum.
  

- \- Beispiele für korrekte Zitationen (laut APA/DGPs) für *Zeitschriftenartikel* sind die Folgenden (Kursivdruck ist durch Sternchen gekennzeichnet): 

  - Gschwendner, T., Hofmann, W. & Schmitt, M. (2006). Moderatoren der Konsistenz implizit und explizit erfasster Einstellungen und Persönlichkeitsmerkmale. \*Psychologische Rundschau\*, 57, 13–33. http://dx.doi.org/10.1026/0033-3042.57.1
  
  - Keselman, H. J., Huberty, C. J., Lix, L. L., Olejnik, S., Cribbie, R. A., Donohue, B. et al. (1998). Statistical practices of educational researchers: An analysis of their ANOVA, MANOVA, and ANCOVA analyses. \*Review of Educational Research, 68\*, 350–386.
  
  
- \- Beispiele für korrekte Zitationen (laut APA/DGPs) für *Buchkapitel* (d.h. Beiträge aus Herausgeberwerken) sind die Folgenden (Kursivdruck ist durch Sternchen gekennzeichnet):

  - Döbert, F. & Nunner-Winkler, G. (1984). Abwehr- und Bewältigungsprozesse in normalen und kritischen Lebenssituationen. In E. Olbrich & E. Todt (Hrsg.), \*Probleme des Jugendalters. Neuere Sichtweisen \*(S. 259–295). Berlin: Springer.
  - Bem, D. J. (2004). Writing the empirical journal article. In J. M. Darley, M  P. Zanna & H. L. Roediger III (Eds.), \*The compleat academic: A career guide. 2nd ed.\*(pp. 185–219). Washington, DC: American Psychological Association. http://dx.doi.org/10.1017/cbo9780511807862.002
  
  
- \- Beispiele für korrekte Zitationen (laut APA/DGPs) von *elektronischen Dokumenten* (inkl. Webseiten) sind die Folgenden (Kursivdruck ist durch Sternchen gekennzeichnet):
  
  - Autor, A. A. & Autor B. B. (Jahr). Titel [ggf. Art des Formats, z.B. PDF-Datei]. Retrieved from https://www.someaddress.com/full/url/
  
  - Spotlight Resources. (n.d.). Retrieved from https://owl.purdue.edu/owl/about_the_owl/owl_information/spotlight_resources.html (Das ist ein Beispiel, in dem Autor und Datum der zitierten Ressource unbekannt sind)
  
  - U.S. Department of Health and Human Services, National Health Statistics Reports. (2008). \*National health statistics reports: Complementary and alternative medicine use among adults and children: United States, 2007\* (Report No. 12). Retrieved from https://nccam.nih.gove/sites/nccam.nih.gove/files/news/nhsr12.pdf
  
  - Kessy, S.S.A. & Urio, F.M. (2006). \*The contribution of microfinance institutions to poverty reduction in Tanzania\* (Research Report No. 06.3). Retrieved from Research on Poverty alleviation website: http://www.repoa.or.tz/documents_storage/Publications/Reports/06.3_Kessy_and_Urio.pdf


#### Literaturverzeichnis - Empfehlungen

- \> Ich empfehle Ihnen, sich intensiv mit der Gestaltung eines Literaturverzeichnisses auseinander zu setzen: In jeder Seminararbeit und in Ihrer Abschlussarbeit wird das Thema eine große Rolle spielen. Nach meiner Erfahrung achten Gutachter sehr auf die formale Korrektheit des Zitieren und speziell des Literaturverzeichnisses. Wenn Sie einmal (und frühzeitig) die Regeln lernen, so werden Sie in jeder Arbeit davon profitieren und umgekehrt.


### Vorgaben zum Zitationsstil

- \+ Die Zitationsvorgaben (APA/DGPs) wurden  umgesetzt, entsprechend den formalen Vorgaben.

- \- Die Zitationsvorgaben (APA/DGPs) wurden nicht vollständig umgesetzt, entgegen formaler Vorgaben.
- \- Die Zitationsvorgaben (APA/DGPs) wurden kaum oder gar nicht umgesetzt, entgegen formaler Vorgaben.

- \- Seitenzahlen werden im APA-Format nur in wörtlichen Zitaten verwendet, nicht in indirekten.
- \- Direkte Zitate sind stets mit Seitenangaben zu versehen (z. B. "S. 5"").

- \- Das Literaturverzeichnis wurde nicht (durchgängig) nach APA formatiert, entgegen formaler Vorgaben.


### Referenzieren (xxref) {#referenzieren}

`+++`

- \+ Tabellen und/oder Abbildungen wurden korrekt im Text *referenziert.*
- \+ Tabellen und/oder Abbildungen wurden korrekt *beschriftet* (z. B. die Beschriftungen einer Abbildung unterhalb der Abbildung aber die Beschriftung einer Tabelle oberhalb der Tabelle).


`---`



- \- Tabellen und Abbildungen müssen im Text referenziert werden ("wie in Tabelle 1 dargestellt"); dies ist in der vorliegenden Arbeit nicht (durchgehend) der Fall.




- \- Abbildungen und/oder Tabellen wurden nicht oder nicht (durchgehend) korrekt *referenziert* (nach APA oder Hochschul-Richtlinien). Bitte konsultieren Sie die entsprechenden Hinweise (z. B. wie beschriftet man Tabellen, wie ist die Legende von Abbildungen zu gestalten).

- \- Laut APA/DGPs sind Referenzen \*unter\* Abbildungen anzubringen; bei Tabellen gilt hingegen Umgekehrtes. Dort ist die Beschriftung \*oberhalb* der Tabelle anzubringen. Die vorliegende Arbeit berücksichtigt dies nicht (durchgehend).

- \- Laut Richtlinien der APA/DGPs ist der Titel einer Abbildung direkt nach der Nummerierung ohne Zeilenumbruch anzugeben.






## Diagramme/Abbildungen {#diagramme}



### Schemata/Ablauf-Diagramme

- \+ Diagramme, Bilder oder Schemata wurden sinnvoll zur Auflockerung und Verdeutlichung des Textes bzw. der theoretischen Grundlagen verwendet.



- \+- Einige (wenige) Diagramme wurden zur sinnvollen Auflockerung und besserer Veranschaulichung des Textes eingesetzt. Mehr Diagramme hätten die Ausarbeitung bereichern können.



`---`


- \- Es wurden keine oder fast keine Diagramme bzw. Schemata zur Auflockerung und Verdeutlichung des theoretischen Teils verwendet, obwohl dies zweckdienlich gewesen wäre.

- \- Laut Formatvorgaben der APA ist die Beschriftung einer Abbildung unter der Abbildung anzubringen. In der vorliegenden Arbeit wurde dies nicht (durchgehend) korrekt umgesetzt.
- \- Laut Formatvorgaben der APA ist die Beschriftung einer Abbildung in dieser Form anzubringen: "*Abbildung X*. Titel der Abbildung.", wobei "Abbildung X" kursiv zu setzen ist. In der vorliegenden Arbeit wurde dies nicht (durchgehend) korrekt umgesetzt.
- \- Es fehlen die Quellenangaben für einige Abbildungen; wie für jedes geistiges Material gilt, dass der Autor zu zitieren ist. Übernimmt man fremde Gedanken, ohne dies zu zitieren, so ist dies heikel (aber im diesem Fall klar nicht als Plagiat zu bewerten, sondern nur als Formfehler).

- \- Abbildungen sollten sich stets durch hohe Informationsdichte auszeichnen. Als Faustregel kann gelten, dass, wenn man eine Abbildung genauso gut in ein paar wenigen Worten oder Sätzen sagen, die Abbildung überflüssig oder nicht richtig genutzt ist; zumindest gilt dies für alle Dokumente mit ernsthaftem Anspruch wie wissenschaftliche Berichte. Inhaltsarme Abbildungen sind wenig nützlich; Abbildungen sollten im Gegensatz dazu den Text (die Wörter) bereichern und insofern zu vertieften Einsichten führen. "Flache" Abbildungen stiften insofern wenig Nutzen.



## Poster


### Übersichtlichkeit

- \+ Das Poster ist übersichtlich gestaltet.

- \+- Das Poster ist nicht immer übersichtlich gestaltet.

- \- Das Poster ist nicht übersichtlich gestaltet.


- \- Bei einem Poster sollten die einzelnen Teile -- wie Einleitung oder Methoden -- optisch gut voneinander getrennt werden. Häufig erreicht man das durch Farbgebung (z. B. jeder Abschnitt wird in einer Box mit grauem Hintergrund dargestellt; zwischen den Boxen liegt Weißraum). Diese optische Abtrennung der einzelnen Teile ist in der vorliegenden Arbeit nicht gut gelungen.
- \- Die Reihenfolge der Positionierung der Abschnitte auf dem Poster entspricht nicht dem Lesefluss. So ist z. B. die Diskussion unten rechts zu positionieren, da dies das Ende des natürlichen Leseflusses darstellt.

### Vollständigkeit

- \+ Das Poster ist vollständig insofern als dass die wesentlichen Aspekte einer Studie (Einleitung, Theorie, Methode, Ergebnisse, Diskussion, Literatur) aufgeführt sind.
- \- Das Poster ist unvollständig insofern als dass die wesentlichen Aspekte einer Studie (Einleitung, Theorie, Methode, Ergebnisse, Diskussion, Literatur) nicht im erforderlichen Umfang aufgeführt sind.


### Platznutzung

- \+ Der (knappe) Platz auf dem Poster wurde sinnvoll genutzt.
- \- Der (knappe) Platz auf dem Poster wurde nicht immer sinnvoll genutzt; z. B. wurde Platz verschenkt.


<!-- ## Podcast -->

<!-- ### Allgemein -->
<!-- - \+ Insgesamt ist der Podcast formal (inkl. stilistisch), methodisch und inhaltlich sehr gut erstellt. -->
<!-- - \+ Insgesamt ist der Podcast formal (inkl. stilistisch), methodisch und inhaltlich gut erstellt. -->

<!-- - \+- Insgesamt ist der Podcast formal (inkl. stilistisch), methodisch und inhaltlich befriedigend erstellt. -->

<!-- - \- Insgesamt ist der Podcast formal (inkl. stilistisch), methodisch und inhaltlich als ausreichend zu bewerten. -->
<!-- - \- Insgesamt ist der Podcast formal (inkl. stilistisch), methodisch und inhaltlich als mangelhaft zu bewerten. -->


<!-- ### Sprechweise - Bewertung -->

<!-- - \+ Insgesamt ist die Sprechweise sehr klar, deutlich und wohl artikuliert. -->
<!-- - \+ Insgesamt ist die Sprechweise insgesamt klar, deutlich und wohl artikuliert. -->

<!-- - \+- Insgesamt ist die Sprechweise nicht immer klar, deutlich und wohl artikuliert. -->

<!-- - \- Insgesamt ist die Sprechweise nicht immer klar, deutlich und wohl artikuliert. -->


<!-- ### Sprechweise - Kommentare -->

<!-- - \- Intonation und Prosodie würden von mehr Variabilität profitieren. -->
<!-- - \- Die Geschwindigkeit der Sprechweise hätte von mehr Variabilität profitiert. -->
<!-- - \- Fragen sollten als Fragen intoniert werden (Stimme geht hoch zum Satzabschluss). -->
<!-- - \- Eine Reihe von Versprechern liegt vor. -->
<!-- - \- Einige Wörter wurden zu oft und/oder in zu kurzem Abstand wiederholt (z. B. "hierbei"). -->


<!-- ### Tonaufnahme -->
<!-- - \+ Insgesamt ist die akustische Qualität des Podcasts als sehr gut einzuschätzen. -->
<!-- - \+ Insgesamt ist die akustische Qualität des Podcasts als gut einzuschätzen. -->

<!-- - \+- Insgesamt ist die akustische Qualität des Podcasts als befriedigend einzuschätzen. -->
<!-- - \- Insgesamt ist die akustische Qualität des Podcasts als ausreichend einzuschätzen. -->






# METHODEN (**xxmeth**) --------------------------------------- {#methoden}


## Reproduzierbarkeit (xxrepro) {#repro}

### Literaturrecherche
- \+ Das Vorgehen bei der Literaturrecherche wurde gut geschildert; das unterstützt die Nachvollziehbarkeit der Ergebnisse in sinnvoller Weise.

- \- Eine Explikation der Recherchestrategie/der Literaturrecherche wäre sinnvoll gewesen, da so die Belastbarkeit der Quellen (und damit der Aussagen der Arbeit) besser eingeschätzt werden kann. Dies würde z. B. Suchbegriffe und Suchzeitraum umfassen sowie die Anzahl der Treffer.





### Daten
- \+ Die Daten der Studie wurden eingereicht, was Transparenz/Reproduzierbarkeit der Studie sinnvoll unterstützt.


`---`


- \- Rohdaten wurden *nicht* eingereicht; das reduziert die Nachvollziehbarkeit und Transparenz ("Reproduzierbarkeit") der Ergebnisse, was nachteilig ist.
- \- Die Daten wurden nicht in maschinenlesbarer Form eingereicht.

### Syntax

`+++`

- \+ Die (R-)Syntax wurde eingereicht, das unterstützt die Reproduzierbarkeit der Arbeit und stärkt insofern einen zentralen wissenschaftsethischen Anspruch an Studien.

- \+ Die Syntax ist wohlstrukturiert (z. B. übersichtlich und kommentiert), was die Reproduzierbarkeit unterstützt. 


`---`


- \- Die *Syntax* zur Datenanalyse der Studie wurde *nicht* eingereicht, was Transparenz/Reproduzierbarkeit der Studie leider verringert.
- \- Die Syntax *sollte nicht im Hauptteil* der Studie berichtet werden, sondern im Anhang (oder im Rahmen einer separaten Datei).
- \- Die Syntax ist *wenig strukturiert *(z. B. nicht übersichtlich und/oder nicht kommentiert), was die Reproduzierbarkeit verringert. 


### Stimuli

`+++`

- \+ Die Stimuli bzw. Messinstrumente (z. B. Fragebogen oder Interviewleitfaden) *wurden eingereicht*, das unterstützt die Reproduzierbarkeit der Arbeit und stärkt insofern einen zentralen wissenschaftsethischen Anspruch an Studien.
- \+ Die Syntax ist in hohem Maße *übersichtlich* und stringent aufgebaut.



`---`


- \- Die Stimuli (z. B. Fragebogen) der Studie wurden *nicht* eingereicht, was die Transparenz/Reproduzierbarkeit der Studie leider schmälert.
- \+ Die *Syntax* ist in *wenig übersichtlich* und stringent aufgebaut.


### Fazit

- \+ Die *Reproduzierbarkeit* ist *insgesamt* in gutem Maße *sichergestellt*, da relevantes Material eingereicht wurde (z. B. Daten, Stimuli, Syntax).



`---`



- \- Die Reproduzierbarkeit ist insofern* nicht sichergestellt*, als dass einer oder mehrere der folgenden Teile nicht eingereicht wurden: Daten, Syntax, Stimuli, sonstiges Material. Reproduzierbarkeit ist die Grundlage oder Bedingung von Transparenz. Transparenz ist ein oder der Grundwert der Wissenschaft.


- \- Die Datei mit den Materialien zur Reproduzierbarkeit *ließ sich nicht öffnen*. Damit/Insofern ist die Reproduzierbarkeit nicht gegeben. Es obliegt dem Autor, die technische Funktionstüchtigkeit sicherzustellen.
- \- Daten brauchen nicht abgedruckt werden, da die Daten nur genutzt werden könnten, wenn man Zeit und Muse hat, diese herauszukopieren oder gar abzutippen (bei Screenshots).





## Design der Studie (xxdesign) {#studiendesign}




### Interne Validität des Designs (xxintval)

- \+ Das Design zeichnet sich durch hohe interne Validität aus.


`---`


- \+- Das Design zeichnet sich weder durch eine besonders hohe, noch durch eine in besonderem Maße eingeschränkte interne Validität aus (z. B. querschnittliche Korrelationsstudie).

- \- Das Design zeichnet sich durch *geringe* interne Validität aus.






### Anspruch des Designs



`+++`


- \+ Der Versuchsaufbau ist geschickt und *handwerklich* *hervorragend* umgesetzt.
- \+ Der Versuchsaufbau ist *"handwerklich" gut* gestaltet.
- \+ Es wurde eine *Pilotstudie* durchgeführt, was zur Güte des Designs (potenziell) beiträgt.




`++--`




- \+- Das Design der Studie ist von *mittlerer (befriedigender) Komplexität oder Güte*.



`---`

- \- Die *methodische Raffinesse* des Versuchsplan ist eher *einfach/gering*.
- \- Das *Versuchsdesign* zeichnet sich durch einen eher geringen Umfang oder eine *eher geringe Komplexität* aus (z. B. nur zwei Variablen in einer Zusammenhangshypothese).
- \- Die Versuchsplanung zeugt nicht von einer hohen Einarbeitung mit dem Gegenstand.



### Dokumentation des Designs/des Ablaufs 

`+++`

- \+ Das *Studiendesign* bzw. der -ablauf wurde in guter Weise stringent und konzise berichtet.
- \+ Das Studiendesign bzw. der -ablauf wurde nachvollziehbar berichtet. 
- \+ *UV und AV* (bzw. Prädiktoren und Kriterium) wurden expliziert.
- \+ Es wurde eine *Visualisierung*  (z. B. als "Flowchart") des Versuchsablauf dargeboten, was die Verständlichkeit erhöht.
- \+ Der *Ablauf* des Versuchs (aus Sicht der Versuchspersonen) wurde nachvollziehbar (und damit reproduzierbar) *geschildert.*

`---`


- \+- Der *Ablauf bzw. das Design* der Studie wurde in einigen Aspekten beschrieben, aber eine genauere Beschreibung wäre sinnvoll gewesen.
- \+- Es wurden einige Hinweise zum Ablauf bzw. Setting der Studie gegeben.



- \- Das Design der Studie wurde nicht oder nicht ausführlich oder nicht korrekt berichtet (z. B. ob es um ein querschnittliches Experiment handelt mit einer UV oder um eine Beobachtungsstudie).
- \- UVs und AVs wurden nicht expliziert, bzw. Prädiktoren und Kriterium wurden nicht expliziert.


- \- Die Darstellung des empirischen Vorgehens (Studiendesign) weist große Lücken auf; die Darstellung lässt Wesentliches außen vor. Insgesamt ist dieser Teil als mangelhaft einzustufen.
- \- Der Ablauf der Studie (z. B. Intervention, Messung, Instruktionen) wurde unzureichend genau beschrieben.
- \- Das empirisch-methodisch Vorgehen wurde zu knapp oder gar nicht beschrieben (z. B. Mit welcher R-Funktion wurde die Power durchgeführt)?


- \- Eine prägnante Beschreibung des Studienablaufs (z.B. in Form eines Ablaufdiagramms) wäre von Nutzen gewesen (z.B.: 1. Informierte Einwilligung; 2. Demografische Daten; 3. Fragebogen 1; 4. Fragebogen 2 etc.).
- \- Eine Visualisierung oder konzise Zusammenfassung (z. B. als "Flowchart") des Versuchsablauf wäre hilfreich gewesen, fehlt aber.




NUR QUALI:

- \- Die Durchführung bzw. das Setting der Studie sowie mögliche *Interaktionen* von Forschendem/r und Forschungssubjekten hätte stärker thematisiert werden können. Könnten existierende Sym- oder Antipathien die Interaktion in eine bestimmte Richtung beeinflusst haben? Welches Vorwissen und Thesen (Meinungen) vertrat der oder die Forschende, welche implizit eingingen? Was waren die Erwartungen aller Beteiligten und wie wirkten sich diese auf den Verlauf der Untersuchung aus? Etc.


### Maßnahmen zur Sicherstellung der internen Validität
- \+ Der Erfolg der experimentellen Intervention wurde geprüft (*"Manipulation Check"*).
- \+ *Störvariablen* wurden reflektiert, identifiziert und (in Teilen) kontrolliert.
- \+ Es wurde auf K*ontrolle von Störvarianz* geachtet, um die interne Validität nicht (unnötig) einzuschränken.
- \+ Der reibungslose Ablauf der Datenerhebung wurde vor der eigentlichen Erhebung getestet (*"Prätest", "Pilot"*) - eine sinnvolle Maßnahme, um die interne Validität der Studie zu sichern.


`++--`

- \+- Die Studie hätte von einer stärkeren Kontrolle von Störvariablen profitiert.


`---`


- \- Es wurde nicht (ausreichend) auf Kontrolle von Störvarianz geachtet, die die interne Validität gefährden könnte.


- \- Die Studie hätte von mehr Maßnahmen zur Sicherung der Datenqualität (und der internen Validität) profitiert. Einige hilfreiche Maßnahmen sind: (a) Kontrolle, dass die Versuchspersonen in Ruhe und ohne Ablenkung an der Studie teilnehmen; (b) Kontrolle, dass die Versuchspersonen alle in ähnlicher Stimmung/Verfassung sind; (c) Kontrolle der Dauer des Versuchs pro Versuchsperson, (d) Kontrolle störender Umwelteinflüsse (z. B. Lärm), (e) Kontrolle personengebundener Störeinflüsse (z. B. Vorwissen).



NUR QUALI:

  
- \- Es wäre für die Validität der Studie nützlich gewesen, dass Vorwissen, Beziehung und/oder das Setting der Untersuchung genauer zu erläutern. Gerade qualitative Forschung ist sich einer Wechselwirkung von Forschungssubjekt und -objekt ausgesetzt - und gerade qualitative Forschung ist sich (und sollte sich) dieser Wechselwirkung besonders bewusst sein.


## Messinstrumente (xxmess) {#measurement}

`+++`

- \+ Es wurden *geeignete Messinstrumente* ausgewählt.

- \+ Die Messinstrumente wurden präzise benannt und beschrieben.


- \+ Die *Qualität* der Messinstrumente *wurde methodisch geschickt untersucht*.
- \+ Zentrale *Gütekriterien* der Messinstrumente (wie interne Konsistenz gemessen an *Cronbachs Alpha*) wurden *berichtet.*
- \+ Es wurden *Messinstrumente mit gut belegter Qualität* verwendet.
- \+ *Einige zentrale Informationen zur Güte* der verwendeten Messinstrumente wurden berichtet.
- \+ Die Qualität der Messinstrumente erscheint gut bzw. die empirische Absicherung der Messinstrumente ist hoch.
- \+ Die Verwendung der "weiß nicht" bzw. "keine Angabe" Kategorie in Fragebögen ist sinnvoll gewählt.


`---`


- \- Es ist nicht klar (genug) ersichtlich aus dem Text, *ob und inwieweit geeignete Messinstrumente ausgewählt* wurden.

- \- Die *verwendeten Messinstrumente wurden nicht (in ausreichendem Maße) erläutert*. Messung ist jedoch für jede empirische Forschung ein Grundstein; daher sollte diesem Punkt immer Aufmerksamkeit zuerteilt werden.
- \- Es *fehlen Hinweise zu den Gütekriterien* der Messinstrumente.

- \- Es fehlen Hinweisen zur *internen Konsistenz* (z. B. Cronbachs Alpha) der verwendeten Messinstrumente.

- \- Es *wurden Messinstrumente mit unklarer oder zweifelhafter Güte* verwendet. Ohne sichere Messinstrumente ist es unsicher, Effekte zu finden, selbst wenn die Theorie richtig ist. Überlegen Sie: Angenommen Ihre Waage ist kaputt und zeigt wirre Zahlen an. Könnten Sie erwarten, die Hypothese "Männer sind im Schnitt schwerer als Frauen" zu bestätigen. Wie aussichtsreich und wie sinnvoll wäre eine Studie mit einem solchen unsicheren Messinstrument? 
- \- Die Verwendung von Messinstrumenten von zweifelhaftem Wert *zeugt nicht von Verständnis der Grundfesten* der empirischen Forschung.

- \- Die *Darstellung der Messinstrumente ist nicht präzise und detailliert genug*; die Ausführung bleibt zu vage.

- \- Werden psychologische Konstrukte gemessen, so *bedarf es i.d.R. validierter Messinstrumente* zur Operationalisierung. Diesem Sachverhalt wurde in der vorliegenden Arbeit nicht ausreichen Rechnung getragen.

- \- Die Messinstrumente sollten in einem *eigenen Abschnitt namens "Messinstrumente"* o.Ä. berichtet werden. Diese Regel gilt auch, wenn keine psychometrischen Maße verwendet wurden, sondern z.B Verhaltensbeobachtungen durchgeführt wurden.

- \- Aufgrund der zentralen Bedeutung der Messinstrumente *sind diese genau zu schildern*. Bei psychometrisch fundierten Fragebogen und ähnlichen Instrumenten sind z.B. die Items im Anhang aufzuführen (oder als zweitbeste Alternative auf eine offene URL zu verweisen) und im Haupttext einige Items beispielhaft zu zitieren. Wird eine Variable nur mit einem Item (per Selbstauskunft) erhoben (z.B. "Wie glücklich sind Sie heute?" oder "Wie viele Zigaretten haben Sie gestern geraucht?") so sind diese Items im Haupttext zu zitieren.




## Stimuli (xxstimuli)


- Es wurde eine (sehr) kleine Stichprobe an Stimuli erhoben, aber es wurden Aussagen für die Grundgesamtheit der betreffenden Stimuli gemacht. Der Grundsatz, dass von einer Personen-Stichprobe nicht ohne Weiteres auf die Grundgesamtheit geschlossen werden kann, sondern dass Größe und Zufälligkeit (Repräsentativität) eine entscheidende Rolle spielen, gilt auch für Stimuli-Stichproben. Beispiel: Eine Studie untersucht, ob Professoren als "freundlich" gesehen werden. Als Beispiel für Professoren wird nur ein Stimulus gewählt, nämlich ein Foto von Professor Süß. Die große Personenstichprobe bewertet das Foto (die Person darauf, Prof. Süß) als wenig freundlich. Kann jetzt geschlossen werden, dass Professoren allgemein als wenig freundlich beurteilt werden? Dieser Schlüsse würde vorschnell übergeneralisieren. Eine größere Stichprobe an Stimuli (mehrere vergleichbare, kontrollierte Professorenfotos) wären für eine solche Generalisierung nötig. Vgl. Wells, G. L., & Windschitl, P. D. (1999). Stimulus sampling and social psychological experimentation. *Personality and Social Psychology Bulletin, 25*(9), 1115-1125.

  

## Hypothesen (xxhypo) {#hypothesen}

### Anzahl {#anzhyps}
- \+ Die Anzahl der Hypothesen ist groß; es wurde somit eine umfangreiche Studie durchgeführt bzw. geplant.

- \+- Die Anzahl der Hypothesen ist weder groß noch gering.

- \+- Die Anzahl der Hypothesen ist von mittlerer Höhe.

`---`



- \- Die Anzahl der Hypothesen ist gering.

- \- Die Hypothesen wurden nicht expliziert oder fehlen komplett. Das ist ein wesentliches Manko für quantitative Arbeiten (sofern der Theorieteil andeutet, dass Hypothesen untersucht werden sollen in der Arbeit, wie es hier der Fall ist).

- \- Eine quantitative Studie dieser Art sollte i.d.R. Hypothesen umfassen. Diese fehlen aber in der vorliegenden Arbeit.


### Formulierung -- Beurteilung (Korrektheit/Vorhandensein)

`+++`

- \+ Die Hypothesen wurden formal korrekt spezifiziert.
- \+ H_0 und H_A wurden jeweils korrekt spezifiziert.


`---`


- \- Die Hypothesen wurden *formal nicht immer korrekt spezifiziert oder fehlen* (teilweise).

- \- Die *Nullhypothese* und/oder die Alternativhypothese wurde nicht korrekt spezifiziert.


- \- H_0 und H_1 wurden nicht immer korrekt spezifiziert.

- \- Eine Hypothese sollte i.d.R. die Form "Wenn A, dann B" aufweisen (oder "Je mehr A, desto mehr B"). Hat aber eine Hypothese die Form *"Wenn A, dann B und C"* und findet man bei Vorliegen von A nur B, aber nicht C, so ist unklar, ob die Hypothese bestätigt ist oder nicht (streng genommen ist sie es nicht). Zur Klarheit empfielt es sich, letztere Hypothese in zwei Hypothesen aufzutrennen ("A -> B" und "A -> C"). Dieser Punkt wurde in der vorliegenden Arbeit nicht (komplett) berücksichtigt.


### Ableitung aus Theorie

`+++`

- \+ Die Hypothesen leiten sich stringent aus dem Theorieteil ab.
- \+ Die Hypothesen leiten sich insgesamt passend aus dem Theorieteil ab.

- \+ Die Hypothesen wurden klar herausgestellt.


- \+ Das Kategoriensystem leitet sich stringent aus der Theorie ab.
- \+ Das Kategoriensystem wurden klar herausgestellt.


`---`



- \- Die Hypothesen leiten sich nicht (alle) stringent aus dem Theorieteil ab.


- \- Einige Hypothesen sind nicht aus der vorher angeführten Theorie abgeleitet, sondern schweben "frei im Raum". Dies ist nicht wünschenswert. Jede Hypothese soll sich gut ersichtlich aus der vorher angeführten Theorie (und der Forschungsfrage) ableiten (klassisches Beispiel: Geschlecht als UV). Nicht klar abgeleitete Hypothesen bergen die Gefahr der Beliebigkeit und erhöhen damit die Zahl der falsch-positiven Ergebnisse. Abgesehen sind sie wenig überzeugend.
- \- Das Kategoriensystem leitet sich nicht stringent aus der Theorie ab.
- \- Das Kategoriensystem wurden nicht klar herausgestellt.




### Präzision

- \+ Ein *Pfaddiagramm* zur Darstellung der Hypothesen wurde verwendet, was die Rezeption der Hypothesen durch den Leser erleichtert.
- \+ Die Hypothesen waren konkret, *spezifisch*; d. h. es wurde z. B. nicht nur ein einfacher Zusammenhang, sondern auch die* Stärke dieses Zusammenhangs* in der Alternativhypothese vermerkt.
- \+ Die Hypothesen wurden *klar (eindeutig, operational)* formuliert.

`---`


- \- Ein *Pfaddiagramm hätte die Darstellung der Hypothesen bzw. die Rezeption der Hypothesen für den Leser erleichtert*, fehlt aber.
- \- Einige oder alle Hypothesen *sollten operationaler* definiert sein ("konkret"), als es in der vorliegenden Arbeit der Fall ist.
- \- Die Hypothesen *wurden als ungerichtet berichtet*; allerdings lässt die Ausarbeitung im Theorieteil eher auf gerichtete Hypothesen schließen. Insofern passen Theorieteil und Hypothesen nicht ideal aufeinander.
- \- Die Hypothesen *sollten konkrete*r sein.
- \- Eine oder mehrere Hypothesen konstatieren (allgemein gesagt), dass "X größer Y" sei. Vermutlich war aber gemeint, dass X *im Durchschnitt* größer als Y ist.
- \- Die Hypothesen sind unpräzise (oder falsch) formuliert bzw. passen nicht zu der Datenanalyse. Testet man z. B., ob sich zwei Mittelwerte (signifikant) unterscheiden, so sollte die zugehörige H0 etwa lauten: "*Mittelwert von Gruppe A gleich Mittelwert von Gruppe B*"; zu sagen "Es gibt keinen Unterschied zwischen den Gruppen A und B" hingegen vernachlässigt, die Aussage auf den Mittelwert einzugrenzen.




### Sonstige Fehler

- \- Für jede einzelne Hypothese soll eine eigene, eigenständige H0 angenommen werden. Das wurde in der vorliegenden Arbeit nicht berücksichtigt.

- \- Die Hypothesen werden nicht an richtiger Stelle aufgeführt.


- \- *H0 und H1 wurden verwechselt*.
- \- Die H0 braucht bei der Auflistung der Hypothesen nicht eigens formuliert zu werden (sofern sie sich komplementär zur H1 ergibt).

- \- Die Hypothesen waren (ganz oder teilweise) ungerichtet formuliert, *obwohl eine gerichtete Hypothese sinnvoll gewesen* wäre.



- \- Die Hypothesen wurden nicht klar ersichtlich oder nicht explizit oder nicht prägnant berichtet.


## Stichprobengröße, -beschaffenheit und Poweranalyse (xxstipro) {#sample}

### Größe  

Der Gutachter beziffert seine Anforderungen an das grobe Mengengerüst einer empirischen Studie wie folgt (s. Hinweise für Abschlussarbeiten auf der OC-Seite des Gutchters): 1. Experiment/Between-Faktor: Ca. 20 Personen pro Between-Faktor-Gruppe; 2. Experiment/Within-Faktor: Ca 30 pro Faktor (unabhängig von der Anzahl der Stufen); 3. Beobachtungsstudie: ca. 150 Fälle und mind. 3 Variablen; 4. Fragebogenanalyse: ca. 300 Fälle.


`+++`


- \+ Der Umfang der Stichprobe ist *hoch* (gemessen an den Anforderungen der Prüfung).


`---`


- \+- Der Umfang der Stichprobe ist *mittel hoch* (gemessen an den Anforderungen der Prüfung).

- \+- Der *Umfang* der Stichprobe ist *angemessen* (gemessen an den Anforderungen der Prüfung).

- \- Der *Umfang* der Stichprobe ist *klein* (gemessen an den Anforderungen der Prüfung).


### Qualität (Zufallsstichprobe)

- \+ Es handelt sich um eine *Zufallsstichprobe*, was eine sinnvolle bzw. eine nötige Voraussetzung für die Verwendung von Methoden der Inferenzstatistik darstellt.
- \+ Die Qualität der Stichprobe wurde unterstützt, indem auffällige Fälle aus der Stichprobe (nach Prüfung) entfernt wurden.

`---`



- \- "Zufallsstichprobe" war hier eher *Adhoc-Stichprobe*.

- \- Zwar spricht die Autorin von einer Zufallsstichprobe, doch handelt es sich wohl eher um eine *Adhoc-Stichprobe*.

- \- Hinweise zur Repräsentativität der Stichprobe wären von nutzen gewesen, fehlen aber.


### Poweranalyse (xxpower)
- \+ Es wurde eine *Power-Analyse* durchgeführt, was eine sinnvolle (oder sogar dringend benötigte) Maßnahme zur Sicherstellung der empirischen Qualität darstellt.
- \+ Bei der Poweranalyse wurde der erwartete Effekt auf Basis früherer Untersuchungen festgelegt. Das ist ein sinnvolles Vorgehen und weit besser als per fiat von z.B. einem "mittleren" Effekt auszugehen. 

- \- Eine Power-Analyse hätte die Aussagekraft der Ergebnisse erhöht, *fehlt* aber oder liegt nicht an geeigneter Stelle vor. Eine (apriori-)Effektgröße wäre aus bestehender Literatur wahrscheinlich ableitbar.
- \- Die Power-Analyse *hätte genauer erläutert werden* müssen, damit sie nachvollziehbar ist. So sind die folgenden Informationen nötig, um die Berechnung replizieren zu können: Effektstärke in Höhe und Typ (z.B. Cohens *d*), Power, Alphaniveau, Seitigkeit des Tests (ein- vs. zweiseitig) und Art der Hypothese bzw. Tests (z.B. $F$-Test). 

- \- Bei einer Poweranalyse sollte die *Größe des erwarteten Effekts* durch *Rückgriff auf geeignete Literatur* gerechtfertigt werden (etwa: "Müller (2019) berichtet in seiner Metaanalyse von einer moderat hohen Korrelation (r = .42); entsprechend wird dieser Schätzwert für die Effektstärke in der vorliegenden Studie angenommen").

- \- Es ist nicht auszuschließen, dass es *fachliche Fehler in der Berechnung* des optimalen Stichprobenumfanges im Rahmen der Poweranalyse gibt.


### Zusammenstellung/Auswahl {#stiprozusammenstellung}


NUR QUALI: 

- \+ Die Auswahl der untersuchten Personen bzw. die Zusammenstellung der Stichprobe wurde adäquat begründet.



- \- Die Zusammenstellung der Stichprobe (bottom-up? top-down? Sättigungskriterien?) wurde nicht (ausreichend) erläutert.


### Interviewdauer

NUR QUALI: 

- \- Für diese Prüfungsleistung war eine gesamte Interviewdauer von 30 Minuten angezeigt. Diese formale Anforderung wird in der vorliegenden Arbeit nicht erfüllt. Insofern ist ein wesentlicher Bestandteil der Prüfungsleistung nicht erbracht.


## Tabellen (xxtabs)

### Anzahl von Tabellen
- \+ Es wurden Tabellen zur Verdeutlichung zentraler Sachverhalte sinnvoll eingesetzt.

- \- Tabellen (oder Abbildungen) wären eine sinnvolle Ergänzung gewesen, um zentrale Ergebnisse konzise darzustellen, fehlen aber.



### Gestaltung der Tabellen

`+++`

- \+ Einige oder alle Tabellen sind *optisch ansprechend formatiert *und übersichtlich gestaltet.
- \+ Die Gestaltung und/oder Referenzierung der Tabellen ist tadellos und/oder orientiert sich an den Gestaltungsrichtlinien der APA.


`---`


- \- Tabellen sollten (in wissenschaftlichen Arbeiten) besser *auf "Schnörkel" verzichten*: Intensiv wirkende Aspekte (wie eingefärbte Hintergründe), die wenig Information bergen und/oder nur begrenzt (wenn überhaupt) zur Übersichtlichkeit/Strukturierung beitragen, sollten vermieden werden. Trotzdem sollte (natürlich) eine Tabelle ansprechend und elegant gesetzt sein, wie es in vielen Fachartikeln sinnvoll gelöst ist.

- \- Die Formatierung der Tabellen ist *häufig nicht ansprechend;* vgl. Richtlinien der dt. Gesellschaft für Psychologie/APA oder Leitfaden Wirtschaftspsychologie dazu.
- \- Die Formatierung der Tabellen ist *nicht immer ansprechend*; vgl. Richtlinien der dt. Gesellschaft für Psychologie/APA oder Leitfaden Wirtschaftspsychologie dazu.
- \- Bitte *machen Sie sich* mit der Formatierung von Tabellen laut APA/DGPs *vertraut*, vgl. Leitfaden Wirtschaftspsychologie.

- \- Tabellen sollten grundsätzlich ohne vertikale Linien gesetzt sein.

- \- *Tabellen* sollten nicht als *Screenshot* (z. B. aus Excel) abgebildet werden. Mit geringem Aufwand kann ein deutlich schöneres Ergebnis erzielt werden. 


- \- Die *Spaltenüberschriften* sollten in der gleichen Sprache geschrieben sein wie der übrige Bericht.

- \- Bei Tabellen sollte man auf (farblich intensive) Darstellung von *Spaltengrenzen* in Formen *vertikaler Linien* verzichten, da diese zur stark im Inhalt ablenken. Die Formvorgaben der APA/DGPs sehen zudem vor, auf solche Linien zu verzichten. Die vorliegende Arbeit berücksichtigt dies nicht durchgehend.






## Datenanalyse (Statistik xxstat xxdataanalysis)  {#datenanalyse}






### Auswahl des richtigen Verfahrens {#auswahlverfahren}

`+++`

- \+ Es wurden durchgängig *angemessene Verfahren* der Datenanalyse (z. B. inferenzstatistische Verfahren) ausgewählt.
- \+ Es wurden *im Großen und Ganzen* angemessene Verfahren der Datenanalyse (z. B. inferenzstatistische Verfahren) ausgewählt.
+ Es wurden *meistens* angemessene Verfahren der Datenanalyse (z. B. inferenzstatistische Verfahren) ausgewählt.


- \+ Es wurden moderne bzw. sinnvolle Methoden der Datenanalyse verwendet,z. B. *simulationsbasierte Inferenz, SBI* o. Ä..
- \+ Es wurden (*in Teilen*) moderne bzw. sinnvolle Methoden der Datenanalyse verwendet (z. B. *simulationsbasierte Inferenz, SBI*).

- \+ Es wurden *fortgeschrittene Methoden der Datenanalyse* eingesetzt, die nicht (oder nur eingeschränkt) im Unterricht behandelt wurden und insofern eine selbständige Einarbeitung verlangt haben (z. B. Moderator-, Interaktions- oder Mediatoranalysen). Dies zeigt eine gute Durchdringung der Materie.
- \+ Es wurden *multivariate Methoden* (z. B. multiple Regression) sinnvoll ausgewählt, um etwaige "Überschneidungen" von Variablen bzw. um "Nettoeffekte" einzelner Variablen zu bestimmen.
- \+ Es wurden *Moderator- bzw. Interaktionsanalysen* durchgeführt; diese Analysen bereichern die vorliegende Arbeit.





- \+- Es wurden zum Teil angemessene, zum Teil nicht angemessene Verfahren der Datenanalyse (z. B. inferenzstatistische Verfahren) ausgewählt.


`---`




- \- *Simulationsbasierte Inferenzverfahren (SBI)* wären eine sinnvolle Ergänzung in der vorliegenden Analyse gewesen, *fehlen* aber.

- \- Gerade im Hinblick zu den (möglicherweise) verletzten Annahmen, die "klassische" Verfahren (wie der t-Test) benötigen, wären simulationsbasierte Verfahren eine sinnvolle Ergänzung oder Alternative gewesen.

- \- Es wurden *nicht angemessene Verfahren* der Datenanalyse (z. B. inferenzstatistische Verfahren) ausgewählt; stattdessen wurden falsche bzw. nicht angebrachte oder keine oder nicht optimale statistische Verfahren ausgewählt.

- \- *Multivariate Auswertungsverfahren* wären eine sinnvolle Ergänzung gewesen, fehlen aber (ganz oder teilweise) bzw. sind nicht im Hauptteil dokumentiert (Beispiel: Die Korrelationsanalysen oder einfache Regressionsanalysen wären durch eine multiple Regression gut ergänzt worden. So wäre es z. B. möglich gewesen, den Einfluss einzelner Variablen vom Einfluss anderer Variablen zu "befreien"). Der Vorteil multivariater Verfahren wie etwa der multiplen Regressionsanalyse liegt in ihrer Fähigkeit, den "wahren" Einfluss eines Prädiktors besser zu bestimmen, als dies etwa mehrere einfache Regressionsanalysen (mit nur jeweils einem Prädiktor) leisten. Die multiple Regression hilft, etwaige "Überschneidungen" von Variablen bzw. "Nettoeffekte" einzelner Variablen zu bestimmen.

- \- Es wurden keine oder nicht genügend *deskriptivstatistische* Kennwerte berichtet.
- \- *Inferenzstatistische Verfahren fehlen* ganz oder teilweise.

- \- Die eingesetzten (statistischen) Verfahren wurde *nicht (durchgängig) spezifiziert*; so wird nicht (immer) klar, welche Berechnungen durchgeführt bzw. welche Modelle berechnet wurden bzw. werden sollen. Wenn die Leserschaft nicht weiß, welche statistischen Verfahren verwendet wurden, ist mit den Ergebnissen wenig anzufangen. Daher ist es von hoher Bedeutung, deutlich anzugeben, welche statistischen Verfahren (allgemein: welche Methoden) eingesetzt wurden bzw. werden sollen.
- \- Bei der Durchführung einer statistischen Simulation reicht es nicht, z. B. von einem Permutationstest zu sprechen. Dazu ist noch anzugeben, welcher Kennwert (Mittelwert? Median?) permutiert wurde. 


- \- Die Auswahl der Verfahren zur Datenanalyse ist *nicht in ausreichendem Maß erläutert* und/oder begründet.

- \- Der Abschnitt zur Beschreibung der gewählten Verfahren zur Datenanalyse hätte *von einer detaillierteren Erörterung profitiert* (Beispiel: Welches Verfahren für welche Hypothese? Welche Variablen sollen jeweils analysiert werden?)












### Richtige Anwendung/Ergebnisbewertung von Verfahren der Datenanalyse {#ergbewertung}

`+++`

+ \+ Die statistischen Verfahren wurden (weitgehend) *richtig* (im Sinne von fehlerfrei) *angewendet.*
+ \+ Die Ergebnisse der eingesetzten statistischen Verfahren wurden (weitgehend) richtig dargestellt.


- \+ Die Ergebnisse wurden in *übersichtlicher und stringenter Weise dargestellt*.
- \+ Es wurde ein sinnvoller und *breiter Überblick an Statistiken berichtet*.

`---`


- \- Es wurden *nicht alle relevanten statistischen Kennwerte berichtet* (z. B. fehlen t-Werte, SE oder deskriptive Kennwerte).
- \- Aufgrund der fehlenden statistischen Kennwerte ist das methodische Vorgehen nur eingeschränkt nachvollziehen.
- \- Die Ergebnisse der statistischen Verfahren wurden *lückenhaft* oder falsch berichtet.
- \- Einige Verfahren wurden *falsch angewendet* (z. B. falsches Skalenniveau angenommen oder UV und AV verwechselt).
- \- Eine quantitative Variable in *ordinale Stufen einzuteilen*, ist statistisch nachteilig (Power-Verlust), vgl. MacCallum, R. C., Zhang, S., Preacher, K. J., & Rucker, D. D. (2002). *On the practice of dichotomization of quantitative variables*. Psychological Methods, 7(1), 19-40. doi: http://dx.doi.org/10.1037/1082-989X.7.1.19.

- \- Bei metrischen Variablen mit vielen Ausprägungen sollten sollten keine Häufigkeiten ausgezählt werden, da es sehr viele Kategorien mit jeweils sehr wenig "Insassen" geben wird. Das Ergebnis ist also nur wenig aussagekräftig.
- \- Der *Standardfehler* ist zur Beurteilung der Signifikanz nötig, wurde aber *nicht berichtet.*
- \- Es wurden Verfahren ausgeführt, die dann *nicht interpretiert* bzw. deren Ergebnisse *nicht (oder zu knapp) beschrieben* wurden. 







### Datenvorverarbeitung

- \- Ein metrische Variable in zwei Gruppen aufzuteilen (sog. "*Dichotomisierung*"), mit z. B. dem Median als Grenze ("*Mediansplit*") ist statistisch i.d.R. nachteilig und sollte vermieden werden. Die vorliegende Arbeit verwendet solch eine Art von nicht sinnvoller Dichotomisierung. ), vgl. MacCallum, R. C., Zhang, S., Preacher, K. J., & Rucker, D. D. (2002). *On the practice of dichotomization of quantitative variables*. Psychological Methods, 7(1), 19-40. doi: http://dx.doi.org/10.1037/1082-989X.7.1.19.




### Daten-Diagramme (xxdataviz) {#datadiagrams}

#### Verwendung/Anzahl
- \+ *Diagramme* wurden sinnvoll eingesetzt, um zentrale Ergebnisse zu vermitteln (z. B. Boxplots, Histogramme, Streudiagramme).

- \- (Mehr) Diagramme hätten geholfen, die empirischen Ergebnisse anschaulicher und greifbarer zu machen.




#### Auswahl

+ \+ Es wurden *sinnvolle Diagramme* ausgewählt, die für die Forschungsfrage relevante Einblicke ermöglichen.

`---`


- \- Zwar wurden Diagramme eingesetzt, um zentrale statistische Sachverhalte zu verdeutlichen, jedoch war die *Wahl der Diagramme nicht immer ideal* (z. B. Balkendiagramm wo ein Histogramm informationsreicher gewesen wäre).
- \- Der *Boxplot* ist gut geeignet, um die Verteilungen mehrerer Gruppen zu vergleichen (Histogramme hingegen weniger). Möchten man hingegen nur eine Verteilung visualisieren ist ein Histogramm oder eine Dichte-Diagramm besser geeignet.

- \- Untersucht man einen Mittelwert bzw. *Mittelwertsunterschied*, so ist der *Boxplot keine ideale Visualisierung*, da im Boxplot der Median (nicht der Mittelwert) dargestellt wird. Eine gute Alternative wäre ein Violinplot plus einen gut sichtbaren Punkt für den (jeweiligen) Mittelwert (im Standard-Statistikskript ist dies dargestellt).


#### Gestalterische Qualität - Bewertung
- \+ Die gestalterische Qualität der Abbildungen ist *sehr hoch*.
- \+ Die gestalterische Qualität der Abbildungen ist *hoch.*
- \+ Die gestalterische Qualität einiger Abbildungen (nicht aller) ist *hoch.*
- \+ Die gestalterische Qualität der Abbildungen ist *insgesamt gut*.
- \+ Die gestalterische Qualität der Abbildungen ist *befriedigend bis gu*t.



- \+- Die gestalterische Qualität der Abbildungen ist von *befriedigender Güte*.

`---`


- \- Die gestalterische Qualität der Abbildungen *überzeugt nicht immer* (z. B. pixelig oder verzerrt).

- \- Die gestalterische Qualität der Abbildungen ist *nicht immer ausreichend* (z. B. pixelig oder verzerrt).
- \- Die gestalterische Qualität der Abbildungen ist *zumeist unzureichend* (z. B. pixelig oder verzerrt).


#### Gestalterische Qualität - Kommentare

`+++`

- \+ Im Hinblick auf die Abbildungen sticht positiv ins Auge, dass die  Abbildungen (zumeist oder immer) gestochen dargestellt sind, also mit *hoher Auflösung* in den Druck eingegangen sind. Dies kann durch den Einsatz von Vektorgrafiken realisiert worden sein, was ein Indikator für technisches Geschick ist unabhängig oder zusätzlich zur optischen Anmutung der Abbildungen.


`---`


- \- Es wäre von Vorteil gewesen, einige *Diagramme nicht (per "Screenshot") einzufügen*, sondern selber zu erstellen, um die Qualität der Abbildung sicherzustellen (z. B. um "pixelige" Abbildungen aufgrund geringer DPI-Auflösung zu vermeiden).
- \- Einige Abbildungen sind "*pixelig*".
- \- Die optische Qualität hätte profitiert, wenn die Diagramme nicht als Bitmap (d. h. als *Screenshot*, z. B. in den Formaten png oder jpg) eingefügt worden wären, sondern als *Vektordiagramm.* Im Fall von Vektorgrafiken ist die Auflösung besser und andere Bildfehler werden ebenfalls vermieden.
- \- *Balkendiagramme* sollten nicht in der Umrandung (ggplot: Parameter `color`), sondern wenn dann in der *Füllung* (ggplot: Parameter `fill`) eingefärbt werden.
- \- Die Diagramme sind *nicht einheitlich gestaltet*; die Format-Vorlage wechselt.
- \- *Kreisdiagramme* ("*Torten*") sollten gemieden werden, da (vor allem bei vielen kleinen Kategorien mit ähnlicher Häufigkeit) die visuelle Diskriminierbarkeit eingeschränkt ist. Einfach gesagt: Man sieht nicht unbedingt, was Sache ist, in einem Kreisdiagramm. In der vorliegenden Arbeit finden aber solche Diagramme Verwendung.
- \- *3D-Diagramme* verzerren zumeist den Blickwinkel, so dass Winkeltreue nicht mehr gegeben ist. Der optische Eindruck von Winkeln (z. B. in einem Kreisdiagramm) korrespondiert dann nicht mehr unbedingt korrekt mit dem Winkel laut Daten.
- \- Bei Balkendiagrammen ist es zumeist hilfreich, *nach der Höhe der Balken zu sortieren* -- zumindest, wenn die Frage im Vordergrund steht, was die häufigste (oder seltenste) Kategorie ist. Eine alphabetische Sortierung oder eine willkürliche Sortierung ist fast immer nicht sinnvoll. Dies wurde in der vorliegenden Arbeit nicht (ausreichend) beachtet.
- \- Die Hypothesen untersuchen den *Mittelwert*, aber alle oder einige Diagramme zeigen nicht den Mittelwert, sondern den *Median* (z. B. mittels eines Boxplots).
- \- Einige Diagramme leiden unter "*Overplotting*", d. h. viele Details (z. B. Punkte) sind übereinander gezeichnet, so dass die (relative) Anzahl von Punkten im Diagramm schwer bzw. eingeschränkt erkennbar ist.


#### Farbwahl

- \- Die gewählte *Farbpalette* war *nicht gut für S/W-Druck geeignet*. Der Sättigungswert der Farben hätte besser variiert werden können Tipp: Auf der Webseite <http://colorbrewer2.org/> kann man sich Farbpaletten erstellen lassen. In `ggplot2` kann man Grauskalen mit dem Argument `scale_fill_grey` erreichen. Auch die Viridis-Farbpalette ist für S/W-Druck geeignet (vgl. <https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html>).

#### Achsen, Labels und Legenden von Abbildungen
- \+ Die Achsen der Diagramme wurden *sinnvoll beschriftet*.
- \+ Die Achsen der Diagramme wurden *(zumeist) sinnvoll beschrifte*t.

- \+- Die Achsen der Diagramme wurden *nur teilweise oder nicht (immer) klar verständlich* (z. B. in einer Abkürzung) beschriftet. Verständliche Achsenbeschriftungen (z. B. verständlicher, deutscher und nicht abgekürzter Variablenname). Ansonsten sind die Diagramme (für sich alleine stehend) schwer(er) zu verstehen.

`---`


- \- Die Legende von Diagrammen sollten das Diagramm erläutern (vgl. auch APA-/DGPs-Richtlinien).
- \- Die Achsen von Diagrammen sollten mit *aussagekräftigen* bzw. *verständlichen*  Bezeichnungen versehen werden (z. B. ganze Wörter in deutscher Sprache).

- \- Die Beschriftungen der Ausprägungen der Achsen (Labels) ware *nicht durchgängig gut zu lesen* (z. B. überdeckten sich die Achsenlabels).












### Breite der Analyse (xxstatbreite) {#analyse-allgemein}

`+++`

- \+ Insgesamt ist der Umfang der Datenanalyse als *von hoher Güte* einzuschätzen. 
- \+ Insgesamt ist der Umfang der Datenanalyse als *gut* einzuschätzen. 


- \+ Die Datenanalyse ist insgesamt *sehr umfangreich*.
- \+ Die Datenanalyse ist insgesamt *umfangreich.*


`---`


- \+- Insgesamt ist der Umfang der Datenanalyse als von *mittlerer (befriedigender) bis hoher Güte* einzuschätzen. 
- \+- Insgesamt ist der Umfang der Datenanalyse als von *mittlerer* (befriedigender) Güte einzuschätzen. 


- \+- Insgesamt ist der Umfang der Datenanalyse als von *unterdurchschnittlicher* Güte einzuschätzen. 
- \+- Insgesamt ist der Umfang der Datenanalyse als von *geringer* Güte einzuschätzen. 



### Güte der Analyse -- Beurteilung (xxstatqualitaet) {#analyse-guete}

`+++`

- \+ Insgesamt ist das Niveau  er Datenanalyse als von *hoher* Güte einzuschätzen. 
- \+ Insgesamt ist das Niveau der Datenanalyse als *gut* einzuschätzen. 

- \+ Die Datenanalyse ist insgesamt als q*ualitativ gut* einzustufen.

- \+- Insgesamt ist das Niveau der Datenanalyse als von *mittlerer*  (befriedigender) bis hoher Güte einzuschätzen. 


- \+- Insgesamt ist das Niveau der Datenanalyse als von *mittlerer* (befriedigender) Güte einzuschätzen. 


- \+- Insgesamt ist das Niveau der Datenanalyse als von *unterdurchschnittlicher* Güte einzuschätzen. 
- \+- Insgesamt ist das Niveau der Datenanalyse als von *geringer* Güte einzuschätzen. 

- \- Zentrale Konzepte oder Methoden oder Prinzipien der Datenanalyse sind fehlerbehaftet.

### Deskriptive Statistik {#deskriptivstatistik}

- \+ Es wurde eine *sinnvolle Auswahl* an deskriptiven Statistik berichtet.
- \+ Die berichteten deskriptiven Statistiken wurden *korrekt interpretiert*.


### Häufigkeitsanalysen

`+++`

- \+ Für eine Häufigkeitsanalyse wurde vorab eine Gruppierung ("Binnen") in einige zusammenfassende Kategorien (z. B. "unter 3000$ Einkommen") vorgenommen. Die nachgeschaltete Häufigkeit wurde damit übersichtlicher und nützlicher.


`---`


- \- Eine Häufigkeitsaufstellung sehr vieler Kategorien ist wenig zweckdienlich, da unübersichtlich. 
- \- Ein sinnvolles Vorgehen beim Berichten der Häufigkeit vieler Kategorien ist es, diese in Ober-Kategorien einzuteilen, so dass es weniger Kategorien zu berichten gibt. Damit kann ein übersichtlicheres Ergebnis erreicht werden.
- \- Eine Häufigkeitsanalyse sollte i.d.R. sortiert erfolgen, d. h. häufigere Kategorien sollten vor selteneren stehen. Eine willkürliche, alphabetische oder sonstige Sortierung ist zumeist wenig nützlich.


### Effektstärke  (xxeffsize) {#effsize}
- \+ Das Effektstärkemaß (wie z. B. Cohens d oder R-Quadrat) ist eine sinnvolle, sogar notwendige Ergänzung zu den anderen deskriptiv-statistischen Werten und wurde sinnvoll eingesetzt; Angaben zur Schätzgenauigkeit eines Effekts sind dabei von hohem Nutzen.


`---`


- \- Maße der Effektstärke (z. B. Cohens D oder R-Quadrat) wären eine sinnvolle Ergänzung gewesen, wurden aber nicht oder nur teilweise verwendet. Auch bei nicht-signifikanten Ergebnissen sind Effektstärken -- insbesondere mit Angaben zur Schätzgenauigkeit -- sinnvoll.


### Robustheit
- \+ Es wurden "robuste" Statistiken berichtet (z. B. Median oder IQR).
- \+ Der Datensatz wurde auf Ausreißer (Robustheit) hin untersucht.


`---`


- \- "Robuste" Statistiken (wie Median oder IQR) wären eine sinnvolle Ergänzung/Alternative zur vorliegenden Analyse gewesen.
- \- Es wurde versäumt, den Datensatz  auf Ausreißer (Stichwort Robustheit) hin zu untersuchen.



### Konfidenzintervalle (xxkonfi) {#ki}

- \+  Konfidenzintervalle wurden in sinnvoller Weise berichtet.
- \- Konfidenzintervalle wären eine sinnvolle Erweiterung gewesen (auch bei nicht-signifikanten Ergebnissen), fehlen aber.


### Voraussetzungen/Annahmen 
- \+ Einige oder alle statistischen *Voraussetzungen* (*Annahmen*) der eingesetzten inferenzstatistischen Verfahren wurden geprüft (z. B. Test auf Normalverteilung).

- \- Wenn die *Voraussetzungen* für parametrische Verfahren *nicht erfüllt* sind, so können oft *non-parametrische Verfahren* eingesetzt werden.

- \- Der *Shapiro-Wilk-Test* ist ein sehr *(zu) strenger Test* für Normalverteilung und sollte zumindest durch andere, v.a. grafisch-explorative Methoden, ergänzt werden.

- \- Es ist ein *Irrglaube*, dass *große Stichproben* alleine schon eine *Normalverteilung* implizieren. Auch eine große Stichprobe an z. B. Filmen wird keine Normalverteilung der Einnahmen aufzeigen.

- \- Laut Gelman und Hill (2014) ist die* wichtigste Annahme der Regressionsanalyse*, dass es *keinen Zusammenhang gibt zwischen vorhergesagten Werten und Residuen*. Im entsprechenden Streudiagramm sollte die Regressionsgerade parallel zur X-Achse verlaufen. 

- \ Laut Box (1953) ist die *Varianzanalyse robust gegenüber der Verletzung der Annahme gleicher Varianzen*, wenn die Stichproben ähnlich groß sind (bis zu einen Faktor von 1.5): 

    > "It has frequently been suggested that a test of homogeneity of variances should be applied


before making an analysis of variance test ior homogeneity of means in which homogeneity
 of variance is assumed. The present research suggests than when, as is usual, little is known
 of the parent distribution, this practice may well lead to more wrong conclusions than if
 the preliminary test was omitted. It has been shown (Welch, 1937; David & Johnson,
 1951b; Box, 1952; and Horsnell, 1953) that in the commonly occurring case in which the
 group sizes are equal, or not very different, the analysis of variance test is affected sur-
 prisingly little by variance inequalities. Since this test is also known to be very insensitive
 to non-normaJity it would be best to accept the fact that it can be used safely under most
 practical conditions. To make the preliminary test on variances is rather like putting to sea
 in a rowing boat to find out whether conditions are sufficiently calm for an ocean liner to
 leave port!" (S. 333).
 
 Demnach kann in diesen Fällen eine Varianzanalyse verwendet werden.
 
 
- \- Der *t-Test ist robust gegenüber Verletzungen seiner Annahmen* (insbesondere der Normalverteilung), wenn die Stichprobe groß genug ist (> 30): "By the time the sample sizes reach 25 or 30, the approach should be close enough that one can, in effect, ignore the effects of violations of assump- tions except for extremes." (S. 63), Boneau, C. A. (1960). The effects of violations of assumptions underlying the t test. *Psychological bulletin*, 57(1), 49-64.



### p-Wert (xxpvalue) {#pvalue}

`+++`

- \+ Der p-Wert wird *exakt erläutert* bzw. verwendet. Es wird auf die genaue Definition gehört, nämlich dass "Die Daten (und noch extremere) unwahrscheinlich sind, unter der Annahme, dass die H0 gilt".

- \+ Der p-Wert wird *einigermaßen korrekt* erläutert bzw. verwendet. Vollständig korrekt wäre etwa "Die Daten (und noch extremere) sind unwahrscheinlich, unter der Annahme, dass die H0 gilt".

- \+ Der p-Wert wird  *korrekt erläutert* bzw. verwendet.



`---`





- \- Der p-Wert wird *falsch berichtet* bzw. verwendet.


- \- Der p-Wert *wird falsch erläutert* bzw. verwendet.
- \- Der p-Wert wurde für einige oder alle Inferenztest nicht berichtet.

- \- Der *p-Wert bzw. seine Bedeutung wurde nicht interpretiert* (z. B. "da der p-Wert größer als alpha ist, wird die H0 beibehalten").

- \- Da der p-Wert und - damit zusammenhängend - das Konzept des Nullhypothesen-Testen zu den zentralen Lernzielen gehört, ist ein Fehler bzw. Verständnislücken in diesem Bereich als *gravierender Mangel* einzuordnen.


- \- *Was heißt ein "signifikanter Einfluss" bzw. ein "signifikanter Zusammenhang"*, wie es in der vorliegenden Arbeit geschrieben wird? Dass der Einfluss (Zusammenhang) groß ist? Dass es wahrscheinlich ist, dass es einen gibt? Beides? Etwas anderes? Ist ein Einfluss kausal? Diese Fragen würden einer besseren Erklärung verdienen. Es sollte z. B. festgehalten werden, dass "statistische Signifikanz" eine Aussage der Inferenzstatistik ist und gewisse Evidenz gegen die H0 liefert und damit für die H1. Aus diesem Grund wird die H0 verworfen. Es ist aber nicht gesagt, dass der Effekt groß ist (also von praktischer Bedeutung); es ist nicht mal gesagt, dass die H0 wahrscheinlich falsch ist. Nur, dass die vorliegende Methode sich gegen die H0 ausspricht.

- \- p-Werte sollten *nicht im "technischen Format"* des Taschenrechners berichtet werd, also etwa nicht *"p = 2.2e-16"*, sondern "p < .001".


### Signifikanzniveau (Alpha)

- \+ Das *Signifikanzniveau* (alpha) wurde spezifiziert.
- \+ Das Signifikanzniveau (alpha) wurde nicht (immer) spezifiziert.

- \- Es wurde nicht spezifiziert, ob ein- oder zweiseitig getestet wurde. Diese Entscheidung hat eine Auswirkung auf das Signifikanzniveau.


### Hypothesen-Testen (xxhyptest) {#hyptests}

#### Hypothesen-Testen -- Beurteilung

- \+ Die Entscheidung zum *Verwerfen/Beibehalten der H0* wurde korrekt von der Datenlage bzw. dem p-Wert abgeleitet.


`---`


- \- Die Entscheidung zum *Verwerfen/Beibehalten der H0 wurde nicht korrekt* von der Datenlage bzw. dem p-Wert abgeleitet.
- \- Es wurden *keine inferenzstatistischen Verfahren* eingesetzt.


#### Hypothesen-Testen  -- Kommentare 



`+++`


- \+ H0 und H1 wurden korrekt spezifiziert.





`---`


- \- Es *wurden nicht für alle Hypothesen (ausreichend bzw. korrekt) hypothesenprüfende Verfahren* (wie die Berechnung eines p-Werts) eingesetzt. Dies wirft die Frage auf, ob das Konzept von (und der Grund für) inferenzstatistischen Verfahren verstanden wurde. Die Antwort auf die Frage kann zumindest nicht positiv beantwortet werden auf Basis der gezeigten Leistung (weil die Leistung nicht gezeigt wurde).


- \- *Hypothesen* beziehen sich auf *Grundgesamtheiten*, von denen *Stichproben (Datensätze) nur einen Ausschnitt zeigen*. Daher kann über eine Hypothese nicht auf Grund der deskriptiven Statistik, d. h. der Beschaffenheit des Datensatzes allein, entschieden werden. Stattdessen ist ein Schluss auf die Grundgesamtheit vonnöten, was mittels Inferenzstatistik vorgenommen werden kann. Dies wurde in der vorliegenden Arbeit nicht verstanden; es wurde *keine Inferenzstatistik in diesem Sinne* eingesetzt. Dieses Manko ist als schwerwiegend einzustufen, da es fraglich ist, ob der Autor die zentrale Idee der Inferenzstatistik verstanden hat. Es sei dem Autor angeraten, über das Wozu der Inferenzstatistik noch einmal nachzudenken.




- \- Leider zielt eine Hypothese in dieser Arbeit auf *Bestätigung einer Nullhypothese* ab, was in der Fisherschen Inferenzstatistik nicht möglich ist. 



- \- *Alternativhypothesen werden nicht beibehalten oder verworfen*, das macht nur für Nullhypothesen sind, da diese getestet werden (im Gegensatz zu den Alternativhypothesen). Zwei Fälle können auftreten. Fall (A): Verwirft man eine Nullhypothese, dann hat man Grund, sich zugunsten der HA zu *entscheiden*. Diese Entscheidung impliziert noch nicht, dass die HA bewiesen ist, also sicher wahr ist. Die Entscheidung impliziert noch nicht mal, dass man an HA glaubt. Aber, egal was man glaubt, entscheiden für eine Aktion muss man sich, und in dem Fall handelt man so, als ob die HA wahr ist (vielleicht ist sie das ja). Fall (B): Kann man die H0 nicht verwerfen, so behält man sie bei. Sie ist "noch nicht verworfen", wie man sagt. Das heißt NICHT, dass die H0 (als wahr) bewiesen wurde. Nein. So könnte die Stichprobe zu klein gewesen sein, um die tatsächliche Wahrheit von HA festzustellen. Aber die Evidenzlage ist im Fall B nunmal so, dass wir nicht (mit genug Sicherheit) ausschließen können, dass H0 der Fall ist. Noch etwas präziser formuliert: Gilt die H0 wirklich (ist sie also wahr), dann sind die vorliegenden Daten nicht unwahrscheinlich. Auf dieser Basis entscheidet man sich, so die "Spielregel" dieser Technik, weiterhin an die H0 zu glauben oder sich zumindest so zu verhalten, als ob sie wahr wäre. Kurz: Man entscheidet sich für die H0, man behält sie bei.



**NICHT signifikantes** Ergebnis, Fehlinterpretationen:



- \- "No evidence of effect" ist *nicht* "evidence of no effect".  Wird ein Signifikanztest nicht signifikant, so heißt das nicht (zwangsläufig), dass kein Effekt vorliegt! Vielleicht war die Stichprobe einfach zu klein. Dieser Sachverhalt wurde in der vorliegenden Arbeit nicht klar genug erkannt.
- \- Es ist *nicht korrekt, bei nicht-signifikanten Ergebnissen die Alternativhypothese abzulehnen*. Besser ist es zu sagen, dass die Nullhypothese *nicht verworfen werden konnte*.


- \- Es wurden nicht für alle Hypothesen die Ergebnisse berichtet.

- \- Die *Nullhypothese wird nicht angenommen*, da Datenlagen, die nicht statistisch signifikant sind, nicht nur mit der Nullhypothese, sondern auch mit vielen anderen Hypothesen kompatibel sind. Eine bessere Bezeichnung ist daher, die Nullhypothese würde "nicht verworfen" oder würde "beibehalten".
- \- Da ein "nicht-signifikantes" Ergebnis nicht beweist, dass die H0 richtig ist, *sieht man besser von Aussagen wie "die H0 wurden akzeptiert/angenommen" ab*. Besser ist der Ausdruck "die H0 wurde nicht verworfen" oder "die H0 wurde beibehalten".


- \- *Da die H0 getestet wurde, kann auch nur die H0 verworfen werden* -- nicht die H1. Dieser Sachverhalt wurde in der vorliegenden Arbeit nicht korrekt dargestellt. Analog wird die H0 bei statistisch nicht signifikanten Daten nicht angenommen, sondern nur nicht verworfen, oder beibehalten.



**Signifikantes** Ergebnis


`+++`

- \+ Es wurde korrekt erkannt, dass ein *nicht* signifikantes Ergebnis keinesfalls impliziert, dass ein Effekt nicht vorliegt. Stattdessen wurde richtig angemerkt, dass die inhaltliche Hypothese keine Unterstützung gefunden habe, die Nullhypothese nicht verworfen werden konnte oder keine/kaum Evidenz zugunsten der Alternativhypothese gefunden werden konnte.


`---`


Fehlinterpretationen:



- \- Ein *signifikanter p-Wert* beim Vergleich von Gruppen kann so interpretiert werden, dass sich die *Mittelwerte* (sic) der *Gruppen unterscheiden* (unter der Annahme, dass man den Mittelwertsunterschied getestet hat). Zu sagen, dass "Gruppe 1 höhere Werte aufweist als Gruppe 2" hingegen ist unpräzise. Weil: Was meinen Sie mit "höheren Werte in Gruppe 1"? Jeder einzelne? Einige? Sicher meinen Sie den Mittelwert und nicht alle. Also lieber präzise sein!


- \- Testet man auf einen Mittelwertsunterschied (z. B. Einparkgeschwindigkeit von Männer vs. Frauen anhand eines t-Tests) und findet man ein signifikantes Ergebnis, so ist es nicht geboten, auf allgemeine Unterschiede zwischen den Gruppen zu schließen (z. B. "Männer parken schneller ein als Frauen"). Man kann höchstens resümieren, das das Ergebnis impliziert, dass sich die *Durchschnitte der Populationen unterschieden* (z. B. "Männer parken IM DURCHSCHNITT schneller ein als Frauen").


- \- Testet man, ob Gruppe "A" im Mittel höhere Werte in X aufweist als Gruppe "B" und findet man ein signifikantes Ergebnis, so *ENTSCHEIDET* man sich, sich so zu verhalten, als ob die Hypothese richtig ist. Wir können aber nicht sicher, sein, dass A wirklich höhere Wert hat als B -- in einigen Fällen werden wir z. B. einen Alpha-Fehler begangen haben. 


- \- Findet sich in einer Analyse ein *statistisch signifikanter Zusammenhang* (Einfluss bzw. allgemeiner ein "Effekt"), so kann *nicht (zwangsläufig)* daraus geschlossen werden, dass es einen *"echten" Effekt* gibt. Die vorliegende Arbeit suggeriert aber diesen (falschen) Schluss. Findet man z. B. dass Babies und Störche "statistisch extrem signifikant" korreliert sind, so heißt das nicht, dass es in Wirklichkeit einen echten (also kausalen) Zusammenhang zwischen beiden Größen geben muss.

- \- Liegt z. B. für einen Zusammenhang ein *statistisch signifikantes Ergebnis* vor, heißt das nicht, dass die Analyse für die Population auf einen "starken", "deutlichen" oder "signifikanten" Zusammenhang hindeutet, sondern nur, dass es einen Zusammenhang gäbe. Entsprechend sollte man bei statistischer Signifikanz nicht von einem *"signifikanten Zusammenhang"* sprechen. Bei einem "signifikanten Zusammenhang" ist man geneigt, an einen starken Zusammenhang, also einen inhaltlich-fahlich bedeutsamen, zu schließen. Diese Aussage ist aber von einem p-Wert als solchem nicht ableitbar.





###  Ungewissheit/Übergewissheit -- Statistisches Denken (xxovercertain) {#overcertainty}

- \- Teilweise *fehlen Koeffizienten der Ungewissheit* (z. B. *SE* bei Regressionsausgaben). Solche Angaben sind sehr wichtig, denn die Ausgaben eines statistisches Modells, sofern sie sich auf einen Populationsparameter beziehen (z. B. Einfluss des Prädiktors X in der Population) sind immer nur Schätzwerte. Ohne eine Angabe der Genauigkeit ist eine Schätzung wenig Wert. Daher sollten Schätzwerte (wie Einflussgewichte der Regression) stets mit einem Koeffizienten der Schätzgenauigkeit ausgegeben werden (z. B. SE oder Konfidenzintervalle).

- \- Die Arbeit ist in einigen Aspekten von *falsch verstandenen (überhöhten) Sicherheit bzw. Übergewissheit* geprägt. Das heißt, dass aus den Analysen eine Sicherheit abgeleitet wird, die die Daten bzw. die verwendeten Modelle nicht hergeben. Insgesamt sollten Sie vorsichtiger formulieren.

- \- Die Ergebnisse einer Analyse sollten *nicht (automatisch) für "bare Münze" genommen werden,* im Sinne von "das Modell hat die Wirklichkeit fotografiert", "das wurde jetzt zweifelsfrei bewiesen". Analyseergebnisse dieser Art sollten eher verstanden werden als "das Modell unterstützt die Hypothese  XXX ", "laut Modell gibt es einen Zusammenhang zwischen XXX" bzw. "es konnte kein Zusammenhang gefunden werden", "die Analyse lieferte keinen Beleg für einen Zusammenhang XXX".

- \- Anstelle von Formulierungen "es besteht folglich (k)ein Einfluss von X auf Y" hätten *besser vorsichtigere Schlussfolgerungen zur Aussagekraft der Ergebnisse* wie "die Daten unterstützen XXX" oder "es konnte kein Hinweis auf YYY gefunden werden".




### Unterscheidung zw. Stichprobe und Population (xxestimate)


- \- Schreibt eine Autorin z. B., dass die Ergebnisse ihrer Analyse aufzeigen, dass der Mittelwert in Gruppe X um 42 Punkte höher sei als in Gruppe Y, so stellt sich die Frage, ob die Aussage für die Stichrobe oder die Population gemeint ist. Die Analyse deutet im Allgemeinen darauf hin, dass die Stichprobe gemeint ist (dass also eine Statistik berichtet wurde), denn die Analyse der Stichprobendaten liefern genau den berichteten Wert (42). Allerdings ist die Aussage allgemein formuliert, so dass sie in diesem Sinne auf die Population anwendbar ist. Außerdem bezieht sich die Hypothese auf die Population, so dass man erwarten darf, dass berichtete Ergebnisse als Antworten zur Hypothese gemeint sind (und daher auf die Population abzielen, also Parameter berichten). Die *Unterscheidung von Statistiken und Parametern* ist wesentlich; das genaue Auseinanderhalten von Statistiken und Parametern ist auch ein wichtiges Indiz, ob und inwieweit eine Autorin die Grundlagen der (Inferenz-)Statistik durchdrungen hat. Gibt man Parameter an, so ist es sinnvoll, die Genauigkeit dieser Schätzung anzugeben, denn Angaben von *Parametern sind stets mit Unsicherheit behaftet*. Eine Studie untersucht stets nur einen Ausschnitt der Population und verallgemeinert dann zumeist auf die Population. Die Unsicherheit dieses Generalisierens sollte angegben sein. Denn: wie wertvoll ist eine Aussage, die eine Schätzung ist, wenn man die Genauigkeit der Schätzung verschwiegen wird? Auf eine Aussage ohne Angabe der Schätzgenauigkeit wird man sich nicht verlassen wollen, man wird die Aussage in vielen Fällen als wenig nützlich zurückweisen wollen. Auf diesen Aspekt ist in der vorliegenden Arbeit *suboptimal dargestellt* bzw. nicht (durchgängig bzw. in ausreichendem Maße) Rücksicht genommen worden.



### Regression (xxregress)

- \+ Die Regression bzw. der Einfluss des Prädiktors wurde korrekt interpretiert.

- \+  Bei den Regressionsmodellen multivariate Modelle mit mehreren Prädiktoren berechnet. Diese Herangehensweise ist meist besser als die Berechnung von Modellen mit nur jeweils einem Prädiktor, da man an den "bereinigten Nettoeffekten" interessiert ist. Univariate Modelle können diese bereinigten Effekte nicht zutage fördern, im Gegensatz zu Modellen mit mehreren Prädiktoren.
  

`---`


- \- Die Regression bzw. der Einfluss des Prädiktors wurde falsch interpretiert.
- \- Es wäre noch nützlich gewesen, zusätzlich die standardisierten Regressionsgewichte anzugeben, da die unstandardisierten Regressionsgewichte von der Streuung bzw. Skalierung der Variablen abhängig sind. Da dieser Punkt aber über den Unterrichtsstoff hinausgeht, wird ihm keine große Bedeutung zugemessen.


### Datensatz
- \+ Die Daten bzw. der Datensatz wurden ausführlich und korrekt beschrieben.


`---`


- \- Die Daten bzw. der Datensatz wurden nicht ausführlich genug oder nicht korrekt beschrieben.
- \- Es reicht, die zu analysierenden Variablen zu beschreiben; es müssen nicht alle Variablen des Datensatzes vorgestellt werden.

### Nachkommastellen (xxdezimal)

- \+ Die Anzahl der *Nachkommastellen* ist immer oder zumeist *passend* bzw. konsistent.


`---`


- \- Die Anzahl der *Nachkommastellen* ist *nicht immer konsistent* oder zu lang (zwei Nachkommastellen reichen i.d.R.).
- \- Die Anzahl der Nachkommastellen ist *teilweise unpassend *(z. B. zu lang) oder *inkonsistent* (mal mehr, mal weniger).

- \- Bei *Prozentzahlen* sollte man in der Regel* auf Nachkommastellen verzichten*, was hier nicht getan wurde.


- \- Die* Anzahl der Nachkommastellen* sollte *nicht zu hoch sein*, um *Scheingenauigkeit* zu vermeiden (Beispiel: "Das mittlere Körpergewicht in Deutschland beträgt 78,314159267 kg, wie eine Studie mit *n=30* herausfand.".) In der Arbeit wurden (teilweise) zu viele Nachkommastellen angegeben.






### Skalenniveau (xxskalen) {#skalenniveau}

- \+ Die *Skalenniveaus* der untersuchten Variablen wurden *korrekt* benannt.

- \- Die *Skalenniveaus* der untersuchten Variablen wurden *nicht (immer) benannt* oder nicht (immer) korrekt benannt.





### Berichten von Statistiken

#### Berichten von Statistiken -- Bewertung

+ \+ Statistische Kennwerte wurden (zumeist) *korrekt nach Vorgaben der APA berichtet*, entsprechend der formalen Vorgaben.

`---`


- \- Statistische Kennwerte *wurden nicht (durchgängig) nach Vorgaben der APA berichtet*.
- \- Es wurden *nicht alle nötigen Statistiken im Text angeführt* (z. B. fehlt der Chi-Quadrat-Wert oder ein SE-Wert).
- \- Statistische Kennwerte wurden *falsch oder unvollständig berichtet*.




#### Berichten von Statistiken -- Kommentare

- \+ Es wurden alle bzw. viele relevante Koeffizienten (Kennwerte) für die Analysen berichtet.

- \- *Statistische Kennwerte* sollten entweder in einer *Tabelle* berichtet werden (die dann im Text referenziert wird) oder im *Fließtext* eingearbeitet sein. *Elliptische*, bruchstückhafte oder nicht kommentierte Statistik-Fragmente *sollten vermieden werden*.
- \- *p-Werte kleiner als 0.001* sollen laut APA als "p < .001" berichtet werden.
- \- Kleine Zahlen wie manche p-Werte sollten nicht in der Exponentialschreibweise und insbesondere nicht in der "Taschenrechnervariante" der Exponentialschreibweise notiert werden, also nicht "p = 2.345e-03", sondern "$p = .002$". 
- \- *Einflusskoeffizienten* der Regressionsanalyse ($b$) sollten entweder direkt verständlich sein, also in allgemein verständlichen Einheiten operationalisiert sein (z. B. Geldeinheiten) oder es sollte zumindest die Skalierung expliziert werden, in z. B. die Skalenendpunkte benannt sind. Eine sinnvolle Alternative liegt im Berichten der standardisierten Koeffizienten.



## Qualitative Inhaltsanalyse {#quali}


### Kodierregeln {#kodierregeln}


- \+ Die Kodierregeln sind stimmig gewählt und transparent dokumentiert.

`---`


- \- Die Kodierregeln sind nicht (ausreichend) stimmig gewählt und/oder nicht transparent (genug) dokumentiert.
- \- Die Kodierregeln für die verwendeten Kategorien wurde nicht expliziert. So besteht die Gefahr, dass die Zuordnung der Textstellen zu den Kategorien nicht objektiv nachprüfbar und damit nicht reproduzierbar ist. Eine Studie, die nicht reproduzierbar und nicht replizierbar ist, ist für die Wissenschaft nicht nutzbar.
- \- Ein Nichtexplizieren der Kodierregeln wirft die Gefahr der Beliebigkeit auf. Insofern handelt es sich dabei aus Sicht der wissenschaftlichen Verwertbarkeit um einen grarvierenden Fehler.





### Kategoriensystem {#kategoriensystem}

- \+ Zentrale Aussagen der Kategorien wurden treffend wiedergegeben.

- \+ Die Kategorien des Kategoriensystems wurden adäquat definiert.

- \+ Es wurden plausible Kategorien abgeleitet, die das Material stimmig widerzuspiegeln scheinen.



- \- Es wurde kein Kategoriensystem berichtet. Das ist als schwerwiegender Mangel der Arbeit einzustufen.

- \- Es wurde versäumt, ein Kategoriensystem aus den Hypothesen abzuleiten. Da Hypothesen vorhanden waren, sollten sich diese im Text bzw. in der inneren Struktur des Textmaterials wiederfinden - in den Kategorien also. 

- \- Der Ergebnisteil berichtet keine Kategorien; Kategorien sind aber das Herzstück einer qualitativen Inhaltsanalyse zumindest so, wie Sie im Unterricht besprochen wurde. Das Fehlen eines Kategoriensystems ist als schwerer Mangel zu werten.

- \- Der Ergebnisteil berichtet zwar Kategorien, jedoch erscheint die Darstellung als zu kurz gehalten und bruchstückhaft.








### Ergebnisdarstellung der Qualitativen Inhaltsanalyse {#ergebnissequali}

`+++`

- \+ Der Ergebnisteil stellt die Kategorien bzw. die Ergebnisse in differenzierter und klarer Weise dar. 
- \+ Der Ergebnisteil berichtet umfangreiches Material zu den Kategorien.


`---`



- \- Beim Berichten der Kategorien sollte die Essenz der Kategorie, d. h. ihre Bestimmungsstücke bzw. wesentlichen Inhalte berichtet werden. Die Kategorie ist zu definieren und ihr Wesensmerkmal zu erklären. Es reicht nicht, einige Textstellen des Interviewmaterials aufzureihen, die der Kategorie zugeordnet wurden.




- \- Das Kategoriensystem, welches aus einer qualitativen Studie resultiert, sollte nicht schwerpunktmäßig aus einer Sammlung von Interview-Zitaten o.ä. bestehen. Vielmehr sind die wesentlichen Inhaltsstücke einer Kategorie als Generalisierung, Abstrahierung und Zusammenfassung von Rohtextstellen zu erstellen. Die Rohtextstellen dienen lediglich dem Beleg; sie sind nicht der Inhalt der Kategorie. Diese Extrahierung der Kategorien bzw. deren Inhalte sind die zentrale intellektuelle/analytische Leistung der empirischen Arbeit. Ein Fehlen solcher Leistung ist ein substanzieller Mangel in der empirischen Ausarbeitung.

- \- Bei einer qualitativen Inhaltsanalyse ist beim Berichten einer Kategorie nicht entscheidend, was die Interview-Partner gesagt haben. Vielmehr ist die Blickrichtung umgekehrt: Es wird die Definition der Kategorie erläutert, die auf Basis der Aussagen der interviewten Personen begründet ist.




## Software zur Datenanalyse/R/RMarkdown (xxrrr) {#rrring}

### Explikation der Software und des Vorgehens

- \+ Der Name einer oder aller Software-Pakete zur Datenanalyse wurde expliziert.


`---`


- \- Idealerweise sind alle Software-Pakete, das Betriebssystem und die Versionsnummern zu explizieren.

- \- Ob ein Datensatz in MS Excel, OpenOffice, Notepad++, eine Oracle-Datenbank etc. gespeichert (betrachtet) wurde, ist irrelevant für diesen Bericht und sollte daher nicht berichtet werden (höchstens im Anhang).

- \- Da RStudio keinerlei Einfluss auf die Syntax, d.h. den Analysealgorithmus hat, ist es irrelevant für diesen Bericht, ob RStudio Verwendung fand. Demgegenüber ist es von hoher Relevanz, ob R (in welcher Version) und welche R-Pakete und -Funktionen (in welcher Version) Verwendung fanden, sprich: ob die Syntax reproduzierbar berichtet wurde.




### Allgemeine Beurteilung der R-Kompetenz (xxrkomp xxrcomp)

`+++`

- \+ Es wurde ein *sehr hohes Maß* an Kompetenz im Umgang mit R demonstriert.
- \+ Es wurde ein *hohes Maß* an Kompetenz im Umgang mit R demonstriert.
- \+ Die Arbeit lässt auf eine *insgesamt gute Kompetenz* im Umgang mit R schließen.
- \+ Es wurden *Verfahren/Funktionen in R angewendet, die nicht im Unterricht besprochen* wurden. Das lässt auf eine selbständige Arbeitsweise und gute Problemdurchdringung schließen.





- \+- Es wurde ein *durchschnittliches bis gutes Maß* an Kompetenz im Umgang mit R demonstriert.
- \+- Es wurde ein *durchschnittliches* Maß an Kompetenz im Umgang mit R demonstriert.


`---`


- \- Es wurde ein *geringes* Maß an Kompetenz im Umgang mit R demonstriert.
- \- Es wurde ein *sehr geringes Maß* an Kompetenz im Umgang mit R demonstriert.

- \- Das Maß an Kompetenz mit R konnte nicht überprüft werden, da (fast) keine Syntax in der Arbeit vorhanden war.


### Data Wrangling (xxwrangle)

- \- Anstatt Variablen mit `<- NULL` zu löschen, ist es einfacher, mit `dplyr::select` zu wählen.
- \- Anstatt Fälle mit dem Operator `[` zu wählen, ist es einfacher, `dplyr::filter` zu verwenden.
- \- Anstatt Variablennamen mit `names` und `[` zu ändern, ist es einfacher, `dplyr::rename` zu verwenden.
- \- Möchte man *Subgruppen vergleichen*, ist es eine suboptimale Lösung, den Datensatz in mehrere Teildatensätze aufzuteilen (z.B. mit `filter()`). Dadurch nimmt man sich die Möglichkeit, die Gruppen einfach bzw. direkt nebeneinander zu vergleichen oder macht sich das Leben komplizierter als nötig. Eine Möglichkeit zur gruppierten Analyse bietet mosaic: `verfahren(AV ~ gruppierungsvariable, ...)`. Alternativ kann man mit `group_by()` aus `dplyr` einen gruppierten Datensatz erzeugen und mittels weiterer Befehle (aus dplyr-komptabiblen Paketen) verrechnen (z.B. `summarise()`).
- \- Es sollten *keine technischen Bezeichnungen für Variablen* wie `F9r` verwendet werden im Hauptteil der Arbeit, sondern stets *sprechende Namen* (oder ggf. definierte Abkürzungen).



### Syntax-Formatierung (xxhighlightcode) {#syntaxformatierung}

`+++`

- \+ Die *Syntax* und/oder die R-Ausgaben wurden *optisch sehr ansprechend* und übersichtlich gestaltet (z. B. mit Syntax-Highlighting).
- \+ Die Syntax und/oder die R-Ausgaben wurden *weitgehend* optisch ansprechend und übersichtlich gestaltet.


- \+- Die Syntax und/oder die R-Ausgaben *nicht immer optisch ansprechend* und übersichtlich gestaltet.

`---`



- \- Die *Syntax wurde optisch wenig ansprechend* und/oder wenig übersichtlich gestaltet (z. B. als Screenshot oder Screenshot mangelnder optischer Qualität). Liegt Syntax nur als Screenshot vor, so ist es nicht möglich, die Syntax zu kopieren, um sie direkt auszuführen. Vielmehr wird der Leser gezwungen, abzutippen (oder anderswo zu suchen). Das ist nicht sehr "kundenfreundlich".
- \- Die Syntax und/oder die R-Ausgaben wurden ganz oder in Teilen als Screenshot dargestellt. Liegt Syntax nur als Screenshot vor, so ist es nicht möglich, die Syntax zu kopieren, um sie direkt auszuführen. Vielmehr wird der Leser gezwungen, abzutippen (oder anderswo zu suchen). Das ist nicht sehr "kundenfreundlich". Darüber ist die grafische Qualität nicht so gut wie bei z. B. Text, der als Vektorgrafik aufgebaut ist, also verlustfrei zoombar ist.


- \- In einem wissenschaftlichen Bericht dieser Art sollte keine R-Syntax bzw. kein unformatierter R-Output aufgeführt sein.


### R-Ausgaben (xxroutput) {#routput}

- \+  Die *R-Ausgaben* wurden optisch sehr ansprechend und *übersichtlich* gestaltet (z. B. mit Syntax-Highlighting).
- \+ Die R-Ausgaben wurden weitgehend optisch ansprechend und übersichtlich gestaltet.


`---`


- \- Die R-Ausgaben sind *teilweise optisch wenig ansprechend formatiert* (z. B. unübersichtlich). 
- \- Teilweise wurde sehr langer und/oder weniger informativer R-Output (kommentarlos) abgedruckt. Solcher R-Output ist wenig nützlich.

- \- Die Syntax und/oder die R-Ausgaben wurden ganz oder in Teilen als Screenshot dargestellt. Liegt Syntax nur als Screenshot vor, so ist es nicht möglich, die Syntax zu kopieren, um sie direkt auszuführen. Vielmehr wird der Leser gezwungen, abzutippen (oder anderswo zu suchen). Das ist nicht sehr "kundenfreundlich". Darüber ist die grafische Qualität nicht so gut wie bei z. B. Text, der als Vektorgrafik aufgebaut ist, also verlustfrei zoombar ist.

- \- In *wissenschaftlichen Berichten dieser Art sollte kein unformartierter R-Code oder R-Ausgaben in den Hauptteil* aufgenommen werden. Vielmehr sollten auf Basis der R-Ausgaben ansprechende, informative, wohl strukturierte Textpassagen, Diagramme oder Tabellen erstellt werden. Den Lesenden soll es nicht aufgebürdet werden, sich selber "durchzupflügen", sondern eine gute Arbeit stellt die Ergebnisse wohl aufbereitet dar. Vermeiden Sie es, unformatierte R-Ausgabe in den Hauptteil einer solchen Arbeit aufzunehmen.


### RMarkdown {#rmarkdown}

- \+ Die Verwendung von *RMarkdown* ist gerade bei Berichten dieser Art sehr sinnvoll; insofern ist dieser Ansatz begrüßenswert.

- \- Hinweise (*Messages*) von in R-Chunks ausgeführten Befehlen wie "Loading required package: dplyr" oder "The following packages are masked XXX" *sollten besser unterdrückt werden* und nicht im Hauptteil des Berichts erscheinen. Dafür ist die Chunk-Option "message = FALSE" sinnvoll: z. B. "```{r message = FALSE}".


### Beschreibung des Datensatzes (xxdatadescription) {#datasetdescription}

- \+ *Relevante Aspekte des Datensatzes* wurden beschrieben.
- \+ Die *Quelle* des Datensatzes wurde benannt. Damit kann die Analyse ggf. besser überprüft werden. Ein zentraler Bestandteil zur Reproduzierbarkeit ist damit gewährleistet.

`---`


- \- Nicht alle relevanten Aspekte des Datensatzes wurden beschrieben.
- \- Die untersuchten Variablen des Datensatzes wurden nicht (alle) bzw. nicht ausführlich (genug) beschrieben.
- \- Es *fehlt ein Hinweis zur Quelle des Datensatzes* (zumindest eine URL wäre wünschenswert). Nur mit der Quelle kann die Analyse in allen Schritten überprüft werden. Ein zentraler Bestandteil zur Reproduzierbarkeit wäre damit gewährleistet gewesen, fehlt aber in der vorliegenden Analyse.


## Sonstige Kommentare zum Methodenteil
- \- Die eingesetzten Methoden sollten \*nicht\* in der Arbeit erläutert werden, sofern es sich gängige Methoden handelt (die im Unterricht erläutert werden; Beispiele: "Der t-Test wird verwendet um XXX", "Qualitative Methoden zeichnen sich aus durch YYYY"). Das Wissen um gängige Methoden wird beim Leser vorausgesetzt. Erörtern Sie nicht, wie eine Methode funktioniert, sondern nutzen Sie den knappen Platz, um zu erklären, was Sie machen. Man soll also in so einer Arbeit kein "Lehrbuch schreiben.


- \- Die vorliegende Arbeit verwendet den Term *"beeinflussen"* an einer (oder mehreren) Stellen (z. B. in den Hypothesen oder im Ergebnisteil). Der Begriff suggeriert einen* kausalen Anspruch *in der Hypothese; ein Anspruch, der das *Design* (bzw. die interne Validität des Designs) der vorliegenden Studie nicht gerecht wird.





## Beurteilung des Methoden-/Ergebnisteils insgesamt

- \+ Insgesamt wurde weitgehend relevante empirisch-methodische Verfahren sinnvoll und methodisch gewandt verwendet.
- \+ Die Anwendung — sowohl in Qualität als auch in Quantität — zeugt in fast allen Punkten von sehr gutem methodischem Verständnis.
- \+ Insgesamt finden sich nur wenige Fehler in der Verwendung von relevanten empirisch-methodischen Verfahren.
- \+ Ein gelungener Einsatz von technischen/EDV-Werkzeugen zur Optimierung der Arbeit ist festzustellen.
- \+ Adäquater Gebrauch der empirisch-wissenschaftlichen Methodik ist insgesamt festzustellen.
- \+ Sehr gutes Verständnis der empirisch-wissenschaftlichen Methodik ist festzustellen.
- \+ Das methodische Vorgehen anschaulich und gut verständlich erläutert.

- \+- Insgesamt ist das Niveau und der Umfang des methodisch-empirischen Teils als von mittlerer Güte einzuschätzen. 

- \- Zentrale empirisch-methodische Konzepte wurden falsch eingesetzt.
- \- Es sind einige kleinere methodische Mängel aufzufinden.
- \- Die Anwendung von empirischen Methoden, wie es in der vorliegenden Arbeit demonstriert wird, weist klares Verbesserungspotenzial auf.

- \- Die Datenanalyse weist große Lücke auf.







# INHALT (xxinh)---------------------------------------- {#inhalt}

## Gliederung (xxtoc)


### Gliederung -- Inhalt {#gliederunginhalt}
- \+ Die Gliederung der Arbeit ist stimmig.

- \+ Die anteilige Aufteilung der Gliederungspunkte zu den einzelnen Hauptteilen der Arbeit ist wohl proportioniert.

- \+ Aufbau und Gliederung der Arbeit sind wohl durchdacht.

- \+ Die Gliederung spiegelt den Titel adäquat wider.
- \+ Die Gliederung spiegelt die Forschungsfrage adäquat wider.


`---`



- \- Ein Abschnitt *"Stand der Forschung"*, *"Forschungsstand"* o. Ä. ist *nicht sinnvoll*, denn der Stand der Forschung sollte sich in praktisch allen Theoriekapiteln wiederfinden. Wenn der Stand der Forschung also nur in einem Kapitel angesprochen wird, was steht dann in den übrigen Kapiteln?

- \- Die Gliederung spiegelt die Forschungsfrage bzw. den Titel nicht zur Gänze bzw. *nicht komplett treffend wider*.

- \- Das *Inhaltsverzeichnis* sollte *alle Teile der Forschungsfrage* aufgreifen bzw. widerspiegeln. Lautet die Forschungsfrage etwa *"A führt zu B"*, so sind im Inhaltsverzeichnis für den Theorieteil (zumindest) *drei Unterkapitel* aufzuführen: A, B und der (möglicherweise kausale) Zusammenhang von A und B. Die vorliegende Arbeit berücksichtigt diesen Aspekt nicht ausreichend. 


### Gliederung -- Formatierung/Formales {#gliederungformat}

`+++`

- \+ Die Gliederung/das Inhaltsverzeichnis ist optisch gelungen und hilft dem schnellen Erfassen.
- \+ Die Gliederung ist optisch gut strukturiert, was das Erfassen der Gedanken des Textes unterstützt.

- \+ Die Einträge des Inhaltsverzeichnis sind verlinkt (zu den entsprechenden Kapiteln im Hauptteil), so dass ein flüssiges, flottes Lesen bzw. Rezipieren des Berichtes möglich ist; dies trägt zur "Leserfreundlichkeit" des Berichts bei. Gleiches gilt für Zitationen und Referenzen auf Kapitel, Abbildungen oder Tabellen. Auch hier ist ein Link im Dokument nützlich und sollte bereitgestellt werden.

`---`



- \- Die Gliederung/das Inhaltsverzeichnis könnte *optisch besser strukturiert* sein. Dies kann u. a. durch Einrücken (horizontale Nähe und Distanz) und durch und Abstände zwischen Kapiteln (vertikalem Raum) erreicht werden (innerhalb der Unterkapitel eines Kapitels ist mehr vertikaler Raum zu lassen als zwischen zwei Kapiteln; die Kapitelgrenze ist durch zusätzlichem vertikalem Raum hervorzuheben). Das Ziel ist optisch zu verdeutlichen, welche Gedanken zur gleichen bzw. zu anderen Gruppen gehören (also einander näher oder weiter entfernt gedacht stehen). In der vorliegenden Arbeit wurden diese Aspekte nicht (komplett) berücksichtigt.

- \- Verzeichnisse (Inhaltsverzeichnis oder Literaturverzeichnis) sollten *linksbündig* formatiert sein (ohne Einzug in der ersten Zeile).
- \- Das Inhaltsverzeichnis sollte (bei so einer kurzen Arbeit) geschickterweise *nur eine Seite lang* sein.

- \- Eine *Gliederung fehlt*; sie sollte stets vorhanden sein, da sie die Orientierung auch bei "kleineren" Arbeiten erleichtert.
- \- Verzeichnisse (Inhaltsverzeichnis oder Literaturverzeichnis) sollten *linksbündig* formatiert sein.


- \- Gliederungspunkte sollten stets *mehr als einen Unterpunkt haben*, ansonsten verzichtet man besser auf die untergeordnete Gliederungsebene.

- \- Teile wie Literaturverzeichnis oder Anhang werden in der Gliederung nicht nummeriert. Dieser Punkt wird in der vorliegenden Arbeit nicht korrekt umgesetzt.


- \- Wären die Einträge des Inhaltsverzeichnis *verlinkt* gewesen (zu den entsprechenden Kapiteln im Hauptteil), so wäre ein flüssigeres, flotteres Lesen bzw. Rezipieren des Berichtes möglich gewesen; die "*Leserfreundlichkeit*" des Berichts wäre damit höher gewesen als es im vorliegenden Bericht der Fall ist.  Gleiches gilt für *Zitationen* und *Referenzen* auf Kapitel, Abbildungen oder Tabellen. Auch hier ist ein Link im Dokument nützlich und sollte bereitgestellt werden.


- \- *Vertikale Abstände* im Text sollten so gesetzt sein, dass sie Sinnzusammenhänge wie Kapitel verdeutlichen. Daher sollte z. B. nach der Überschrift zum Text des Absatzes weniger Abstand sein als zwischen Absatzende und neuer Überschrift. In der vorliegenden Arbeit wurden die Abstände zwischen Sinnabschnitten nicht durchgehend sinnvoll gewählt.

- \- Der *Abstract* soll nicht in der Gliederung erscheinen.

- \- Teile wie *Literaturverzeichnis* oder Anhang werden in der Gliederung *nicht nummeriert*. Dieser Punkt wird in der vorliegenden Arbeit nicht korrekt umgesetzt.

- Das *Literaturverzeichnis* ist im Inhaltsverzeichnis aufzuführen.


- Auf der ersten Gliederungsebene sollte die klassische Einteilung in *Einleitung*, *Theorie*, *Methode*, *Ergebnisse* und *Diskussion* gewählt werden.





## Titel und Titelseite (xxtitel)

### Titel -- Inhalt Beurteilung {#titelinhalt}

`+++`

+ \+ Der Titel der Arbeit ist *pointiert*, konzise und gut passend.
+ \+ Der Titel der Arbeit ist *passend.*
+


`---`


- \- Der Titel der Arbeit ist *sehr (zu) lang* und damit nicht sehr eingängig.
- \- Der Titel der Arbeit ist *zu vage/unpräzise* oder nicht griffig genug.
- \- Der Titel der Arbeit ist *sehr kurz *und damit nicht präzise genug.
- \- Der Titel ist *zu kurz *und damit nicht präzise genug; besser wäre ein präziserer Titel.



- \- Es *fehlt* ein Titel.



### Titel -- Inhalt Kommentare {#titelinhaltkommentar}

`+++`

- \+ Die *Gliederung* spiegelt den *Titel* adäquat wider.



- \+ Der Titel spiegelt die *Forschungsfrage* adäquat wider. Das ist sinnvoll, denn die Forschungsfrage kann als zentrale Informationseinheit zu einer Studie verstanden werden und verdient daher eine prominente Platzierung.



- \+- Der Titel gibt einige zentrale Aspekte der Forschungsfrage und/oder des Studiendesigns wieder, aber hätte noch *von weiterer Präzisierung profitiert*.




`---`


- \- Der Titel spiegelt den *zentralen Inhalt* der Arbeit *nicht präzise* genug wider. 

- \- Das *Inhaltsverzeichnis* der Arbeit findet sich in seinen Schwerpunkten *nur in Teilen im Titel* wieder.


- \- Der Titel *hätte präziser formuliert werden könne*n, z.B. um die Richtung der *Hypothesen* oder Art des *Studiendesigns* zu erwähnen.
- \- Besser wäre der Titel noch, wenn die Art des *Studiendesigns* berichtet werden würde* ("Das Paarungsverhalten der südsibirischen Kreuzschwanzschwalbe blablabla - Eine *querschnittliche Beobachtungsstudie*").

- \- Die *Forschungsfrage* geht aus dem Titel *nicht (klar)* genug hervor. Da die Forschungsfrage vermutlich der wichtigste Teil des bzw. die wichtigste Information zum wissenschaftlichen Berichts darstellt, sollte die Forschungsfrage auf jeden Fall klar formuliert werden. Ein Fehler der Forschungsfrage in diesem Sinne ist ein klarer Fehler.



###  Titel -- Formatierung {#titelformatierung}

`+++`

+ \+ Der Titel ist auf der Titelseite *gut platziert*, so dass die zentrale Bedeutung des Titels optisch-gestalterisch prominent platziert ist.

+ \+ Die *Zäsur* in der Mitte des Titels (in Form eines Bindestrichs, Doppelpunkt oder Fragezeichens) gliedert den Titel in sinnvoller Weise; dadurch steigt die Lesbarkeit des Titels.

+ \+ Durch die *Gliederung* des *Titels* in *Haupt- und Untertitel* steigt die Lesbarkeit des Titels.



`---`


- \- Der Titel könnte auf der Titelseite *noch besser "in Szene gesetzt" werden*, so dass die zentrale Bedeutung des Titels optisch-gestalterisch deutlicher zutage tritt (z. B. ist der Titel zu klein gesetzt oder hat nicht genug Abstand zum Rest des Textes).

- \- Zwar zeigen aktuelle Studien, dass die Lesbarkeit von SCHRIFT IN *GROSSBUCHSTABEN* NICHT geringer sein muss, als Schrift in Groß- und Kleinschreibung (Arditi, A., & Cho, J. (2007). Letter case and text legibility in normal and low vision. Vision research, 47(19), 2499–2505. doi:10.1016/j.visres.2007.06.010). Allerdings sollte die Textmenge von sog. "All Caps Text" (Großschreibung) sehr sparsam eingesetzt werden, und für besonders wichtige Wörter (zur Aufmerksamkeitssteuerung etwa auf einer Webseite) verwendet werden. (Lange) Titel oder Überschriften sollten daher besser nicht in Großbuchstaben gesetzt werden.

- \- Das *Logo* auf der Titel entspricht nicht der Relevanz des Logos; besser wäre es, das Logo kleiner zu halten, da dem Logo keine große (inhaltliche) Bedeutung zukommt.


## Forschungsfrage, Problemstellung und Zielsetzung (xxfofrage) {#fofrage}


`+++`

- \+ Die Forschungsfrage wurde *klar formuliert*.
- \+ Die Forschungsfrage wurde klar und an geeigneter Stelle (z. B. am Ende der Einleitung) formuliert.
- \+ Das Ziel der Arbeit wurde klar herausgestellt.
- \+ Das Ziel der Arbeit wurde herausgestellt.


- \+- Das Ziel der Arbeit wurde herausgestellt, hätte aber noch von Präzisierung profitiert.
- \+ Die Forschungsfrage wurde stringent beantwortet.



`---`

- \- Die *Forschungsfrage nicht klar genug herausgestellt* oder findet sich nicht an dem einschlägigen Platz (Einleitung oder zu Beginn des Theorieteils).
- \- Das Ziel der Arbeit sollte in einem oder zwei Sätzen prägnant expliziert sein.
- \- Ein deutliches Manko der Arbeit ist das *Fehlen einer expliziten Forschungsfrage*.
- \- Es wird nicht deutlich genug klar, welches Problem (welche Frage) die Arbeit versucht zu lösen. Dadurch wird viel Potenzial verschenkt. 

- \- Es sollten *nicht mehrere Forschungsfrage formuliert werden*, sondern besser nur eine einzige. Oder zumindest muss es eine übergreifende Forschungsfrage geben. Stehen mehrere Forschungsfragen nebeneinander, ist der wesentliche Beitrag der Arbeit weniger klar erkenntlich. Außerdem ist es zweifelhaft, ob eine vergleichsweise kurze Arbeit mehrere Fragen in nützlicher Tiefe bearbeiten kann. Ich empfehle daher, die Arbeit auf die Beantwortung einer Frage hin zuzuspitzen. Man braucht i. d. R. keine Sorge haben, dass es nicht genug Stoff (Literatur und Gedanken) gibt, um eine Arbeit zu füllen; diese Sorge ist fast immer unbegründet. 

- \- Eine *Forschungsfrage in einer explorativen Arbeit sollte als offene Frage formuliert sein* (etwa: "Was sind die Gründe für xxx?", "Wie kann man die Produktivität steigern?"). Im Gegensatz dazu weisen *hypothesenprüfende Arbeiten zumeist geschlossenen (oder skalierende) Fragen auf* ("Parken Frauen im Schnitt schneller ein als Männer?"). Dieser Punkt wurde in der vorliegenden Arbeit nicht ausreichend berücksichtigt.



## Bezug zur Praxis oder sonstigen wichtigen oder aktuellen Themen {#praxisbezug}


`+++`


- \+ Der Bezug zu *aktuellen Themen* wurde herausgestellt.
- \+ Der *Praxisbezug* der Arbeit wurde gut herausgearbeitet.
- \+ Der Autor/die Autorin nähert sich auf kreative und durchdachte Weise einem interessanten und forschungsbedeutsamen Thema.
- \+ Der Autor/die Autorin bewies gute Problemlösungskompetenz.


## Roter Faden (xxrot) {#roterfaden}

`+++`

- \+ Titel, Forschungsfrage/Hypothesen und Theorieteil passen zueinander.
- \+ Titel, Forschungsfrage/Hypothesen und Datenanalyse passen zusammen.
- \+ Titel, Forschungsfrage/Hypothesen und Datenanalyse passen großteils zusammen.


- \+ Ein häufiger Fehler in vergleichbaren Arbeiten besteht darin, dass der Theorieteil eine Lücke aufweist. Und zwar sind viele Forschungsfragen formal mit dem Gerüst A -> B (A beeinflusst B) fassbar; allerdings übersehen einige Schreibende, im Theorieteil eben nicht nur A und B vorzustellen, sondern auch über den (möglicherweise) kausalen *Zusammenhang* beider Merkmale zu schreiben. In der vorliegenden Arbeit wurde dieser Fehler nicht begangen, sondern korrekterweise alle drei Aspekte im Theorie adressiert.



`---`


- \- Titel, Forschungsfrage/Hypothesen und Theorieteil passen teilweise zueinander.
- \- Titel, Forschungsfrage/Hypothesen und Theorieteil passen nicht zueinander.

- \- Titel, Forschungsfrage/Hypothesen und Datenanalyse passen nur bedingt zusammen.

- \- Im Theorieteil wird versäumt, auf alle Aspekte, die in der Forschungsfrage/den Forschungsfragen vorkommen, einzugehen.

- \- Ein häufiger Fehler in vergleichbaren Arbeiten besteht darin, dass der Theorieteil eine Lücke aufweist. Und zwar sind viele Forschungsfragen formal mit dem Gerüst "A -> B" (A beeinflusst B) fassbar; allerdings übersehen einige Schreibende, im Theorieteil eben nicht nur A und B vorzustellen, sondern auch über den (möglicherweise) kausalen Zusammenhang beider Merkmale zu schreiben. In der vorliegenden Arbeit wurde nicht ausreichend auf den Zusammenhang von "A" und "B" eingegangen.

- \- Damit ein "roter Faden" in der Arbeit erkennbar ist, ist es notwendig, dass im Theorieteil *alle Aspekte der der Forschungsfrage des Typs "A -> B"* diskutiert werden, nämlich A, B und der Zusammenhang von A und B (möglicherweise kausaler Natur). Häufig sind das zwei Phänomen und (das wird häufig vergessen) eine Erklärung zum Einfluss oder zum  Zusammenhang der Phänomene. Gleiches gilt für die Hypothese; es sollten nur Hypothesen (in einer quantitativen bzw. nicht-explorativen Arbeit) formuliert werden, die zuvor im Theorieteil erläutert wurden. Dieser Aspekt wird in der vorliegenden Arbeit nicht (komplett) berücksichtigt.






## (Güte der) Problemlösung


`+++`

- \+ Der Ansatz der Problemlösung ist breit angelegt.
- \+ Der Ansatz zur Problemlösung erreicht eine sehr gute Tiefe.
- \+ Der Ansatz zur Problemlösung erreicht eine gute Tiefe.
- \+ Der Ansatz zur Problemlösung erreicht eine angemessene Tiefe.

- \+- Der Ansatz zur Problemlösung erreicht eine mittlere Tiefe.

`---`


- \- Der Ansatz zur Problemlösung erreicht nicht eine hohe Tiefe.
- \- Der Ansatz zur Problemlösung erreicht nur eine geringe Tiefe.


## Argumentation und inhaltliche Güte {#argumentation}

### Argumentation - Beurteilung

`+++`

- \+ Der *Theorieteil leitet sich stringent aus der Forschungsfrage* ab.
- \+ Die wissenschaftliche Fundiertheit des untersuchten Konstrukts wird gut erörtert.
- \+ Es wurde auf wissenschaftlich angemessene Art und Weise argumentiert (z. B. unparteiisch und mit kritischer Distanz).
- \+ Der Ergebnisteil schildert die wesentlichen Ergebnisse treffend/pointiert.

- \+ Die Arbeit rekurriert zwar auf theoretisch fragwürdiges Material (z. B. AIDA-Modell, Maslows Bedürfnispyramide oder das Johari-Fenster), allerdings wird diese Einschränkung erkannt und kritisch diskutiert. Besser wäre es noch gewesen, auf wissenschaftlich fragwürdiges Material gänzlich zu verzichten bzw. es durch Quellen höherer Qualität einzutauschen.



`---`

- \- Der Ergebnisteil schildert die wesentlichen Ergebnisse nicht treffend/pointiert.
- \- Der Theorieteil ist zu wenig differenziert.
- \- Das empirisch-methodisch Vorgehen wurde zu knapp oder gar nicht beschrieben.

- \- Der Theorieteil fußt (in Teilen) auf alten, falsifizierten oder wissenschaftlich überholten oder fragwürdigen Theorien bzw. Modellen (z. B. AIDA-Modell, Maslows Bedürfnispyramide oder das Johari-Fenster).
-

### Argumentation - Hinweise

`+++`


- \+ Theoretische Behauptungen (z. B. "A führt zu B") werden anhand von empirischen Ergebnissen untermauert. Das ist ein gutes Beispiel für gelungene wissenschaftliche Argumentation.

- \+ Wissenschaftliches Argumentieren zeichnet sich (auch) darin aus, dass Befunde nicht als (unabdingbare) Wahrheiten hingestellt werden, sondern als das, was sie zumeist sind: Vermutungen mit einiger empirischer Unterstützung, aber noch längst nicht zweifelsfreie "Naturgesetze" (wenn es das überhaupt gibt). Diese Art des Argumentieren lässt sich an einigen Stellen schön in der vorliegenden Arbeit nachzeichnen. Beispiele für gute Argumentationsweisen in diesem Sinne sind: "Laut XXX (2019) ist ...", "Insgesamt deutet die Studienlage darauf hin, dass ...", "Nach Süß und Sauer (2019) lassen sich drei Varianten unterscheiden ...", "Die Daten unterstützen die Hypothese nicht".

- \+ Sofern die Forschungsfrage strukturell vom Typ "A führt zu B" oder "A beeinflusst B" ist, so sollte der Theorieteil nicht nur auf A und B, sondern auch auf den (kausalen) Zusammenhang von A und B, den Einfluss von A auf B also, eingehen. Dies ist in der vorliegenden Arbeit adäquat berücksichtigt worden.

- \+ Der Text der vorliegenden Arbeit ist in Teilen begrüßenswert nahe an den Interna der empirischen Evidenzbeurteilung; dazu zählen als Beispiel die Aufschlüsselung der Qualität von Messinstrumenten anhand gängiger Kriterien (wie Cronbachs Alpha oder Interrater-Reliabilität) oder die Erläuterung von Zusammenhangskoeffizienten (wie Pearsons r).


`---`

- \- Im Theorieteil sind prototypisch drei Aspekte zu erörtern: 1. Die UV, 2. die AV und 3. der (kausale) Zusammenhang von UV und AV. In der vorliegenden Arbeit wurde es versäumt, einen dieser drei Aspekte  in ausreichendem Maße zu erörtern (nämlich 3., den (kausalen) Zusammenhang von UV und AV). 

- \- Behauptungen (Aussagen) sind grundsätzlich mit einer Quelle zu belegen. Die vorliegende Arbeit hält dies nicht durchgängig ein.

- \- *Ergebnisse und Diskussion sind strikt zu trennen* - die Arbeit hält dies nicht durchgängig durch. Der Ergebnisteil berichtet Fakten; die Diskussion tut das nicht. In der Diskussion wird über Fakten gesprochen. Damit ist die Diskussion deutlich subjektiver als der Ergebnisteil. In der Wissenschaft versucht man, Fakten von Meinungen deutlich zu trennen, da es sich um grundverschieden Dinge handelt.
- \- Grundlegende methodische Verfahren sollten hier nicht erläutert werden.

- \- Der Theorieteil versäumt es (zu einem großen Teil), auf den Zusammenhang oder den Einfluss der untersuchen Konstrukte ("X", "Y") untereinander einzugehen. Es ist aber eine wesentliche Aufgabe, im Theorieteil zu erläutern, wie X auf Y wirkt oder warum X und Y statistisch zusammenhängen könnten.

- \- Anstatt von "technischen" Variablennamen wie "xkcd_42_trmp" sollten besser *sprechende Variablennamen* verwendet werden wie "Experimentalgruppe" oder "Anzahl richtiger Wörter".

- \- *Hinweise wie "durch umfangreiche Recherchen und Analysen erreichte die Arbeit XXX" sind nicht angebracht*; in einer Arbeit sollte in *wissenschaftlich-nüchternem Duktus* berichtet werden. Es widerspricht dem Duktus wissenschaftlichen Schreibens a. global-unspezifisches Vorgehen anstelle von genauer Beschreibung anzuführen, b. die eigene Arbeit (frühzeitig) zu loben und c. durch Adjektive Emphasis herauszukehren anstelle von sachlicher Erörterung.

- \- Die Argumentationsweise der vorliegenden Arbeit ist stellenweise von kausalen Aussagen zur Forschungsfrage geprägt: "Die Ergebnisse bestätigen, dass X sich auf Y auswirkt". Allerdings lässt theoretischer und/oder empirischer Aufbau der Arbeit keine solchen starken Aussagen zu. Wissen über die Grenzen der eigenen (empirischen) Analyse - im positiven wie im negativen Sinne - sind essenzielle Kompetenz im wissenschaftlichen Arbeiten. Entsprechendes wurde in der vorliegenden Arbeit nicht durchgängig berücksichtigt.

- \- Der *Theorieteil sollte nicht als "kleines Lehrbuch"* missverstanden werden. Insbesondere sind nur Bestandteile der empirisch getesteten Modelle darzustellen. Grundlagen wie z. B. der Wahrnehmung oder Kognition im Allgemeinen sind zu weitführend und sollten vermieden werden.  Die vorliegende Arbeit hält das nicht durchgehend durch.

- \- *Zitationen* aus allgemeinen Psychologie-Lehrbüchern wie Meyers, *Zimbardo* o.Ä. sind Anzeichen von geringer fachlicher Durchdringung und sollten vermieden werden. Besser sind spezifische Lehrbücher zum Thema der Arbeit; noch besser sind Fachartikel.

- \- Ein wesentliches Merkmal wissenschaftlicher Argumentation ist es, nur Dinge zu behaupten, deren man sich sicher ist. Zu anderen Dingen schweigt man entweder oder man verdeutlicht den Grad der Ungewissheit. Es ist kein Mangel, sich Dinge nicht sicher zu sein. Die meisten interessanten Dinge (in der Wissenschaft) sind nicht (komplett) sicher. 

- \- Anstelle von Sätzen wie "Es gibt drei Arten von Problemen ...", sollte man besser schreiben in der Art von "Sauer und Lustig (2017) unterscheiden drei Arten von Problemen nämlich blabla" oder "Nach Sauer und Lusting (2017) gibt es drei Arten von Problemen, wobei man laut Süß (2018) noch ein viertes Problem blablabla". Diese Art der Formulierung entspricht eher der intellektuellen Redlichkeit, denn es ist schwer abzusichern, dass es genau drei Arten von Problemen gibt (nicht mehr und nicht weniger) und dass es genau die gerade dargestellten sind (und keine anderen).



## Einführung/Einleitung (xxeinl)

- \+ Die Arbeit beginnt mit einer sinnvollen Einführung.
- \+ Die Relevanz das Themas wird anhand verschiedener Statistiken (wie Umsatz, Anzahl Personen oder dergleichen) belegt. Das ist eine sinnvolle Art, die Relevanz eines Themas einzuleiten.


## Theorieteil (xxtheo) {#fachkenntnis}
### Theorieteil - Beurteilung

`+++`

- \+ Die fachlich-theoretische Ausarbeitung ist von *außergewöhnlich hoher Güte*.
- \+ Die fachlich-theoretische Sachkenntnis ist *sehr hoch*.
- \+ Die fachlich-theoretische Sachkenntnis ist *hoch*.
- \+ Die fachlich-theoretische Sachkenntnis ist *gut bis sehr gut*.

- \+ Die fachlich-theoretische Sachkenntnis ist *gut.*
- \+ Die fachlich-theoretische Sachkenntnis ist *insgesamt gut*.

- \+ Umfang und/oder Tiefe des Theorieteils von hoher Stärke.




`+-`


- \+- Die fachlich-theoretische Sachkenntnis ist insgesamt *befriedigend bis gut*.
- \+- Die fachlich-theoretische Sachkenntnis ist insgesamt *befriedigend.*
- \+- Die fachlich-theoretische Sachkenntnis ist insgesamt *befriedigend bis ausreichend*.


`---`

- \- Die fachlich-theoretische Sachkenntnis ist insgesamt *ausreichend.*
- \- Die fachlich-theoretische Sachkenntnis ist *mangelhaft.*



- \+- Der Umfang und/oder die Tiefe des Theorieteils ist von mittlerer Stärke.



- \- Umfang und/oder Tiefe des Theorieteils ist/sind von eingeschränkter Güte.
- \- Umfang und/oder Tiefe des Theorieteils ist/sind gering.
- \- Umfang und/oder Tiefe des Theorieteils ist/sind nicht ausreichend.




### Umfang des Theorieteiles

`+++`

- \+ Der Theorieteil ist umfangreich; es wird ein breiter Überblick an theoretischen Grundlagen vermittelt.


- \+ Der Umfang des Theorieteils ist *hoch.*
- \+ Der Umfang des Theorieteils ist *angemessen.*

- \+- Der Umfang des Theorieteils ist  von *mittlerer Stärke*.


`---`


- \- Der theoretischer Teil *könnte tiefer und breiter ausgebaut* sein.
- \- Der Theorieteil hat einen relativ geringen Anteil an der Gesamtmenge des Textes. Die Arbeit würde von einem größeren Anteil des Theorieteiles profitieren.

- \- Umfang und/oder Tiefe des Theorieteils ist/sind von *eingeschränkter Güte*.
- \- Umfang und/oder Tiefe des Theorieteils ist/sind *gering.*
- \- Umfang und/oder Tiefe des Theorieteils ist/sind *nicht ausreichend*.



- \- Der Theorieteil ist insgesamt *kurz* geraten.
- \- Der Umfang des theoretischen Teils hätte von *stärkerer Ausarbeitung bzw. größerem Umfang profitiert*.


- \- Der Theorieteil lässt wesentliche Aspekte des Themas außen vor; die Ausarbeitung weist *deutliche Lücken* auf.
- \- Die fachlich-psychologische *Erklärung* zum angesprochenen Phänomen *fehlt fast vollständig*.
- \- Die fachlich-psychologische *Erklärung* zum angesprochenen Phänomen *fehlt zum großen Teil*.
- \- Der theoretischer Teil könnte *tiefer und breiter ausgebaut* sein.


### Qualität des Theorieteiles

`+++`

- \+ Der Theorieteil baut auf gut *etablierten und aktuellen Theorien auf*; damit ist das theoretische Fundament der Arbeit als solide zu betrachten.
- \+ Der Theorieteil bezieht sich in *hohem Maße auf wissenschaftliches Material*.
- \+ Der Theorieteil bezieht sich auf *einiges wissenschaftliches Material*.
- \+ Die Arbeit *bezieht aktuelle Überblicksarbeiten mit ein*; das ist begrüßenswert, da diese Arbeiten die in der Regel beste Stufe an Evidenzqualität aufweisen.


`+-`


- \+- Der Theorieteil hätte von einem ausgiebigerem Rückgriff auf wissenschaftliches Material hoher Güte profitiert.

`---`






- \- Der Theorieteil lässt wesentliche Aspekte des Themas außen vor; die Ausarbeitung weist *deutliche Lücken* auf.
- \- Die fachlich-psychologische Erklärung zum angesprochenen Phänomen *fehlt fast vollständig*.
- \- Die fachlich-psychologische Erklärung zum angesprochenen Phänomen *fehlt zum großen Teil*.
- \- Es liegen *substanzielle Fehler in der Sachkenntnis* vor.
- \- Die *Diskussion* psychologischer Aspekte des fachlich-inhaltlichen Themas *fehlt* fast komplett.
- \- *Es fehlt ein kausales Modell* bzw. eine Erklärung, warum die Effekte (auf die AV) erwartet werden und inwiefern die UV diesen Effekt induzieren sollten. Dies ist ein schwer wiegender Mangel, fehlt doch die grundlegende Rationale, also der eigentliche Grund, warum der Versuchsaufbau so erstellt wurde.
- \- Ein *ausgiebiger(er) Rückgriff auf aktuelle Forschungsarbeiten wäre zweckdienlich* gewesen.
- \- Der Theorieteil bezieht sich in in nur *geringem Maße auf wissenschaftliches Material*.




- \- Ein stärkerer *Rückgriff auf aktuelle Überblicksarbeiten hätte die Arbeit bereichert*.


- \- Es finden sich *kaum Quellen zur Forschungsfrage* im Literaturverzeichnis.
- \- *Unveröffentlichte Skripte* sind keine qualitativ hochstehenden Quellen und sollten daher besser gemieden werden.
- \- Eine zentrale Aufgabe des Theorieteiles ist es, *Erklärungen für das "Warum" der zentralen Behauptungen der Arbeit vorzuschlagen*. Lautet eine zentrale Behauptung der Arbeit "A hat einen Einfluss auf B", so sollte der Theorieteil - neben der Darstellung der Phänomene A und B - im Wesentlichen Erklärungen anbieten, warum A einen Einfluss auf B haben könnte. Handelt es sich bei A und/oder B um ein psychologisches Phänomen, so sind (auch und vor allem) psychologische Theorien anzuführen.

- \- Die *Aufgabe des Theorieteiles ist es, die Forschungsfrage zu erläutern* - nicht mehr (also keine Phänomene, die nicht in der Forschungsfrgage spezifiziert sind) und nicht weniger (also alle Aspekte, die in der Forschungsfrage aufgegriffen werden). Wesentlich ist, dass die Erläuterung auf bestehende (wenn möglich, gut etablierte) Theorien zurückgreift. Daten bzw. Beobachtungen sollten stets im Lichte einer Theorie diskutiert - etwa der Dissonanztheorie, der Theorie des schnellen und langsamen Denkens oder der Selbstbestimmungstheorie nach Deci und Ryan, um einige willkürliche Beispiele zu nennen. Es ist bzw. es wäre ein substanzielles Versäumnis, auf Erläuterungen von "Fakten" im Lichte einer Theorie zu verzichten. Dabei ist die Leistung einer Theorie darin zu spezifizieren, dass Beobachtungen ("Fakten") durch (z.B. psychologische) zumeist nicht direkt beobachtbare Vorgänge oder Strukturen in ihrer kausalen Bedingtheit aufgeschlüsselt werden. Dieser Punkt findet in der vorliegenden Arbeit nicht genug Beachtung. 

- \- Der Theorieteil sollte *nicht als kleines Lehrbuch missverstanden* werden. Leitidee sollte sein, alle Phänomene der Forschungsfrage zu erläutern - aber nicht mehr. So ist es falsch, die Grundlagen der Persönlichkeit oder gar einen Überblick über Persönlichkeitstheorien aufzuführen, wenn z.B. "Extraversion" ein Bestandteil der Forschungsfrage ist. Der Theorieteil sollte also möglichst nah an der Forschungsfrage dran sein, je "weiter weg" ein Inhaltsteil des Theorieteils von der Forschungsfrage ist, desto weniger Berechtigung gibt es, diesen Inhaltsteil auszuführen. Dieser Punkt wird im Theorieteil der vorliegenden Arbeit nicht (komplett) berücksichtigt.


### Theorieteil - Theorien und Kausalmodell

`---`

- \- Die Forschungsfrage legt ein Kausalmodell der Form "X wirkt auf Y" nahe, aber der Theorieteil geht nicht (ausführlich genug) auf ursächliche Erläuterungen ein. Es wird daher nicht klar genug herausgearbeitet, wie - vermöge welcher Mechanismen bzw. auf welche Art und Weise - X auf Y wirken könnte.

- \- Zur Erläuterung eines Kausalmodells (oder seiner Grundzüge) ist es hilfreich, auf eine bestehende Theorie zurückzugreifen, da diese zumeist auf Wirkbeziehungen fokussieren. Dieser Punkt wurde in der vorliegenden Arbeit nicht (ausreichend) berücksichtigt.

- \- Bei der Erläuterung eines Kausalmodells ist neben einer theoretischen Erklärung möglichst auch empirische Evidenz zugunsten dieser theoretischen Erklärung anzuführen. So könnte z. B. die Ergebnisse einer Studie, die ein Kausalmodell überprüft - etwa anhand eines randomisierten, gut kontrollierten Experiments  - angeführt werden. Die vorliegenden Arbeit hätte von der (stärkeren) Berücksichtigung dieses Punktes profitiert. 

## Literaturverzeichnis (xxliteratur)



### Umfang des Literaturverzeichnisses (xxlitmenge) {#literaturmenge}

Der Gutachter beziffert seine Anforderung an die zitierte Quellenzahl wie folgt (vgl. Anforderungen für Abschlussarbeiten auf der OC-Seite des Gutachters): 1. Bachelor: Ca. 50-60 Quellen; 2. Master: ca. 60-80 Quellen.

`+++`

- \+ *Einige hochwertige Literaturstellen *(Fachartikel) finden sich im Literaturverzeichnis.
- \+ Der Umfang des Literaturverzeichnisses und die Qualität der Quellen sind *sehr gut*.
- \+ Der Umfang des Literaturverzeichnisses (an guten Quellen) ist sehr hoch.
- \+ Der Umfang des Literaturverzeichnisses ist sehr hoch.


- \+ Der Umfang des Literaturverzeichnisses (an guten Quellen) ist hoch.
- \+ Der Umfang des Literaturverzeichnisses ist *hoch.*


- \+ Der Umfang des Literaturverzeichnisses (an guten Quellen) ist als gut zu bewerten.
- \+ Der Umfang des Literaturverzeichnisses  ist als gut zu bewerten.


- \+ Der Umfang des Literaturverzeichnisses (an guten Quellen) ist befriedigend bis gut.
- \+ Der Umfang des Literaturverzeichnisses ist *befriedigend bis gut*.

- \+- Der Umfang des Literaturverzeichnisses (an guten Quellen) ist befriedigend groß (Note 3).
- \+- Der Umfang des Literaturverzeichnisses  ist *befriedigend* groß (Note 3).


- \+- Der Umfang des Literaturverzeichnisses (an guten Quellen) ist *ausreichend bis befriedigend* groß (Note 3-4).
- \+- Der Umfang des Literaturverzeichnisses ist ausreichend bis befriedigend groß (Note 3-4).


`---`


- \- Der Umfang des Literaturverzeichnisses (an guten Quellen) ist *ausreichend.*
- \- Der Umfang des Literaturverzeichnisses ist ausreichend.


- \- Die Anzahl der Quellen im Literaturverzeichnis (an guten Quellen) ist *ausreichend bis mangelhaft* (Note 4 bis 5).
- \- Die Anzahl der Quellen im Literaturverzeichnis ist ausreichend bis mangelhaft (Note 4 bis 5).


- \- Der Umfang des Literaturverzeichnis (an guten Quellen) ist *mangelhaft.*
- \- Der Umfang des Literaturverzeichnis  ist mangelhaft.



- \- Die Anzahl der fachlich-inhaltlichen Quellen (mit Qualität) sollte umfassender sein.
- \- Die Anzahl der fachlich-inhaltlichen Quellen sollte umfassender sein.

- \- Die Anzahl der Quellen im Literaturverzeichnis (mit Qualität) ist zu gering.
- \- Die Anzahl der Quellen im Literaturverzeichnis ist zu gering.

- \- Die Anzahl und/oder die Qualität der der Quellen im Literaturverzeichnis entspricht nicht dem geforderten Niveau des Studiengangs.



### Verwendung von Fachartikeln {#fachartikelverwendet}

`+++`

- \+ Die Anzahl der zitierten wissenschaftlich hochwertigen Literaturstellen (Originalartikel oder Reviews) ist *ungewöhnlich groß*; dies belegt die theoretische Fundierung der Arbeit.
- \+ Die Anzahl der zitierten wissenschaftlich hochwertigen Literaturstellen (Originalartikel oder Reviews) ist *sehr hoch*.
- \+ Die Anzahl der zitierten wissenschaftlich hochwertigen Literaturstellen (Originalartikel oder Reviews) ist *hoch.*
- \+ Die Anzahl der zitierten wissenschaftlich hochwertigen Literaturstellen (Originalartikel oder Reviews) ist befriedigend bis hoch.

- \+- Die Anzahl der zitierten wissenschaftlich hochwertigen Literaturstellen (Originalartikel oder Reviews) ist von *mittlerer Güte*.


`---`


- \- Die Anzahl der Quellen mit hohem wissenschaftlichem Anspruch (Originalartikel oder Reviews) ist gering.
- \- Die Anzahl der Quellen mit hohem wissenschaftlichem Anspruch (Originalartikel oder Reviews) ist zu gering.


### Qualität der Quellen - Beurteilung (xxlitqual)

`+++`

- \+ Die Qualität der Quellen im Literaturverzeichnis ist sehr gut.
- \+ Die Qualität der Quellen im Literaturverzeichnis ist insgesamt gut bis sehr gut.
- \+ Die Qualität der Quellen im Literaturverzeichnis ist insgesamt gut.

- \+- Die Qualität der Quellen im Literaturverzeichnis ist von mittlerer (befriedigender) Güte.
- \+- Die Qualität der Quellen im Literaturverzeichnis ist von mittlerer bis geringer Güte.




`---`

- \- Die Qualität der Quellen im Literaturverzeichnis ist wenig überzeugend (Note 4).
- \- Die Qualität der Quellen im Literaturverzeichnis ist mangelhaft.



- \- Die Qualität der Quellen im Literaturverzeichnis erreicht nicht das Niveau eines Master of Science Studiengangs.

 
### Qualität der Quellen -- Kommentare

`+++`

- \+ Aktuelle (Forschungs-)arbeiten werden aufgegriffen.
- \+ In der vorliegenden Arbeit werden (eine oder mehrere) Überblicksarbeiten wie Reviews oder Meta-Analysen zitiert. Das ist begrüßenswert und zeugt von gutem Verständnis zum Evidenzgehalt von Publikationen.


`---`


- \- Aktuelle (Forschungs-)arbeiten werden nicht oder kaum aufgegriffen.

- \- Dem Literaturverzeichnis mangelt es an Originalarbeiten bzw. genauen Berichten empirischer Ergebnisse.

- \- Internetquellen sind meist von geringer Qualität und außerdem von Flüchtigkeit und sollten gemieden werden.
- \- Die Arbeit bezieht sich in großer Zahl auf Quellen von geringer Qualität wie etwa Internetseiten.

- \- Es wurden in zu hohem Maße allgemeine Lehrbücher, nicht aber spezifische Quellen zur Verdeutlichung der Theorien herangezogen.




### Englischsprachige Literatur


`+++`

- \+ Das Literaturverzeichnis bezieht angelsächsische Quellen reichhaltig mit ein. Da diese Quellen einen dominierenden Anteil der Literatur stellen, ist plausibel, dass das theoretische Fundament der Arbeit breit und solide ist.

- \+ Das Literaturverzeichnis bezieht englischsprachige Arbeiten reichhaltig mit ein.
- \+ Das Literaturverzeichnis bezieht einige englischsprachige Arbeiten mit ein.


`---`


- \- Das Literaturverzeichnis hätte von einem ausgiebigerem Rückgriff auf englischsprachige Literatur profitiert.

- \- Das Literaturverzeichnis berücksichtigt nur wenige englischsprachige Arbeiten. Da aber englischsprachige Arbeiten einen Großteil der verfügbaren Literatur ausmachen, ist davon auszugehen, dass substanzielle Lücken im Literaturüberblick vorliegen.
- \- Das Literaturverzeichnis vernachlässigt angelsächsische Quellen, die aber einen dominierenden Anteil der Literatur stellen. Daher ist davon auszugehen, dass das theoretische Fundament der Arbeit lückenhaft oder/und verzerrt ist.



### Qualität der Quellen -- Empfehlungen  


- \> Versuchen Sie in künftigen Arbeiten dieser Art, eine größere Zahl Fachartikel, am besten englischsprachige, zu berücksichtigen.


## Sprachlicher Ausdruck (xxsprach) {#sprache}

### Sprachlicher Ausdruck -- Bewertung 


`+++`
- \+ Der sprachliche Ausdruck ist insgesamt sehr gut.
- \+ Der sprachliche Ausdruck ist gut.
- \+ Der sprachliche Ausdruck ist insgesamt sehr gut.

- \+ Der sprachliche Ausdruck ist angemessen.
- \+ Der sprachliche Ausdruck ist insgesamt adäquat.

- \+ Auf Fachjargon wurde verzichtet, ohne dass die Klarheit der Begriffe eingeschränkt ist. Damit ist eine Fachsprache auf gutem Niveau großteils erreicht worden.
- \+ Die Formulierung ist exakt und präzise, so wie es für eine wissenschaftliche Arbeit angemessen ist.


`---`

- \- Der sprachliche Ausdruck ist nicht immer angemessen.
- \- An einigen Stellen ist der sprachliche Ausdruck nicht angemessen.


### Sprachlicher Ausdruck (Klarheit) -- Kommentare {#klaresprache}

`+++`

- \+ Wesentliches Merkmal wissenschaftlicher (und technischer) Sprache ist die *Prägnanz*: Viel Information soll auf wenig Raum wiedergegeben werden. Das Gegenteil wäre, vulgo, "Schwafeln". *Schwafeln* ist bei wissenschaftlichen Schriften ein grober Fehler und immer zu vermeiden. Außerdem bemühe man sich, die Dinge so einfach wie möglich, ohne unnötige (!) Komplexität darzulegen. Unnötige Fremdwörter sind also zu vermeiden. Das Wort Schopenhauers "Man gebrauche gewöhnliche Worte und sage ungewöhnliche Dinge" fasst diese Idee schön in Worte. Die vorliegende Arbeit setzt dies gut um.

- \+ Ein *Zitat* oder mehrere Zitate wurden in gewinnbringender, *schmückender* Form verwendet.

- \+ *Rhetorische* Fragen wurden in *sinnvoller* (eleganter) Art und Weise verwendet.


- \+ Die Sprache in der vorliegenden Arbeit zeichnet sich durch eine angenehm *geringen Teil an Füllwörtern* ("nämlich", "nun", "gerade deshalb", "letztlich") und überflüssigen Adjektiven ("sehr stringent", "besonders aufwändig", "schwere Verwüstung") aus.
- \+ Der *Satzbau* ist *elegant*, insofern er durch Konjunktionen (und/oder andere Junktoren) wie "obwohl", "während" oder "gleichzeitig" interessante Gedankengefüge erstellt.



`---` 


- \- Die *Ergebnisse* der statistischen Tests bzw. Statistiken allgemein *sollten im Text angeführt* und erläutert und besprochen werden.

- \- Die *erste Person Singular* (Ich-Form) und Plural sollte in wissenschaftlichen Berichten *spärlich* eingesetzt werden; zumindest in der deutschen Sprache. Die vorliegende Arbeit macht relativ regen Gebrauch von dieser Form.

- \- Zwar kann man es mit *politisch korrekter Sprache* auch übertreiben, aber nur von Männern zu reden, wenn es um Frauen und Männer geht, führt eine unnötige Verzerrung und Verengung des Blickwinkels an (z. B. "Hier muss man einen alleinstehenden Mann von einem Familienvater unterscheiden" - wenn man auch eine alleinstehende Frau von einer Mutter unterscheiden müsste).

- \- *Abkürzungen* wurden verwendet,* ohne dass sie vorab definiert* wurden; Abkürzungen sollten zuerst definiert werden, bevor sie verwendet werden.

- \- In einem Forschungsbericht sollten Handlungen, die in der Vergangenheit liegen, mit einer *Vergangenheitsform* (Präteritum oder Perfekt) beschrieben werden ("Die Versuchspersonen wurden aufgeklärt über ..."). Aussagen hingegen, die zeitübergreifend oder aktuell gültig sind, sollten im Präsens formuliert werden ("Die Ergebnisse zeigen/implizieren/verdeutlichen ..."). Die Wahl der Zeitform wurde in der vorliegenden Arbeit nicht immer korrekt gewählt.

- \+ Wesentliches Merkmal wissenschaftlicher (und technischer) Sprache ist die *Prägnanz*: Viel Information soll auf wenig Raum wiedergegeben werden. Das Gegenteil wäre, vulgo, "Schwafeln". Schwafeln ist bei wissenschaftlichen Schriften ein grober Fehler und immer zu vermeiden. Außerdem bemühe man sich, die Dinge so einfach wie möglich, ohne unnötige (!) Komplexität darzulegen. Unnötige Fremdwörter sind also zu vermeiden. Das Wort Schopenhauers "Man gebrauche gewöhnliche Worte und sage ungewöhnliche Dinge" fasst diese Idee schön in Worte. Die vorliegende Arbeit setzt dies nicht konsequent um.


`---`





- \- *Füllwörter sollten vermieden* werden ("also", "nun", "etwas", "genau", "gerade", "gewiss", "im Prinzip", "ja", "letztlich" "sogar", "streng", "zudem", usw.). In der vorliegenden Arbeit finden sich davon einige.

- \- Die Sprache klingt in Teilen nach "*Amtsdeutsch*": "Durch die Begehungsvorschriftinkraftretung wird ein Fortschritt erzielt". Besser: "Die Maßnahme brachte Fortschritte in XXX". 

- \- *Anglizismen* sollten in deutschsprachigen Texten *vermieden* werden bzw. nur verwendet werden, wenn sie im Deutschen üblich sind (ok: Internet, vermeidbar: Das Slidedeck, der Go-Live, der Consultant).
- \- Der Text ist in hohem *(zu hohem) Umfang im Passiv* formuliert. So könnten Textstellen wie "es wird gezeigt, dass blablabla" umformuliert werden in "Die Ergebnisse deuten darauf hin, dass blablabla" oder "Kapitel 2 geht auf blablabla ein".
- \- Adjektive sollte man vorsichtig(er) verwenden, da sie oft unnötig aufblähen ("eine besonders extrem ambitiöse quantitativ-statistische Untersuchung"), doppelt-gemoppelt sind ("Interviewpartner bewusst gewählt" - wie oft wählt man die Interviewpartner unbewusst) oder falsch sind ("die einzigste Untersuchung"). Im vorliegenden Text wird in *zu hohem oder nicht adäquatem Maß von Adjektiven Gebrauch* gemacht.

- \- *Adjektive* sollten in technischen Berichten bzw. wissenschaftlichen Texten sparsam (nicht ohne Not) verwendet werden.

- \- Es findet sich mind. ein *Pleonasmus* im Text ("weißer Schimmel"; z. B. "geistige Reflexion").

- \- Ein sachlicher Bericht, und das ist eine wissenschaftliche Seminararbeit, *sollte auf Adjektive verzichten*, da Adjektive mitunter einen nüchternen Beschreibung im Wege stehen. So sollte man vermeiden, von der "ausführlichen Recherche" oder der "genauen Beschreibung", die man durchgeführt habe, zu sprechen.

- \- Wissenschaftliche (und andere) Berichte zeichnen sich durch Präzision aus. *Phrasen* wie "nach intensiver Lektüre wurden folgende Thesen abgleitet", "Dieses Kapitel [der Theorieteil] beschäftigt sich mit der theoretischen Betrachtung" oder "durch Anwendung fortgeschrittener Analysemethoden" stehen daher der wissenschaftlichen Sprache  entgegen, da *inhaltsarm*, und sollten sorgfältig vermieden werden. Insbesondere gilt dies für Abschnitte des Berichts, die das Aushängeschild für präzise, knappe bzw. prägnante Sprache herhalten sollen wie der Abstract. (In Teilen) *mangelnde Präzision* ist ein substanzieller Fehler im Hinblick auf den Bewertungsaspekt des wissenschaftlichen Formulierens zu verstehen. 

- \- Es finden sich *Schachtelsätze* bzw. "Klemmkeil-Satzkonstruktionen", die von einem zu hohem Maße an eingeschobenen *Nebensätzen* gekennzeichnet sind. Überspitztes Beispiel: "Derjenige, der denjenigen, der den Pfahl, der an der Brücke, die an der Straße, die nach Mainz führt, liegt, stand, umgeworfen hat, anzeigt, erhält eine Belohnung." Besser ist es, kurze Hauptsätze (*Hypotaxen*) mit etwas längeren Sätzen (etwa: Hauptsatz plus ein Nebensatz) abzuwechseln.



## Reflexion/Diskussion (xxreflex, xxdisk) {#diskussion}

### Reflexion/Diskussion - Beurteilung 

`+++`

- \+ Insgesamt ist die Diskussion als sehr gut zu beurteilen.
- \+ Die Diskussion ist sehr umfangreich.

- \+ Insgesamt ist die Diskussion als gut zu beurteilen.
- \+ Die Diskussion spricht einige nennenswerte Aspekte an.

- \+- Insgesamt ist die Diskussion als befriedigend zu beurteilen.
- \+/- Es wurden einige Aspekte der Arbeit (Inhalt, Methode, Ergebnis) diskutiert; die Diskussion erreicht jedoch keine große Tiefe oder Breite.


`---`


- \- Insgesamt ist die Diskussion als ausreichend zu beurteilen.
- \- Die Diskussion ist sehr kurz gehalten.
- \- Die Diskussion ist insgesamt zu wenig ausgeprägt; wesentliche diskussionswürdige Punkte bleiben unadressiert.

- \- Wesentliche Einschränkungen qualitativer Forschung (wie eingeschränkte Repräsentativität der Ergebnisse) wurden nicht diskutiert.


- \- Das Fehler des Diskussionsteils ist zu bemängeln. 


### Reflexion/Diskussion (allgemein, OHNE Schwächen) -- Kommentare



- \+ Das Ergebnis der Arbeit wurde kritisch reflektiert.
- \+ Die Implikation bzw. die Bedeutung für die Praxis, die sich aus den Ergebnissen der Arbeit ergeben, werden in nützlicher Weise diskutiert.

- \+ Die Ergebnisse der Studie wurden recht umfangreich interpretiert.


`---`



- \- Der Arbeit fehlt eine Anbindung der Ergebnisse in die Forschungslandschaft. Fügen sich die Ergebnisse in das Gros der bisherigen Befunde ein? Wo widersprechen die vorliegenden Erkenntnisse der Literatur? Werden Lücken in der Forschungslandschaft gefüllt? Sind die Erkenntnisse dieser Arbeit als valider zu bewerten als gewisse andere existierende Arbeiten?
- \- Die Diskussion bietet Raum primär um das Ausmaß, die Tiefe und die Gründlichkeit des eigenen Nachdenkens über die eigene Arbeit und das Ergebnis der Analyse zu erörtern. Diese Gelegenheit wurde nicht (ausreichend) genutzt; die Diskussion erreicht keine großen Tiefen.
- \- Fähigkeit zur Reflexion im Allgemeinen und zur Selbstreflexion im Besonderen sind ein wesentliches (vielleicht das wesentliche) Lernziel eines akademischen Studiums. Daraus leitet sich die hohe Bedeutung der Reflexion bzw. des Diskussionsteils in einer wissenschaftlichen Arbeit wie einer Seminararbeit oder einer Thesis ab; die Güte des Diskussionsteils ist ein wichtiger Indikator zur Einschätzung der Fähigkeit zur Reflexion bei der Autorin bzw. beim Autor. In der vorliegenden Arbeit kann die Reflexionsfähigkeit aufgrund der gezeigten Reflexion bzw. Reflexivität nicht als ausgeprägt eingeschätzt werden, da keine ausführliche Reflexion des eigenen Vorgehens im Rahmen des Diskussionsteils gezeigt wurde.
- \- Ein wesentliches Manko (des Diskussionsteils) der Arbeit ist der von Übergewissheit bzw. nicht gerechtfertigtem Optimismus auf die Aussagekraft (Validität) der Ergebnisse getragen. So finden sich Hinweise, dass die Ergebnisse "verlässlich" seien oder etwas "bewiesen" haben oder etwas klar "zeigen". So wird verkannt, dass die Ergebnisse weniger Aussagekraft haben, als es die sprachliche Darstellung vermuten ließe.

- \- Zwar reflektieren viele Studien den Einfluss der Personen-Stichprobengröße, der Anzahl der (i.d.R.) Personen, die an einem Versuch teilnehmen. Hingegen fehlt häufiger - und so auch in der vorliegenden Arbeit - eine umfassende Reflektion des Einflusses der *Stimuli*-Stichprobe. Wie auch für eine Personen-Stichprobe gilt für eine Stimuli-Stichprobe in gleichem Maße: je geringer die Größe der Stichprobe, desto unsicherer die Schätzung der Grundgesamtheit. Vergleicht zum Beispiel eine Studie ob "Adam" attraktiver ist als "Eva", so ist etwa der Schluss, dass "Männer weniger attraktiv" seien als Frauen (bei gegebener Datenlage) überzogen. Das Studiendesign ließe, ob der geringen Stichprobengröße der Stimuli nur einen Schluss zu, dass etwa Eva als attraktiver wahrgenommen wird als Adam.  



### Schwächen/Limitationen/Kritik (xxlimit) {#limitationen}

`+++`

- \+ Der eigene Forschungsprozess wurde in sinnvollerweise Weise *kritisch diskutiert*.
- \+ Die Studie in Aufbau, Durchführung und Ergebnissen wurden *umfangreich diskutiert*.
- \+ Das methodische Vorgehen wurde *kritisch reflektiert*.
- \+ *Die (geringe) Stichprobengröße* bzw. die Konsequenzen auf den Signifikanzwert wurde *gut diskutiert* (bei größerer Stichprobe wären vielleicht andere/deutlichere Effekte aufgetreten).
- \+ *Grenzen der internen Validität* der Studie (also des Ursache-Wirkungs-Zusammenhangs) wurden erkannt und *stimmig diskutiert*.

- \+- Die *Stichprobengröße* ist zwar ein meist treffender Kritikpunkt an einer Studie; kaum eine Studie weist eine "zu große" Stichprobe auf. Gleichzeitig ist dieser Punkt nicht ausreichend für die Diskussion der Grenzen der Untersuchung und insofern noch *kein Zeugnis einer tiefen Durchdringung* der Stärken und Schwächen eines Forschungsdesigns.
- \+- Das methodische Vorgehen wurde kritisch reflektiert, wenn dieser Teil auch *relativ kurz gehalten* ist. Die Diskussion hätte von einer ausführlicheren Diskussion der methodischen Schwächen bzw. Einschränkungen der Studie profitiert.

- \+- Es wurden einige Aspekte im Hinblick auf die Grenzen (Limitationen) der vorliegenden Arbeit diskutiert.


`---`


- \- Die Diskussion hätte von einer *intensiveren Erörterung der Limitationen der vorliegenden Arbeit profitiert*.

- \- Der Diskussion *fehlt es an einer Diskussion der Grenzen der Arbeit* und der Grenzen der Aussagekraft der Ergebnisse. 

- \- Der Diskussion fehlt es an einer Diskussion der Grenzen der Arbeit und der Grenzen der Aussagekraft der Ergebnisse. Das ist als *substanzieller Schwachpunkt* der Arbeit zu bewerten.

- \- Der Diskussion fehlt es an einer Diskussion der Grenzen der Arbeit und der Grenzen der *Aussagekraft* der Ergebnisse.

- \- Die (geringe) *Stichprobengröße* bzw. die Konsequenzen auf den Signifikanzwert wurde *nicht* (ausreichend) diskutiert (bei größerer Stichprobe wären vielleicht andere/deutlichere Effekte aufgetreten).
- \- Die *Schwächen im Aufbau der Studie* wurden nicht in ausreichendem Umfang und Tiefe diskutiert.

- \- Eine Schwäche an *Beobachtungsstudien* ist, dass die Aufnahme weiterer Kovariablen (Prädiktoren) die Einflussgewichte der bereits inkludierten Variablen ändern kann, teils sogar das Vorzeichen umdreht. Bei gut geplanten Experimenten tritt dieses gravierende Problem hingegen nicht auf. Die vorliegende Studie hätte in ihrer Diskussion von einer Erörterung dieses Sachverhalts profitiert.

- \- *Beispiele für methodische Schwächen*, die es lohnt, in der Diskussion zu erörtern, sind: Welche anderen Variablen hätten (vermutlich) noch einen substanziellen Erklärungsbeitrag geliefert? Welche anderen statistischen Analysen wären noch hilfreich gewesen, wurden aber nicht durchgeführt (z. B. Konfidenzintervalle, klassifizierende Regression, Mehrebenenmodelle und so weiter)? War die Stichprobe insofern nicht repräsentativ, als dass bestimmte Ausprägungen bestimmter Variablen nicht (ausreichend) Eingang fanden (z. B. junge Frauen oder nur bestimmte Zeitperioden)? Welche Schwachpunkte hat das Studiendesign aufzuweisen (z. B. querschnittliche Beobachtungsstudie oder Messinstrumente geringer Qualität)? Sind die gefundenen Effekte vielleicht Artefakte (z. B. durch mögliche Interessenskonflikte)? Inwiefern sind kausale Schlüsse gerechtfertigt (z. B. erlaubt eine große randomisierte Stichprobe eher kausale Schlüsse als eine kleine, nicht balancierte Adhoc-Stichprobe)? 

- \- Die Diskussion der methodischen Schwächen der Arbeit *begrenzt sich auf den Hinweis, dass eine größere Stichprobe sinnvoll gewesen wäre*. Dieser Hinweis ist zwar richtig, erfüllt aber noch nicht den Anspruch an einer wohl überlegten und tiefgehenden Reflexion der Studienmethodik.

- \- Der Diskussion der Schwächen der Arbeit ist ein *eigener Abschnitt bzw. Absatz* zu widmen, da diesem Teil eine *große Bedeutung zukommt*. Dieser Punkt wurde in der vorliegenden Arbeit nicht berücksichtigt.

- \- Im Gegensatz zum Großteil des Textes einer wissenschaftlichen Arbeit, *bespricht der Abschnitt zu den Limitationen der Arbeit keine Fachinhalte*, noch wird über das Vorgehen des Forschers informiert. Stattdessen wird über das Vorgehen des Forschers, über die "Handwerksarbeit" des vorliegenden Forschungsbericht geschrieben. Insofern ist es ein besonderer Abschnitt, der aber von großer Wichtigkeit für die Qualität eines Forschungsberichtes ist.

- \- Ein substanzielles, alldieweil oft vernachlässigtes Problem von Forschung mittels Fragebogen ist es, dass die *Konstrukte oft semantisch stark überlappen*: "Ich nehme unangenehme Erfahrung an" (Achtsamkeit), "Schwierigkeiten sehe ich gelassen entgegen ..." (Optimismus) und "Ich bin mit meinem Leben zufrieden" (Lebenszufriedenheit). So könnte ein Zusammenhang in den Antwortmustern der Respondenten alleine schon auf diese semantischen Überlappungen zurückzuführen sein, unabhängig von der Validität der Konstrukte. Diese Möglichkeit bzw. sollte einem Autor bewusst sein bzw. er oder sie sollte explizieren, dass das Problem bekannt ist. Dieses Problem wird auch *Common Method Bias* bezeichnet. Die vorliegende Arbeit hätte von einer intensiveren Diskussion der Relevanz dieses Problems für die Studie profitiert Nimon, K., Shuck, B., & Zigarmi, D. (2016). Construct Overlap Between Employee Engagement and Job Satisfaction: A Function of Semantic Equivalence? Journal of Happiness Studies, 17(3), 1149–1171. https://doi.org/10.1007/s10902-015-9636-6).

- \- Die *formalen Bedingungen* (wie geforderte Ober-/Untergrenzen an Text- oder Datenmenge) sollten bei den Limitationen nicht aufgeführt werden. 


### Sonstiges

- \+ Mit der Studie wurde eine aktuelle Diskussion in der Scientific Community  aufgegriffen.
- \+ Anregungen für zukünftige Forschungsarbeiten werden auf fundierter Basis gegeben.



`---`



- \- In Fällen, in denen sich Hypothesen nicht bestätigen, ist es angezeigt, *über die Gründe (post-hoc) zu spekulieren*. Kurz gesagt: Woran lag's? Statt der angenommen Ursache "A" könnte vielleicht doch "B" wichtiger sein? Oder wirkt "A" nur in der Situation "C", die nicht zutraf in der vorliegenden Studie hingeben bei Mayer (2015) der Fall war? Solcherlei Räsonnement wäre sinnvoll gewesen im Diskussionsteil, fehlt aber (großteils).
- \- Ein *Kritikpunkt* an der Arbeit ist, dass im Schlussteil *versäumt* wird, das eigene *Vorgehen* (und somit die Qualität der Ergebnisse) (ausführlich genug) zu *diskutieren*: Wurden womöglich nicht alle zentralen Literaturstellen identifiziert? Wurden einige Theorien nicht berücksichtigt? Wurden bestimmte Blickwinkel ausgelassen? Haben die Messinstrumente Mängel? Könnte die Intervention nicht richtig funktioniert haben? Gab es Ausreißer, die die Daten evtl. verfälscht haben? Waren die Annahmen der statistischen Verfahren nicht ausreichend abgesichert? Etc. Dabei soll keineswegs seitens des Gutachters kritisiert werden, dass nicht alle möglichen Punkte beleuchtet wurden (was aufgrund z. B. von Platzrestriktionen nicht möglich ist). Vielmehr soll die Reflexion des eigenen Vorgehen verdeutlichen, dass kritisches Denkvermögen insoweit angewandt wurde, als dass eigene Stärken und Schwächen bewusst sind, soweit sie die niedergeschriebene Arbeit betreffen. Insgesamt ist diese Art der Reflexivität nicht in ausreichendem Maße im Diskussionsteil gezeigt werden. Das ist ein substanzieller Mangel, da Reflexivität ein zentrales Lernziel nicht nur für diese Seminararbeit, sondern generell des Studiums darstellt.
- \- *Ergebnisse und Diskussion sind strikt zu trennen* - die Arbeit hält dies nicht durchgängig durch.
- \- Die Diskussion versäumt es, kritisch über (potenzielle) Einschränkungen der internen Validität zu diskutieren. 

- \- Die Diskussion r*ückbezieht die Ergebnisse nicht (ausführlich) genug auf den Stand der Literatur*.



### Unkritische Verwendung von Theorien

- \- Der *Theorie* hätte *stärker auf Kritikpunkte* am untersuchten Konstrukt eingehen sollen.

- \- Die Idee, dass empirisch scharf abgrenzbare *Generationenunterschiede* existieren, ist nicht als wissenschaftlich etabliert zu betrachten. Im Gegenteil, es sind deutliche Zweifel angebracht, ob dieses Phänomen überhaupt existiert. So zeigte eine Untersuchung von Schröder (2018) anhand von knapp 80.000 Menschen aller Generationen (inkl. *GenY*, Generation X, Baby-Boomer), dass "von der Literatur postulierte Generationsunterschiede zwischen der sogenannten Generation Y, X, den Babyboomern, den ’68ern sowie der sogenannten Skeptischen Nachkriegsgeneration in Wirklichkeit kaum existieren" (S. 469). Die vorliegende Arbeit verwendet das Konzept der Generationenprofile zu unkritisch. Die Arbeit hätte von einem intensiveren Hinterfragen profitiert. Literatur: Schröder, M. (2018). Der Generationenmythos. KZfSS Kölner Zeitschrift für Soziologie und Sozialpsychologie, 70(3), 469–494. https://doi.org/10.1007/s11577-018-0570-6



### Reflexion im Theorieteil

- \+ Theorien/Studien wurden *kritisch bzw. aus mehreren Blickwinkeln beleuchtet* oder es wurden Theorien verglichen.


`---`


- \- Die untersuchten Theorien sollten (im Theorieteil) *nicht nur aufgeführt, sondern noch stärker als es in der vorliegenden Arbeit der Fall ist diskutiert*, verglichen, beurteilt — kurz: analysiert — werden.
- \- Die untersuchten Theorien sollten nicht nur aufgeführt, sondern diskutiert, verglichen, beurteilt — kurz: analysiert — werden. 

### Ideen für weiterführende Studien

- \+ Es werden *Vorschläge* für die Weiterführung der vorliegenden Arbeit in *zukünftigen Studien* gegeben.
- \+ Es werden Vorschläge zur Weiterführung der vorliegenden Arbeit unterbreitet.

- \- Anregungen für Forschungsfragen zukünftiger Studien aufbauend auf den 
Überlegungen, warum die Hypothesen sich nicht bestätigt haben (z. B. zu geringe Power) wären sinnvoll gewesen, aber fehlen.


#### "Beweisen"

- \- *Vorsicht vor Kausalaussagen* zu den Ergebnissen ("es wurde bewiesen, dass ", "X führt zu Y", etc.), da solche sehr ambitionierten Aussagen häufig nicht durch die zitierten Befunde ausreichend gestützt werden. Vorsichtigere Formulierungen ("Die publizierten Ergebnisse lassen darauf schließen, dass", "die Ergebnisse unterstützen die These, dass", etc.) sind häufig sinnvoller.

- \- "*Beweisen*" ("belegen") ist ein großes Wort; *statistische Untersuchungen treffen (auf die allermeisten Fragen) nur bedingte Wahrscheinlichkeitsaussagen*. Solche Aussagen lassen keine sicheren Aussagen zu, und damit auch keine Beweise. Nur "fast sicher" ist als höchstes Gefühl möglich. Sie sollten daher Ausdrücke wie "bewiesen" mit mehr Vorsicht verwenden.

- \- "*Beweisen*" ("belegen") ist ein großes Wort; da der *Stand der Forschung der Stärke dieser Behauptung häufig nicht standhält*. Weiterhin sollte man, wenn man diesen Ausdruck doch verwendet, ausreichend Belege für so eine weitgehende Behauptung präsentieren und etwaige Gegenargumente entkräften.





# Plagiate ---------------------------------------------------------------------------------------- {#plagiate}

- \- Es fanden sich mögliche *Plagiate* in der vorliegenden Arbeit aus dieser Quelle:

- \- Hinweise auf mögliche Plagiate in der vorliegenden Arbeit wurden nicht weiter verfolgt.
- \- Weitere Hinweise auf mögliche Plagiate in der vorliegenden Arbeit wurden nicht weiter verfolgt.
- \- Es fanden sich Hinweise auf Plagiate.
- \- Im Sinne von in dubio pro reo flossen diese Verdachtsfälle von Plagiaten nicht in die Beurteilung der Seminararbeit ein.

- \- Es kann nicht ausgeschlossen werden, dass es sich Vergessen des Zitierens, aber nicht um bewusste Täuschung handelt. Daher werden dieser Arbeit nur grobe Fehler des Zitierens, kein absichtsvolles Betrügen, zur Last gelegt.

- \- Die Befundlage zu den möglichen Plagiaten  beeinflusst die Notengebung negativ.
- \- Die Befundlage zu den möglichen Plagiaten bzw. den schweren Zitationsfehlern beeinflusst die Notengebung negativ.


+- \- Hinweise auf mögliche Plagiate sind nicht in die Beurteilung eingeflossen.


# Summarisch ---------------------------------------------------------------------------------------



## Sehr gute qualitative Methoden  {#sehrgutequalimeth}

- \+ Die Auswahl der untersuchten Personen bzw. die Zusammenstellung der Stichprobe wurde adäquat begründet.

- \+ Ethische Aspekte in Bezug auf die Datenerhebung wurden diskutiert und angemessen umgesetzt.

- \+ Die Kodierregeln sind stimmig gewählt und transparent dokumentiert.

- \+ Zentrale Aussagen der Kategorien wurden treffend wiedergegeben.

- \+ Die Kategorien des Kategoriensystems wurden adäquat definiert.

- \+ Es wurden plausible Kategorien abgeleitet, die das Material stimmig widerzuspiegeln scheinen.

- \+ Der Ergebnisteil stellt die Kategorien bzw. die Ergebnisse in differenzierter und klarer Weise dar.

- \+ Der Ergebnisteil berichtet umfangreiches Material zu den Kategorien.


## Keine Kodierregeln expliziert (qualitative Methoden)  {#schlechtequalimeth}


- \- Die Kodierregeln sind nicht (ausreichend) stimmig gewählt und/oder nicht transparent (genug) dokumentiert.

- \- Die Kodierregeln für die verwendeten Kategorien wurde nicht expliziert. So besteht die Gefahr, dass die Zuordnung der Textstellen zu den Kategorien nicht objektiv nachprüfbar und damit nicht reproduzierbar ist. Eine Studie, die nicht reproduzierbar und nicht replizierbar ist, ist für die Wissenschaft nicht nutzbar.

- \- Ein Nichtexplizieren der Kodierregeln wirft die Gefahr der Beliebigkeit auf. Insofern handelt es sich dabei aus Sicht der wissenschaftlichen Verwertbarkeit um einen gravierenden Fehler.

- \- Beim Berichten der Kategorien sollte die Essenz der Kategorie, d. h. ihre Bestimmungsstücke bzw. wesentlichen Inhalte berichtet werden. Die Kategorie ist zu definieren und ihr Wesensmerkmal zu erklären. Es reicht nicht, einige Textstellen des Interviewmaterials aufzureihen, die der Kategorie zugeordnet wurden.

- \- Das Kategoriensystem, welches aus einer qualitativen Studie resultiert, sollte nicht schwerpunktmäßig aus einer Sammlung von Interview-Zitaten o. Ä. bestehen. Vielmehr sind die wesentlichen Inhaltsstücke einer Kategorie als Generalisierung, Abstrahierung und Zusammenfassung von Rohtextstellen zu erstellen. Die Rohtextstellen dienen lediglich dem Beleg; sie sind nicht der Inhalt der Kategorie. Diese Extrahierung der Kategorien bzw. deren Inhalte sind die zentrale intellektuelle/analytische Leistung der empirischen Arbeit. Ein Fehlen solcher Leistung ist ein substanzieller Mangel in der empirischen Ausarbeitung.

- \- Bei einer qualitativen Inhaltsanalyse ist beim Berichten einer Kategorie nicht entscheidend, was die Interview-Partner gesagt haben. Vielmehr ist die Blickrichtung umgekehrt: Es wird die Definition der Kategorie erläutert, die auf Basis der Aussagen der interviewten Personen begründet ist.


## Praxistransfer

- \+ Die Arbeit weist einen wohl ausgearbeiteten und umfangreichen Transfer in die (berufliche) Praxis auf.

- \- Der Arbeit fehlt der formal geforderte Transfer in die berufliche Praxis.



# Kommentare -------------------------------------------------------------------------------------- {#kommentare}

## Negativ
- \- Bitte vertiefen Sie Ihre methodischen Kenntnisse vor der Abschlussarbeit.

- \- Bitte lesen Sie sich (gute) andere Arbeiten durch, um besser das Anspruchsniveau an eine solche Ausarbeitung zu verstehen. 


- \+- Im OC finden Sie unter meinem Namen bei "Allgemeine Informationen" eine Auswahl guter  Seminararbeiten.

- \- Insgesamt ist die gezeigte Leistung nicht mehr ausreichend.

- \- Das ist als schwerwiegender Mangel der Arbeit einzustufen.

- \- Aufgrund schwerwiegender Mängel (falsche oder nicht gezeigte Ansätze) ist die Arbeit als "mangelhaft" einzustufen.

- \- Aufgrund fehlender Erörterungen sind einige Aspekte der vorliegenden Arbeit nicht beurteilbar.

- \- Da wesentliche Aspekte der Arbeit fehlen, ist die Arbeit mit "mangelhaft" einzustufen.

- \- Hinweise, dass ein höheres Wortlimit detailliertere Erklärung ermöglicht hätte, sollten nicht gegeben werden, da damit keine neuen Informationen gegeben werden.


## Positiv

- \- Der Autor/die Autorin hat sehr selbständig gearbeitet. Damit wurde ein zentraler Aspekt der Lernziele einer akademischen Ausbildung erfüllt.


## Neutral

- \- Der genannte Punkt fließt nicht in die Bewertung der Arbeit ein.

