% Uni Scientific Exercises
% Felicitas Pojtinger
% \today
\tableofcontents
\newpage

# Uni Scientific Exercises

## Introduction

### Contributing

These study materials are heavily based on [professor Charzinski's "Anleitung zum wissenschaftlichen Arbeiten" lecture at HdM Stuttgart](https://www.hdm-stuttgart.de/vorlesung_detail?vorlid=5212596).

**Found an error or have a suggestion?** Please open an issue on GitHub ([github.com/pojntfx/uni-sciwriting-notes](https://github.com/pojntfx/uni-sciwriting-notes)):

![QR code to source repository](./static/qr.png){ width=150px }

If you like the study materials, a GitHub star is always appreciated :)

### License

![AGPL-3.0 license badge](https://www.gnu.org/graphics/agplv3-155x51.png){ width=128px }

Uni Scientific Exercises (c) 2021 Felicitas Pojtinger and contributors

SPDX-License-Identifier: AGPL-3.0
\newpage

### Results

#### 2021-10-08

**Sie haben in einem Blog-Eintrag gelesen, dass man mit Hilfe heutiger GPUs 4k-Videos in Echtzeit komprimieren kann. Das ist entscheidend dafür, ob das Konzept, das Sie sich ausgedacht haben, funktionieren kann. Wie gehen Sie mit diesem Literaturhinweis um?**:

- Blogs sind oft keine akzeptablen Quellen
- Direktes oder indirektes Zitat
- Aussagen sind daher nicht alleinstehend belastbar!
- Blogs haben meist kein Peer-Review etc. → Überprüfen, ob d. Autor:in im Fachgebiet Qualifikation vorweisen kann
- Überprüfen, ob Autor:in Interessenkonflikte im Thema hat (z.B. NVIDIA-Entwickler:in → Hat Interesse, eigene Grafikkarten gut darzustellen)
- Quellen/Referenzen des Blogs überprüfen
- Blogs haben oft eine Kommentarsektion; wenn es noch Fragen zum Thema gibt, können diese hier öffentlich gestellt werden
- Autor:in kann bei Unregelmäßigkeiten oft auch kontaktiert werden
- Wenn z.B. im Software-Bereich: Versuch, z.B. hier konkret das Experiment/den Benchmark zu reproduzieren

**Hinrichsdorf (2013) schreibt „Ab 100 Computern muss ein lokales Netzwerk durch Router geteilt werden.“ Heinerstadt (2013) schreibt „Lokale Netzwerke können bis zu einer Größe von 100 000 Computern ohne Routing betrieben werden.“ Beide Aufsätze sind im selben Jahr in derselben Zeitschrift erschienen. Was machen Sie mit diesen Quellen? eine ignorieren? nachmessen? weitere Quellen suchen? verstehen, wie die auf diese Ergebnisse kommen?**:

- Beide Quellen sind im gleichen Jahr und in der gleichen Zeitschrift erschienen, es ist also wahrsch. dass sie im Widerspruch zueinander stehen
- Überprüfen, ob eine Sprunginnovation zwischen den beiden Veröffentlichungen erschienen ist (z.B. 2011 armv8 vs armv7), welche die Unterschiede erklären könnte
- Methodik der beiden Quellen untersuchen: Was ist ein "lokales Netzwerk" - z.B. sind sowohl ein kabelgebundes LAN und ein WLAN-Netzwerk ein "lokales Netzwerk", haben aber unerschiedliche Charakteristika
- Nach weiteren Quellen suchen
- Nach Metaanalysen von Papern zum Thema suchen
- Falls möglich beschriebenes Experiment lokal nachstellen (z.B. mit virtualisierter Netzwerkinfrastruktur)
- Lektor kontaktieren: Derartige Differenzen bei den Ergebnissen im selben Jahr müssten eigentlich auffallen!

**Was ist an der folgenden Darstellung kritisch? "Momentan ist mobiles Einkaufen noch Zukunftsmusik. Das wird sich aber laut Studien in den nächsten 10 Jahren schlagartig ändern, und der mobile Handel wird enorme Umsatzsteigerungen verzeichnen."**

- "laut Studien" ist vage formuliert: Welche Studien?
- "Zukunftsmusik" ist sehr informell; alternativ: "noch nicht Marktreif" oder "noch in der Entwicklungsphase"
- "wird enorme Umsatzsteigerungen verzeichnen" ist eine Schlussfolgerung ohne Quelle; nur weil das mobile Einkaufen möglich wird, müssen diese nicht unbedingt in Umsatzsteigerungen resultieren
- Der wertende Schreibstil is effekthasschend und lässt darauf schließen, dass d. Autor:in voreingenommen ist
- Aus welchem Jahr ist die vorliegende Quelle? Jahr des Schreibens, Jahr der Veröffentlichung usw.? → Satz sollte in Isolation stehen können

#### 2021-10-19

**Wie würden Sie vorgehen, um die folgende Forschungsfrage zu beantworten: „Kann man mit Tool A zur Cross-Platform-Entwicklung von Apps Zeit sparen?“**

1. Frage analysieren
2. Hypothese ausarbeiten ("Tool A kann bei der Entwicklung von Apps Zeit sparen")
3. Bestehende Literatur zum Thema suchen und auswerten
4. Experiment ausarbeiten (i.e. Beispielapps von Entwickler:innen mit und ohne Tool entwickeln lassen)
5. Experiment durchführen & analyisieren
6. Hypothese mittels bestehender Literatur und Experiment beantworten

**Überlegen Sie sich, wie Sie ein Experiment gestalten und auswerten würden, um der Frage nachzugehen, und dokumentieren Sie das (z.B. mit einem Bildchen oder 10 Zeilen Text)**

- Idee: Beispielapps von Entwickler:innen mit und ohne Tool entwickeln lassen
- Vergleichbare und in Time and Budget umsetzbare Anwendungsfälle überlegen (wahrsch. eher einfachere Anwendungen/TODO etc. - dies kann aber auch die Ergebnisse verfälschen, da viele Tools zwar oft für einfache Anwendungsfälle gut geignet sich aber mit zunehmender Komplexität schlecht skalieren)
- Zeit, in welcher entwickelt wird, eintragen
- Seiteneffekte müssen verhindert werden; z.B. nicht nur Entwickler:innen der HdM verwenden, welche wahrsch. eher web- oder mobile-orientiert
- Unethische Szenarien verhindern: Entwickler:innen z.B. nicht aus wichtigen Freie-Software-Projekten abziehen, wenn diese nicht darüber informiert werden (siehe z.B. https://lore.kernel.org/linux-nfs/YH%2FfM%2FTsbmcZzwnX@kroah.com/ für ein Beispiel im Linux-Kernel)
- Interessenkonflikte dürfen nicht die Ergebnisse verfälschen; ist z.B. d. Entwickler:in des Tools an der Durchführung des Experiments beteiligt, so muss sichergestellt werden dass "ungewollte" Ergebnisse nicht unterdrückt werden
- Nach Abschluss des Experiments muss dieses ausgewertet werden; hier z.B.:
  - Wie lang haben Entwickler:innen, welche das Tool verwenden, im Durchschnitt und Median gebraucht? Wie lange ohne Tool?
  - Wie stark waren die Differenzen pro Entwickler:innen mit Tool und ohne Tool?
  - Wie unterscheiden sich die erstellten Anwendungen bzgl. Performance und HIGs?
- Nach der Auswertung und Interpretation kann die Frage beantwortet werden
- Die Rohdaten und Auswertungen können nun gespeichert werden

**Überlegen Sie, welche Annahmen und Randbedingungen für Ihre Untersuchung relevant sind**

- Randbedingung, dass Entwickler:innen ähnliches Vorwissen haben
- Randbedingung, dass vergleichbare Beispielapps mit und ohne Tool entwickelt werden können
- Randbedingung, dass Entwickler:innen gewissenhaft Zeiten eintragen
- Annahme, dass Entwickler:innen bei gleicher Komplexität vergleichbar lange für die Entwicklung brauchen
- Annahme, dass Entwickler:innen ähnliche vergleichbaren Tools zuvor verwendet hatten
