<!-- ELUCENIA technical documentation · escore-de-beighton · en · no clinical/professional/rights approval -->

# Beighton score

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-de-beighton)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Age group

`faixa`

- `pre` — Prepubertal
- `adulto` — Pubertal to 50 years
- `idoso` — Older than 50 years

### Passive extension of the right 5th finger beyond 90°

`dedo_d`

### Passive extension of the left 5th finger beyond 90°

`dedo_e`

### Right thumb touches forearm (passive flexion)

`polegar_d`

### Left thumb touches forearm (passive flexion)

`polegar_e`

### Hyperextension of the right elbow beyond 10°

`cotovelo_d`

### Hyperextension of the left elbow beyond 10°

`cotovelo_e`

### Hyperextension of the right knee beyond 10°

`joelho_d`

### Hyperextension of the left knee beyond 10°

`joelho_e`

### Places palms on the floor with knees straight

`tronco`

## Method edition

Beighton 1973: 9 points; 2017 EDS age thresholds; no automatic new diagnosis

## Documented formula

1 point per positive maneuver, each side when bilateral: fifth finger (2), thumb (2), elbow (2), knee (2), trunk flexion (1). Total 0 to 9.

Generalized hypermobility (2017): ≥6 in prepubertal children/adolescents; ≥5 from puberty to 50 years; ≥4 over 50 years.

## Limits and population

Beighton assesses generalized joint hypermobility; it does not by itself diagnose hypermobile Ehlers–Danlos syndrome. In the 2017 classification, cutoffs are at least 6 in prepubertal children and adolescents, 5 in pubertal individuals and adults up to 50 years, and 4 above 50 years. Surgery, amputation, wheelchair use, injuries and other acquired limitations may prevent maneuvers; document them. A history of hypermobility can complement the examination, but the 2017 classification notes that the five-question historical questionnaire had not been validated in children. Diagnosis of hEDS requires all three sets of criteria and exclusion of other causes.

## References

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Generalized joint hypermobility (cutoff ≥ 5 for the age group)

Hypermobility is not a disease: investigate chronic pain, dislocations, and systemic signs before considering hypermobile Ehlers-Danlos syndrome.


### 2

Below the cutoff for generalized hypermobility (≥ 6 for the age group)


### 3

Generalized joint hypermobility (cutoff ≥ 4 for the age group)

Hypermobility is not a disease: investigate chronic pain, dislocations, and systemic signs before considering hypermobile Ehlers-Danlos syndrome.


### 4

Below the cutoff for generalized hypermobility (≥ 5 for the age group)

