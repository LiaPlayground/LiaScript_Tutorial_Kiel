<!--
author:   Sebastian Zug, André Dietrich

email:    Sebastian.Zug@informatik.tu-freiberg.de

version:  0.0.1

language: de

narrator: Deutsch Male

mode:     Presentation

comment:  Dieser Kurs für in das Projekt LiaScript ein und diskutiert die
          Vorteile im Kontext der OER Idee.

logo:     ./images/logo.png

import: https://raw.githubusercontent.com/LiaTemplates/Rextester/master/README.md
        https://raw.githubusercontent.com/liaTemplates/processingjs/master/README.md

translation: Deutsch  translations/German.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/SebastianZug/WillkommenAufLiaScript/master/eTeach_Talk.md#1)

# A) Open Educational Ressources (OER) - Vision und Herausforderungen

![OER logo](images/Global_Open_Educational_Resources_Logo.png "OER-Logo - Quelle: Jonathasmello - Eigenes Werk, CC BY 3.0, [https://commons.wikimedia.org/w/index.php?curid=18460156](https://commons.wikimedia.org/w/index.php?curid=18460156)")

Diese Präsentation beschreibt die Vision der _Open Educational Ressources_ mit LiaScript. Der Beitrag wurde im Rahmen eines Tutorials an der CAU zu Kiel am 5. Mai 2022 vorgestellt.

