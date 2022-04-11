---
layout: single
title: "Praktikum Computeralgebra"
permalink: /teaching/S22/PraktikumCA/
---

## Sommersemester 2022

### Aktuelles

### Termine

* Parktikumstermine: Mo 16:15—17:45 Uhr (Beginn: 11. April) [Siehe Unisono-Eintrag](https://unisono.uni-siegen.de/qisserver/pages/cm/exa/examEventOverviewOwn/showOverview.xhtml?_flowId=examEventOverviewOwn-flow&_flowExecutionKey=e7s2), der Donnerstagstermin ist als Ausweichtermin gedacht.

### Zielgruppe und benötigte Vorkenntnisse

Das Praktikum Computeralgebra besteht aus zwei Teilen, Teil I und Teil
II. Es richtet sich an Studierende der Mathematik aller Semester.

* Studierende des Fach-Bachelors müssen beide Teile bearbeiten (4 SWS, 6 CP).
* Studierende des Lehramts müssen einen der beiden Teile bearbeiten (2 SWS, 3 CP).

Da das Praktikum jedes Semester angeboten wird, können Studierende des
Fach-Bachelors die Veranstaltung auf zwei Semester strecken, d.h. pro
Semester einen Teil bearbeiten. Die Semester müssen nicht
aufeinanderfolgend sein. Für Studierende des Fach-Bachelors gibt es
die Möglichkeit, in einem Semester beide Teile zu bearbeiten. Dafür
müssen sie an beiden wöchentlich angebotenen Terminen teilnehmen.

Für das Praktikum wird folgendes vorausgesetzt:

* mathematisch: Für Teil I ein Grundverständnis der Mengenlehre und für Teil II der Gauss-Algorithmus und der erweiterte Euklidische Algorithmus
* technisch: Umgang mit einem [Texteditor](https://en.wikipedia.org/wiki/Text_editor) und Grundzüge der [(imperativen) Programmierung](https://de.wikipedia.org/wiki/Imperative_Programmierung):
  * [Zuweisung von Variablen](https://de.wikipedia.org/wiki/Zuweisung)
  * [if-Abfragen](https://de.wikipedia.org/wiki/Bedingte_Anweisung_und_Verzweigung)
  * [for-Schleifen](https://de.wikipedia.org/wiki/For-Schleife)

### Inhalt

Im Teil I des Praktikums werden wir die Kategorie endlicher Mengen
berechenbar machen. Insbesondere werden wir Algorithmen entwickeln, um
Gleichungen in dieser Kategorie lösen zu können. Dies sind die
Aufgaben mit den ungeraden Nummern (1, 3, 5, ... ).

Im Teil II des Praktikums werden wir die Kategorie der Matrizen über
sogenannte Bézout-Ringe berechenbar machen. Zu dieser Klasse von
Ringen gehören alle Körper, der Ring der ganzen Zahlen und univariate
Polynomringe über Körper. Insbesondere werden wir Algorithmen
entwickeln, um lineare Gleichungssysteme über diesen Ringen lösen zu
können. Dies sind die Aufgaben mit den geraden Nummern (2, 4, 6, ...)

### Installation der dazu notwendigen Software auf dem eigenen Rechner

Für die Installation des benötigten Computeralgebrasystems `GAP` auf
dem eigenen Rechner können die Schritte unter `Step 0` auf der
[Installationsseite](https://homalg-project.github.io/docs/installation)
befolgt werden. Die Teilschritte für `ArangoDB` können übersprungen
werden. Für Linux und Windows besteht der letzte Schritt darin, den
folgenden Befehl auszuführen:

```
sudo apt-get install -y gap
```

Der Erfolg der Installation kann anhand des ersten Übungsblattes (siehe unten) getestet werden.

### Blätter

1. [Blatt01 (GAP)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt01.pdf), [Blatt01 (Julia)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt01_julia.pdf)
2. [Blatt02 (GAP)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt02.pdf), [Blatt02 (Julia)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt02_julia.pdf)
3. [Blatt03 (GAP)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt03.pdf), [Blatt03 (Julia)](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt03_julia.pdf)

<!--
4. [Blatt04](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt04.pdf)
5. [Blatt05](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt05.pdf)
6. [Blatt06](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt06.pdf)
7. [Blatt07](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt07.pdf)
8. [Blatt08](https://algebra.mathematik.uni-siegen.de/barakat/Lehre/SS22/Praktikum/Uebungen/blatt08.pdf)
-->
