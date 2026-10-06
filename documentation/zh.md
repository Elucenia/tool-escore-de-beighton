<!-- ELUCENIA technical documentation · escore-de-beighton · zh · no clinical/professional/rights approval -->

# Beighton 评分

[条件、来源与许可](https://elucenia.org/zh/tools/escore-de-beighton)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 年龄组

`faixa`

- `pre` — 青春期前
- `adulto` — 青春期起至50岁
- `idoso` — 超过50岁

### 右侧第 5 指被动伸展超过 90°

`dedo_d`

### 左侧第 5 指被动伸展超过 90°

`dedo_e`

### 右侧拇指触及前臂（被动屈曲）

`polegar_d`

### 左侧拇指触及前臂（被动屈曲）

`polegar_e`

### 右侧肘关节过伸超过 10°

`cotovelo_d`

### 左侧肘关节过伸超过 10°

`cotovelo_e`

### 右侧膝关节过伸超过 10°

`joelho_d`

### 左侧膝关节过伸超过 10°

`joelho_e`

### 膝关节伸直时双手掌可贴地

`tronco`

## 方法版本

Beighton 1973：9分；EDS 2017年龄阈值；不自动作新诊断

## 已记录的公式

每阳性动作1分，双侧各计：第五指（2）、拇指（2）、肘（2）、膝（2）、躯干前屈（1）。总分0至9。

全身性关节过度活动（2017）：青春期前儿童及青少年≥6；青春期至50岁≥5；超过50岁≥4。

## 限制与适用人群

Beighton评估全身性关节过度活动，不能单独诊断关节过度活动型埃勒斯–当洛综合征。2017年分类的截点为：青春期前儿童和青少年至少6分，已进入青春期者及不超过50岁的成人至少5分，超过50岁者至少4分。手术、截肢、使用轮椅、损伤及其他后天限制可能使动作无法完成；请记录这些情况。关节过度活动史可补充体格检查，但2017年分类指出，当时五项病史问卷尚未在儿童中验证。hEDS诊断必须满足全部三组标准，并排除其他原因。

## 参考文献

- [Beighton P, Solomon L, Soskolne CL. Articular mobility in an African population. Ann Rheum Dis, 1973.](https://doi.org/10.1136/ard.32.5.413)

- [Malfait F et al. The 2017 international classification of the Ehlers-Danlos syndromes. Am J Med Genet C Semin Med Genet, 2017.](https://doi.org/10.1002/ajmg.c.31552)

- [Malfait2017](https://www.ehlers-danlos.com/wp-content/uploads/2022/12/Malfait_et_al-2017-American_Journal_of_Medical_Genetics_Part_C__Seminars_in_Medical_Genetics.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

全身关节过度活动（该年龄组截点≥ 5）

关节过度活动并非疾病：在考虑高移动型Ehlers-Danlos综合征之前，应先评估慢性疼痛、脱位和全身性体征。


### 2

低于全身性过度活动的截点（该年龄组≥ 6）


### 3

全身关节过度活动（该年龄组截点≥ 4）

关节过度活动并非疾病：在考虑高移动型Ehlers-Danlos综合征之前，应先评估慢性疼痛、脱位和全身性体征。


### 4

低于全身性过度活动的截点（该年龄组≥ 5）