_ Der Quellcode kann des Open Source Dokuments ist unter [Link](https://github.com/SebastianZug/WillkommenAufLiaScript/blob/master/eTeach_Talks.md) zu finden._

------------------------------------------------------

Sebastian Zug, André Dietrich

Fakultät für Mathematik und Informatik

TU Bergakademie Freiberg

[sebastian.zug@informatik.tu-freiberg.de](mailto:sebastian.zug@informatik.tu-freiberg.de)

------------------------------------------------------

## OER Vision

> {0-1}{Lehrende möchten motivierende, interaktive Lehrmaterialien realisieren.}
> {1-2}{Lehrende möchten motivierende, interaktive Lehrmaterialien mit einem überschaubaren Aufwand realisieren.}
> {2-3}{Lehrende möchten maximal motivierende, interaktive Lehrmaterialien mit einem überschaubaren Aufwand realisieren, die optimal auf die eigenen didaktischen Ziele abgestimmt sind.}

{{3}}
********************************************************************************

> Das kann er/sie natürlich alleine realisieren, aber ...

---------------------

**1. Muss er/sie sich über alle Inhalte selbst Gedanken machen**

Beispiel:


- [[male (der)] (female [die]) [neuter (das)]]
- [    [X]           [ ]             [ ]     ]  Mann - German for man
- [    ( )           (X)             ( )     ]  Frau - German for woman

---------------------

**2. Muss er/sie sich erheblichen technischen Herausforderungen stellen**

Beispiel:

??[ear model](https://sketchfab.com/3d-models/ear-anatomy-468e2039bde34a3fabb9e90bff9cd56b)

---------------------

********************************************************************************

### Ausgangspunkt

>  **Open Courseware / Open Educational Resources** ... teaching, learning and
> research materials in any medium, digital or otherwise,that reside in the
> **public domain** or have been released under an open license that permits
> no-cost access, use, **adaptation** and **redistribution** by others with no or 4
> limited restrictions. Open licensing is built within the existing framework of
> intellectual property rights as defined by relevant international conventions
> and respects the authorship of the work
>
> -- UNESCO 2002 Forum on the Impact of Open Courseware for Higher Education in Developing Countries [(Link)](https://unesdoc.unesco.org/ark:/48223/pf0000128515)

           {{0-1}}
********************************************************************************

| Anforderung                  | Bedeutung                                  |
| ---------------------------- | ------------------------------------------ |
| `verwahren/vervielfältigen ` | Download, Speicherung und Vervielfältigung |
| `verwenden`                  | Nutzung im Lernkontext                     |
| `verarbeiten`                | Umgestaltung und Adaption                  |
| `vermischen`                 | Kombination und Extraktion                 |
| `verbreiten`                 | (digitale) Publikation                     |


*_5 V-Freiheiten für Offenheit_ von Jöran Muuß-Merholz und Jörg Lohrer für [open-educational-ressources](https://open-educational-resources.de) - Transferstelle für OER*

> _OER können der Auslöser für Innovation und neue Lenrformen des 21. Jahrhunderts sein._
>
> -- _Handreichung OER - Der Einstieg in den Umgang mit Open Educational Ressources_, Bericht des Projektes OERsax, 2018

********************************************************************************


### Ideales OER Material - ein Textdokument

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii

Kurs.txt         Version 1.0          Kurs.txt          Version 1.1
+--------------------------+          +---------------------------+
| Kurs  Deutsche Literatur |          | Kurs  Deutsche Literatur  |
| Autor Peter Muster       | "Fehler" | Autoren Peter Muster      |
|                          |------>   |         Angelika Maier    |----->
|~~~~~~~~~~~~~~~~~~~~~~~~~~|          |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
| Ab 1756 bereiste Goethe  |---.      | Ab 1786 bereiste Goethe   |--.
| Italien ...              |   |      | Italien ...               |  |
                               |                                     |    Course.txt       Version 1.1.2
                               |                                     |    +----------------------------+
                               |                                     |    | Kurs  German Literature    |
                               |                                     |    | Autoren Peter Muster       |
                               |                                     .--> |         Angelika Maier     |
                               |                                          |         Steve Gray         |
                               |                                          |~~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                               |                                          | In 1786 Goethe traveled to |
                               |                                          | Italy ...                  |
                               |      Kurs.txt         Version 1.0
                               |      +---------------------------+
                               |      | Kurs  Goethes Welt        |
                               |      | Autoren Peter Muster      |
                               .-->   |         Angelika Maier    |----->
                                      |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                                      | Während der italienischen |
                                      | Reise ...                 |
```
*Versionen der Lehrinhalte eines Kurses und deren Wiederverwendung in anderen Veranstaltungen*

{{0-1}}
********************************************************************************

| Anforderung                  | txt |                                                          |
| ---------------------------- | --- | -------------------------------------------------------- |
| `verwahren/vervielfältigen ` | ++  | vorteilhaft wegen geringer Größe                         |
| `verwenden`                  | +   | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                | ++  | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                 | ++  | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                 | ++  | gut exportierbar                                         |

> **Moment, ein reines Textdokument ist als OER Inhalt perfekt?**

********************************************************************************

{{1-2}}
********************************************************************************

> _1. Die 5V Definition fokussiert das Open in OER lässt aber das Education beiseite._
>
> _2. Die Verwaltung und Auffindbarkeit von OER Inhalten ist dadurch nicht erfasst._

| Anforderung                                           | txt                           |                                                          |
| ----------------------------------------------------- | ----------------------------- | -------------------------------------------------------- |
| `verwahren/vervielfältigen `                          | ++                            | vorteilhaft wegen geringer Größe                         |
| `verwenden`                                           | +                             | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                                         | ++                            | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                                          | ++                            | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                                          | ++                            | gut exportierbar                                         |
| <!-- Style="color:green" --> verwalten / versionieren | ++                            |                                                          |
| <!-- Style="color:green" -->   motivieren             | <!-- Style="color:red" --> -- | keine zeitgemäßen Formate und interaktiven Inhalte       |

> __Offensichtlich brauchen wir Formate, die neben den positiven Aspekten von Textdarstellungen auch das erweiterte Set von Anforderungen abdecken.__

********************************************************************************

### Kritik am OER-Ansatz

| Ebene                               | Kernaussage                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| Emotionale Einordnung               | "_Da kann ja jeder meine Arbeit für sich nutzen!_"                                      |
|                                     | "_Da kann mich ja jeder kontrollieren!_"                                                |
| Rechtliche Herausforderungen        | "_Ich verwende viele Grafiken, die bei deren Urheberrecht ich mir im besten Fall unsicher bin!_"                                                                                        |
| Auffindbarkeit                      | "_Ich finde keine Inhalte, die ich in meiner Lehre gewinnbringend integrieren kann!_"   |
| <!-- Style="color:red" --> Aufwand  | <!-- Style="color:red" --> "_Da muss man ja Informatik studiert haben!_"                |
| <!-- Style="color:red" -->Abdeckung | <!-- Style="color:red" -->"_Da fehlen mir aber die Schnittstellen für meine Tools XY!_" |

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii

      Wunsch nach                                             Wunsch nach
  einfacher Umsetzung  -----------> Konflikt <----------- spezifischen Elementen
                                       |                       im Material
                                       |
                                       v
                              OER als Lösungsansatz

```

## OER Praxis

> 1. Materialien müssen transformierbar sein, um eine Wiederverwendung zu ermöglichen. (_Verarbeiten/Verwenden/Verbreiten_)
> 2. Materialien brauchen Metadaten, um auffindbar zu sein. (_Verbreiten_)
> 3. Materialien brauchen offenkundige Versionierungen (_Verwalten_)

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii
+------------------+
| # Digital Systems|\                                      .-----------.
| (SoSe 2021)      +-+                              ╔══════|   LMS  X  |══════╗
|                    |  --------------------------> ║      '-----------'      ║
| ## Task 1          |                              ║ Digital Systems 2021    ║
|                    |                              ║                         ║
| + Implement ...    | --------------+              ║ import numpy as np      ║
|                    |    Trans-     |              ║ ...                     ║
|                    |    formation  |              ╚═════════════════════════╝
+--------------------+               v
                                .-,(   ),-.                .-----------.
Lizenz: ...                  .-(           )-.      ╔══════|   LMS  Y  |══════╗
Inhalt: ...                 (    OER Cloud    )     ║      '-----------'      ║
Autor: ...                   '-(           )-'  +-->║ Digital Systems 2021    ║
Versionshistorie: ...           '-.(   ).-'     |   ║                         ║
                                     |          |
                                     +----------+          .-----------.
                                                |   ╔══════|  Webapp   |══════╗
                                                |   ║      '-----------'      ║
                                                +-->║ Digital Systems 2021    ║
                                                    ║                         ║

```
*Transformation von OER Materialien für die Verwendung in verschiedenen LMS*

### OER in OPAL ...

                {{0-1}}
********************************************************************************

Anderen Kursmaterialien zur Verfügung zu stellen, ist in OPAL im Wesentlichen auf 3 Wegen möglich:

+ für ganze Kurse

   - innerhalb der OPAL "Welt" als offene Kurse
   - über Exportschnittstellen, die die Einbettung in andere LMS ermöglichen
   - manuelle Übertragung

+ für einzelne Dateien

   - Dateien mit Meta-Informationen und expliziter Angabe

![alt-text](images/OER_in_OPAL.png "Screenshot eines OER Materials im OPAL LMS, 22. März 2022")

********************************************************************************

                    {{1-2}}
********************************************************************************

Welche Muster lassen sich mit Blick auf die verfügbaren Kurse erkennen?

| Lizenz               | Anzahl |
| -------------------- | ------ |
| keine                | 3764   |
| CC BY 4.0 Int.       | 1499   |
| CC BY-NC 4.0 Int.    | 1675   |
| CC BY-NC-ND 4.0 Int. | 3950   |
| CC BY-NC-SA 4.0 Int. | 977    |
| CC BY-ND 4.0 Int.    | 143    |
| CC BY-SA 4.0 Int.    | 2308   |
| CC0 1.0 Universell   | 834    |


<!-- data-type="BarChart"
data-title="Anteil der Datenformate im Kontext der OPAL OER Materialien"
data-xlabel="Datentyp"
data-ylabel="% of Anzahl" -->
| Dateityp | Anzahl | ratio    |
| -------- | ------ | -------- |
| `pdf`    | 5242   | 0.494995 |
| `jpg`    | 1040   | 0.098206 |
| `mkv`    | 873    | 0.082436 |
| `mp4`    | 586    | 0.055335 |
| `png`    | 494    | 0.046648 |
| `zip`    | 443    | 0.041832 |
| `html`   | 387    | 0.036544 |
| `docx`   | 376    | 0.035505 |
| `pptx`   | 245    | 0.023135 |
| `xlsx`   | 191    | 0.018036 |


Die Materialien im OPAL kommen überwiegend ohne Lizenzen und als geschlossenes Dateiformat daher. Eine Wiederverwendung ist entsprechend nur schwer möglich.

********************************************************************************

### OER in LiaScript ...

*LiaScript* löst den Inhalt vom LMS und erlaubt die Anwendung von Methoden der verteilten Softwareentwicklung.

- Beschreibungssprache
- Verteilte Entwicklung
- Serverlose Infrastruktur
- Dynamische Inhalte

Weitere Informationen finden Sie unter der Projektwebseite [https://liascript.github.io/](https://liascript.github.io/) in der [Dokumentation](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1) oder dem [Youtube-Channel](https://www.youtube.com/channel/UCyiTe2GkW_u05HSdvUblGYg)

       {{1}}
********************************************************************************

**Tabellen**

```markdown
<!-- data-type="BarChart"
data-title="Anteil der Datenformate im Kontext der OPAL OER Materialien"
-->
| Dateityp | Anzahl | ratio    |
| -------- | ------ | -------- |
| `pdf`    | 5242   | 0.494995 |
| `jpg`    | 1040   | 0.098206 |
| `mkv`    | 873    | 0.082436 |
| `mp4`    | 586    | 0.055335 |
| `png`    | 494    | 0.046648 |
| `zip`    | 443    | 0.041832 |
| `html`   | 387    | 0.036544 |
| `docx`   | 376    | 0.035505 |
| `pptx`   | 245    | 0.023135 |
| `xlsx`   | 191    | 0.018036 |
```

********************************************************************************

      {{2}}
********************************************************************************

**Ausführbarer Code**

```
void setup() {
  size(480, 220);
}

void draw() {
  if (mousePressed) {
    fill(0);
  } else {
    fill(255);
  }
  ellipse(mouseX, mouseY, 80, 80);
}
```



```cpp                         Processing.js
void setup() {
  size(480, 220);
}

void draw() {
  if (mousePressed) {
    fill(0);
  } else {
    fill(255);
  }
  ellipse(mouseX, mouseY, 80, 80);
}
```
@Processing.eval

********************************************************************************

      {{3}}
********************************************************************************

**Quizze**

```markdown
Markieren Sie die ungeraden Zahlen!

    [[X]] 1
    [[ ]] 2
    [[X]] 3
    [[?]] Nur zur Erinnerung, wie definiert sich eine ungerade Zahl?
```

Markieren Sie die ungeraden Zahlen!

    [[X]] 1
    [[ ]] 2
    [[X]] 3
    [[?]] Nur zur Erinnerung, wie definiert sich eine ungerade Zahl?

********************************************************************************

### ... und jetzt alles zusammen

In der folgenden Demo wird die Integration von LiaScript auf Basis des Exporters dargestellt. Grundlage ist der OPAL Kurs [Link](https://bildungsportal.sachsen.de/opal/auth/RepositoryEntry/28960423936/CourseNode/103166567950189)

### Erfahrungen bei Einsatz von OER

-> Kursüberblick der Arbeitsgruppe _Softwareentwicklung und Robotik_ auf [GitHub](https://github.com/TUBAF-IfI-LiaScript)

Ergebnisse:

1. Aus der Zusammenarbeit an den Materialien entsteht im Kontext eines Kernteams ein "Wir" Gedanke.
2. Fehler werden deutlich schneller ausgemerzt als in vergangenen Jahren. Die "kurzfristige" Qualität steigt an.
3. Die Interaktion zwischen Lehrenden und Studierenden steigert sich - *"Sollte man das nicht besser so erklären ..."*
4. Das Verständnis über verteilte Entwicklung von Inhalten entwickelt sich sehr positiv, selbst die Nicht-Informatiker beschäftigen sich mit den Methoden.

## OER Forschung

                {{0-1}}
********************************************************************************

1. Wie lässt sich die Auffindbarkeit der OER Materialien steigern?

> Lösungsansatz: Automatische Extraktion von Metainformationen und Klassifikationsmerkmalen

********************************************************************************


                {{1-2}}
********************************************************************************

2. Welche Qualität haben OER Materialien?

![alt-text](images/DeletedArticlesWikipedia.png "Screenshot der Webseite [https://en.wikipedia.org/wiki/Wikipedia:Deleted_articles_with_freaky_titles](https://en.wikipedia.org/wiki/Wikipedia:Deleted_articles_with_freaky_titles), 22. März 2022")

> Lösungsansatz: Textanalyse und Textsemantikuntersuchungen in OER Materialien

********************************************************************************


                {{2-3}}
********************************************************************************

3. Wie lässt sich die Breite der Materialien steigern?

![alt-text](images/OERSI_screenshot.png "Screenshot der Webseite [https://oersi.de/resources/](https://oersi.de/resources/), 22. März 2022")

> Lösungsansatz: Plugin-Konzept in LiaScript

********************************************************************************

## Kontakt

Neugierig geworden auf OER? Sprechen Sie uns an!

| | |
| Prof. Dr. Sebastian Zug | [sebastian.zug@informatik.tu-freiberg.de](mailto:sebastian.zug@informatik.tu-freiberg.de)   |
| Dr. André Dietrich      | [andre.dietrich@informatik.tu-freiberg.de](mailto:andre.dietrich@informatik.tu-freiberg.de) |
