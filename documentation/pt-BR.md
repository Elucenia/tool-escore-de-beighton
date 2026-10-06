<!-- ELUCENIA technical documentation · escore-de-beighton · pt-BR · no clinical/professional/rights approval -->

# Escore de Beighton

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-de-beighton)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Faixa etária

`faixa`

- `pre` — Pré-púbere
- `adulto` — Púbere até 50 anos
- `idoso` — Acima de 50 anos

### Extensão passiva do 5º dedo direito além de 90°

`dedo_d`

### Extensão passiva do 5º dedo esquerdo além de 90°

`dedo_e`

### Polegar direito toca o antebraço (flexão passiva)

`polegar_d`

### Polegar esquerdo toca o antebraço (flexão passiva)

`polegar_e`

### Hiperextensão do cotovelo direito além de 10°

`cotovelo_d`

### Hiperextensão do cotovelo esquerdo além de 10°

`cotovelo_e`

### Hiperextensão do joelho direito além de 10°

`joelho_d`

### Hiperextensão do joelho esquerdo além de 10°

`joelho_e`

### Apoia as palmas das mãos no chão com os joelhos estendidos

`tronco`

## Edição do método

Beighton 1973:9 pontos; limiares etárioscritérios EDS 2017; sem novo diagnóstico automático

## Fórmula documentada

Um ponto por manobra positiva, de cada lado quando bilateral: 5º dedo (2), polegar (2), cotovelo (2), joelho (2) e flexão do tronco (1). Total de 0 a 9.

Hipermobilidade generalizada (critérios de 2017): ≥ 6 em crianças e adolescentes pré-púberes; ≥ 5 de púberes até 50 anos; ≥ 4 acima de 50 anos.

## Limites e população

O Beighton avalia hipermobilidade articular generalizada; não diagnostica, sozinho, síndrome de Ehlers–Danlos hipermóvel. Na classificação de 2017, os cortes são pelo menos 6 em crianças e adolescentes pré-púberes, 5 em púberes e adultos até 50 anos, e 4 acima de 50 anos. Cirurgia, amputação, uso de cadeira de rodas, lesões e outras limitações adquiridas podem impedir manobras; documente-as. O histórico de hipermobilidade pode complementar o exame, mas a classificação de 2017 ressalva que o questionário histórico de cinco perguntas não havia sido validado em crianças. O diagnóstico de hEDS exige os três conjuntos de critérios e a exclusão de outras causas.

## Referências

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Hipermobilidade articular generalizada (corte ≥ 5 para a faixa etária)

Hipermobilidade não é doença: investigue dor crônica, luxações e sinais sistêmicos antes de pensar em síndrome de Ehlers-Danlos hipermóvel.


### 2

Abaixo do corte de hipermobilidade generalizada (≥ 6 para a faixa etária)


### 3

Hipermobilidade articular generalizada (corte ≥ 4 para a faixa etária)

Hipermobilidade não é doença: investigue dor crônica, luxações e sinais sistêmicos antes de pensar em síndrome de Ehlers-Danlos hipermóvel.


### 4

Abaixo do corte de hipermobilidade generalizada (≥ 5 para a faixa etária)

