<!-- ELUCENIA technical documentation · escore-de-beighton · es · no clinical/professional/rights approval -->

# Puntuación de Beighton

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-de-beighton)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Grupo de edad

`faixa`

- `pre` — Prepuberal
- `adulto` — De la pubertad hasta los 50 años
- `idoso` — Mayor de 50 años

### Extensión pasiva del 5.º dedo derecho más allá de 90°

`dedo_d`

### Extensión pasiva del 5.º dedo izquierdo más allá de 90°

`dedo_e`

### El pulgar derecho toca el antebrazo (flexión pasiva)

`polegar_d`

### El pulgar izquierdo toca el antebrazo (flexión pasiva)

`polegar_e`

### Hiperextensión del codo derecho más allá de 10°

`cotovelo_d`

### Hiperextensión del codo izquierdo más allá de 10°

`cotovelo_e`

### Hiperextensión de la rodilla derecha más allá de 10°

`joelho_d`

### Hiperextensión de la rodilla izquierda más allá de 10°

`joelho_e`

### Apoya las palmas en el suelo con las rodillas extendidas

`tronco`

## Edición del método

Beighton 1973: 9 puntos; umbrales por edad EDS 2017; sin nuevo diagnóstico automático

## Fórmula documentada

1 por maniobra positiva, cada lado si bilateral: quinto dedo (2), pulgar (2), codo (2), rodilla (2), flexión del tronco (1). Total 0 a 9.

Hipermovilidad generalizada (2017): ≥6 prepuberales; ≥5 desde pubertad a 50 años; ≥4 mayores de 50.

## Límites y población

El Beighton evalúa hipermovilidad articular generalizada; no diagnostica por sí solo el síndrome de Ehlers–Danlos hipermóvil. En la clasificación de 2017, los puntos de corte son al menos 6 en niños y adolescentes prepúberes, 5 en personas púberes y adultos de hasta 50 años, y 4 por encima de 50 años. Cirugía, amputación, uso de silla de ruedas, lesiones y otras limitaciones adquiridas pueden impedir las maniobras; documéntelas. Los antecedentes de hipermovilidad pueden complementar el examen, pero la clasificación de 2017 señala que el cuestionario histórico de cinco preguntas no se había validado en niños. El diagnóstico de hEDS exige los tres conjuntos de criterios y excluir otras causas.

## Referencias

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
