<!-- ELUCENIA technical documentation · escore-de-beighton · ja · no clinical/professional/rights approval -->

# Beightonスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/escore-de-beighton)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 年齢区分

`faixa`

- `pre` — 思春期前
- `adulto` — 思春期から50歳まで
- `idoso` — 50歳超

### 右第5指の他動伸展が90°を超える

`dedo_d`

### 左第5指の他動伸展が90°を超える

`dedo_e`

### 右母指が前腕に接触（他動屈曲）

`polegar_d`

### 左母指が前腕に接触（他動屈曲）

`polegar_e`

### 右肘関節の過伸展が10°を超える

`cotovelo_d`

### 左肘関節の過伸展が10°を超える

`cotovelo_e`

### 右膝関節の過伸展が10°を超える

`joelho_d`

### 左膝関節の過伸展が10°を超える

`joelho_e`

### 膝を伸ばしたまま両手掌を床につける

`tronco`

## 方法の版

Beighton 1973：9点、EDS 2017年齢閾値、自動的な新規診断なし

## 記載された計算式

陽性動作ごと1点、両側は各側：第5指（2）、母指（2）、肘（2）、膝（2）、体幹前屈（1）。合計0～9。

全身性過可動性（2017）：思春期前の小児・青少年≥6、思春期～50歳≥5、50歳超≥4。

## 限界・対象集団

Beightonは全身性関節過可動性を評価しますが、それだけで関節過可動型エーラス・ダンロス症候群を診断するものではありません。2017年分類の基準値は、思春期前の小児・青年で6以上、思春期以降の人と50歳までの成人で5以上、50歳超で4以上です。手術、切断、車椅子使用、外傷、その他の後天的制限により手技ができない場合は記録してください。過可動性の既往歴は診察を補いますが、2017年分類は、病歴を尋ねる五項目質問票が小児では検証されていなかったとしています。hEDS診断には三群すべての基準と他の原因の除外が必要です。

## 参考文献

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

全身性関節過可動性（年齢群のカットオフ≥ 5）

過可動性は病気ではない。ハイパーモバイル型エーラス・ダンロス症候群を考える前に、慢性疼痛、脱臼、全身徴候を評価する。


### 2

全身性関節過可動性のカットオフ未満（年齢群で≥ 6）


### 3

全身性関節過可動性（年齢群のカットオフ≥ 4）

過可動性は病気ではない。ハイパーモバイル型エーラス・ダンロス症候群を考える前に、慢性疼痛、脱臼、全身徴候を評価する。


### 4

全身性関節過可動性のカットオフ未満（年齢群で≥ 5）

