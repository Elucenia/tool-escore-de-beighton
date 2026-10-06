<!-- ELUCENIA technical documentation · escore-de-beighton · de · no clinical/professional/rights approval -->

# Beighton-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-de-beighton)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Altersgruppe

`faixa`

- `pre` — Präpubertär
- `adulto` — Ab Pubertät bis 50 Jahre
- `idoso` — Über 50 Jahre

### Passive Streckung des 5. Fingers rechts über 90°

`dedo_d`

### Passive Streckung des 5. Fingers links über 90°

`dedo_e`

### Der rechte Daumen berührt den Unterarm (passive Beugung)

`polegar_d`

### Der linke Daumen berührt den Unterarm (passive Beugung)

`polegar_e`

### Überstreckung des rechten Ellenbogens über 10°

`cotovelo_d`

### Überstreckung des linken Ellenbogens über 10°

`cotovelo_e`

### Überstreckung des rechten Knies über 10°

`joelho_d`

### Überstreckung des linken Knies über 10°

`joelho_e`

### Legt die Handflächen bei gestreckten Knien auf den Boden

`tronco`

## Fassung der Methode

Beighton 1973: 9 Punkte; Altersgrenzen EDS 2017; keine automatische neue Diagnose

## Dokumentierte Formel

1 je positivem Test, beidseitig je Seite: fünfter Finger (2), Daumen (2), Ellbogen (2), Knie (2), Rumpfbeugung (1). Gesamt 0 bis 9.

Generalisierte Hypermobilität (2017): ≥6 vor Pubertät; ≥5 ab Pubertät bis 50 Jahre; ≥4 über 50 Jahre.

## Grenzen und Population

Beighton beurteilt generalisierte Gelenkhypermobilität; er diagnostiziert nicht allein das hypermobile Ehlers–Danlos-Syndrom. In der Klassifikation 2017 liegen die Grenzwerte bei mindestens 6 für präpubertäre Kinder und Jugendliche, 5 für pubertäre Personen und Erwachsene bis 50 Jahre sowie 4 über 50 Jahre. Operationen, Amputationen, Rollstuhlnutzung, Verletzungen und andere erworbene Einschränkungen können die Manöver verhindern; dokumentieren Sie diese. Die Hypermobilitätsanamnese kann die Untersuchung ergänzen; die Klassifikation 2017 weist jedoch darauf hin, dass der historische Fünf-Fragen-Fragebogen bei Kindern nicht validiert war. Die hEDS-Diagnose erfordert alle drei Kriteriengruppen und den Ausschluss anderer Ursachen.

## Referenzen

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Generalisierte Gelenkhypermobilität (Cutoff ≥ 5 für die Altersgruppe)

Hypermobilität ist keine Krankheit: chronische Schmerzen, Luxationen und systemische Zeichen abklären, bevor an ein hypermobiles Ehlers-Danlos-Syndrom gedacht wird.


### 2

Unterhalb des Cutoffs für generalisierte Hypermobilität (≥ 6 für die Altersgruppe)


### 3

Generalisierte Gelenkhypermobilität (Cutoff ≥ 4 für die Altersgruppe)

Hypermobilität ist keine Krankheit: chronische Schmerzen, Luxationen und systemische Zeichen abklären, bevor an ein hypermobiles Ehlers-Danlos-Syndrom gedacht wird.


### 4

Unterhalb des Cutoffs für generalisierte Hypermobilität (≥ 5 für die Altersgruppe)

