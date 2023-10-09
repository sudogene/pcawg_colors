# Pancancer Analysis of Whole Genomes (PCAWG) colors

A quick reference library for data visualization on Python following the standard colors used in PCAWG figures.

From the color reference table found [here](https://dcc.icgc.org/releases/PCAWG/terminology_and_standard_colours).

## Installation
```
pip install pcawg-colors
```

## Usage Example
```python
import pcawg_colors as pc

color1 = pc.coding_snv.nonsynonymous
color2 = pc.chromosomes.chr1
color3 = pc.tumour_subtype.Breast_AdenoCA
```
For all fields, see <b>Reference to fields</b> below.

## Reference to fields

#### Coding SNV
```python
coding_snv.indel_frameshift
coding_snv.indel_nonframeshift
coding_snv.nonsynonymous
coding_snv.splicing
coding_snv.stopgain
coding_snv.stoploss
coding_snv.synonymous
```
#### Noncoding SNV
```python
noncoding_snv.enhancer
noncoding_snv.insulator
noncoding_snv.intergenic
noncoding_snv.intronic
noncoding_snv.lncRNA
noncoding_snv.miRNA
noncoding_snv.noncoding
noncoding_snv.operator
noncoding_snv.promoter
noncoding_snv.rRNA
noncoding_snv.silencer
noncoding_snv.sncRNA
noncoding_snv.tRNA
noncoding_snv.telomeres
noncoding_snv.utr5_utr3
```
#### Structural Variants
```python
structural_variants.CNA_gain
structural_variants.CNA_loss
structural_variants.inversion
structural_variants.translocation
structural_variants.transposition
```
#### Chromosomes
```
chromosomes.chr1
chromosomes.chr10
chromosomes.chr11
chromosomes.chr12
chromosomes.chr13
chromosomes.chr14
chromosomes.chr15
chromosomes.chr16
chromosomes.chr17
chromosomes.chr18
chromosomes.chr19
chromosomes.chr2
chromosomes.chr20
chromosomes.chr21
chromosomes.chr22
chromosomes.chr3
chromosomes.chr4
chromosomes.chr5
chromosomes.chr6
chromosomes.chr7
chromosomes.chr8
chromosomes.chr9
chromosomes.chrX
chromosomes.chrY
```
#### Sex
```python
sex.male
sex.female
```
#### Stage Arabic
```python
stage_arabic.st1
stage_arabic.st2
stage_arabic.st3
stage_arabic.st4
```
#### Stage Roman
```python
stage_roman.st1
stage_roman.st2
stage_roman.st3
stage_roman.st4
```
#### T Category
```python
t_category.t0
t_category.t1
t_category.t2
t_category.t3
t_category.t4
t_category.tx
```
#### N Category
```python
n_category.n0
n_category.n1
n_category.n2
n_category.n3
n_category.n4
n_category.nx
```
#### M Category
```python
m_category.m0
m_category.m1
m_category.mx
```
#### Grade
```python
grade.g1
grade.g2
grade.g3
grade.g4
```
#### Prostate Grade
```python
prostate_grade.g3_3
prostate_grade.g3_4
prostate_grade.g3_5
prostate_grade.g4_3
prostate_grade.g4_4
prostate_grade.g4_5
prostate_grade.g5_3
prostate_grade.g5_4
prostate_grade.g5_5
```
#### Primary Met
```python
primary_met.metastatic
primary_met.primary
```
#### Tumour Subtype
```python
tumour_subtype.Biliary_AdenoCA
tumour_subtype.Bladder_TCC
tumour_subtype.Bone_Epith
tumour_subtype.Bone_Osteosarc
tumour_subtype.Breast_AdenoCA
tumour_subtype.CNS_GBM
tumour_subtype.CNS_Medullo
tumour_subtype.CNS_Oligo
tumour_subtype.CNS_PiloAstro
tumour_subtype.Cervix_SCC
tumour_subtype.ColoRect_AdenoCA
tumour_subtype.Eso_AdenoCA
tumour_subtype.Head_SCC
tumour_subtype.Kidney_ChRCC
tumour_subtype.Kidney_RCC
tumour_subtype.Liver_HCC
tumour_subtype.Lung_AdenoCA
tumour_subtype.Lung_SCC
tumour_subtype.Lymph_BNHL
tumour_subtype.Lymph_CLL
tumour_subtype.Myeloid_AML
tumour_subtype.Myeloid_MPN
tumour_subtype.Ovary_AdenoCA
tumour_subtype.Panc_AdenoCA
tumour_subtype.Panc_Endocrine
tumour_subtype.Prost_AdenoCA
tumour_subtype.Skin_Melanoma
tumour_subtype.SoftTissue_Leiomyo
tumour_subtype.SoftTissue_Liposarc
tumour_subtype.Stomach_AdenoCA
tumour_subtype.Thy_AdenoCA
tumour_subtype.Uterus_AdenoCA
```
#### Low Sample Size Cohort
```python
low_sample_size_cohort.Bone_Cart
low_sample_size_cohort.Breast_DCIS
low_sample_size_cohort.Breast_LobularCA
low_sample_size_cohort.Cervix_AdenoCA
low_sample_size_cohort.Lymph_NOS
low_sample_size_cohort.Myeloid_MDS
```
#### Organ System
```python
organ_system.biliary
organ_system.bladder
organ_system.bone_softtissue
organ_system.breast
organ_system.cervix
organ_system.cns
organ_system.colon_rectum
organ_system.esophagus
organ_system.head_neck
organ_system.kidney
organ_system.liver
organ_system.lung
organ_system.lymphoid
organ_system.myeloid
organ_system.ovary
organ_system.pancreas
organ_system.prostate
organ_system.skin
organ_system.stomach
organ_system.thyroid
organ_system.uterus
```
