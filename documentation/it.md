<!-- ELUCENIA technical documentation · escore-de-beighton · it · no clinical/professional/rights approval -->

# Punteggio di Beighton

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-de-beighton)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Fascia d’età

`faixa`

- `pre` — Prepuberale
- `adulto` — Dalla pubertà fino a 50 anni
- `idoso` — Oltre 50 anni

### Estensione passiva del 5° dito destro oltre 90°

`dedo_d`

### Estensione passiva del 5° dito sinistro oltre 90°

`dedo_e`

### Il pollice destro tocca l’avambraccio (flessione passiva)

`polegar_d`

### Il pollice sinistro tocca l’avambraccio (flessione passiva)

`polegar_e`

### Iperestensione del gomito destro oltre 10°

`cotovelo_d`

### Iperestensione del gomito sinistro oltre 10°

`cotovelo_e`

### Iperestensione del ginocchio destro oltre 10°

`joelho_d`

### Iperestensione del ginocchio sinistro oltre 10°

`joelho_e`

### Appoggia i palmi a terra con le ginocchia estese

`tronco`

## Edizione del metodo

Beighton 1973: 9 punti; soglie d’età EDS 2017; nessuna nuova diagnosi automatica

## Formula documentata

1 per manovra positiva, ogni lato se bilaterale: quinto dito (2), pollice (2), gomito (2), ginocchio (2), flessione tronco (1). Totale 0 a 9.

Ipermobilità generalizzata (2017): ≥6 prepuberi; ≥5 da pubertà a 50 anni; ≥4 oltre 50.

## Limiti e popolazione

Il Beighton valuta l’ipermobilità articolare generalizzata; da solo non diagnostica la sindrome di Ehlers–Danlos ipermobile. Nella classificazione del 2017, le soglie sono almeno 6 nei bambini e adolescenti prepuberi, 5 nelle persone puberi e negli adulti fino a 50 anni, e 4 oltre 50 anni. Chirurgia, amputazione, uso della sedia a rotelle, lesioni e altre limitazioni acquisite possono impedire le manovre; documentale. La storia di ipermobilità può integrare l’esame, ma la classificazione del 2017 precisa che il questionario anamnestico di cinque domande non era stato validato nei bambini. La diagnosi di hEDS richiede tutti e tre i gruppi di criteri e l’esclusione di altre cause.

## Riferimenti

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
