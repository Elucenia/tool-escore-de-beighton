<!-- ELUCENIA technical documentation · escore-de-beighton · fr · no clinical/professional/rights approval -->

# Score de Beighton

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-de-beighton)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Tranche d’âge

`faixa`

- `pre` — Prépubère
- `adulto` — De la puberté à 50 ans
- `idoso` — Plus de 50 ans

### Extension passive du 5e doigt droit au-delà de 90°

`dedo_d`

### Extension passive du 5e doigt gauche au-delà de 90°

`dedo_e`

### Le pouce droit touche l’avant-bras (flexion passive)

`polegar_d`

### Le pouce gauche touche l’avant-bras (flexion passive)

`polegar_e`

### Hyperextension du coude droit au-delà de 10°

`cotovelo_d`

### Hyperextension du coude gauche au-delà de 10°

`cotovelo_e`

### Hyperextension du genou droit au-delà de 10°

`joelho_d`

### Hyperextension du genou gauche au-delà de 10°

`joelho_e`

### Pose les paumes au sol avec les genoux tendus

`tronco`

## Édition de la méthode

Beighton 1973 : 9 points ; seuils d’âge EDS 2017 ; pas de diagnostic automatique

## Formule documentée

1 par manœuvre positive, de chaque côté si bilatérale : cinquième doigt (2), pouce (2), coude (2), genou (2), flexion du tronc (1). Total 0 à 9.

Hypermobilité généralisée (2017) : ≥6 prépubères ; ≥5 de puberté à 50 ans ; ≥4 après 50 ans.

## Limites et population

Le Beighton évalue l’hypermobilité articulaire généralisée ; il ne diagnostique pas à lui seul le syndrome d’Ehlers–Danlos hypermobile. Dans la classification de 2017, les seuils sont d’au moins 6 chez les enfants et adolescents prépubères, 5 chez les personnes pubères et les adultes jusqu’à 50 ans, et 4 au-delà de 50 ans. Chirurgie, amputation, fauteuil roulant, blessures et autres limitations acquises peuvent empêcher les manœuvres ; documentez-les. Les antécédents d’hypermobilité peuvent compléter l’examen, mais la classification de 2017 précise que le questionnaire historique à cinq questions n’avait pas été validé chez les enfants. Le diagnostic de hEDS exige les trois ensembles de critères et l’exclusion d’autres causes.

## Références

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Hypermobilité articulaire généralisée (seuil ≥ 5 pour la tranche d’âge)

L’hypermobilité n’est pas une maladie : rechercher une douleur chronique, des luxations et des signes systémiques avant d’envisager un syndrome d’Ehlers-Danlos hypermobile.


### 2

En dessous du seuil d’hypermobilité généralisée (≥ 6 pour la tranche d’âge)


### 3

Hypermobilité articulaire généralisée (seuil ≥ 4 pour la tranche d’âge)

L’hypermobilité n’est pas une maladie : rechercher une douleur chronique, des luxations et des signes systémiques avant d’envisager un syndrome d’Ehlers-Danlos hypermobile.


### 4

En dessous du seuil d’hypermobilité généralisée (≥ 5 pour la tranche d’âge)

