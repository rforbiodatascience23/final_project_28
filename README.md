# Project Contributors

skrendaskrenduolis - s222858 \
tudelska - s212846 \
tado512 - s170362 \
beleonattila - s213785 \
s222372 - s222373 \

# final_project_28

group 28 r4bds final project

# Data availability 

The data set used in this project was originally published by Gloub et al.
(1999)
https://www-science-org.proxy.findit.cvt.dk/doi/10.1126/science.286.5439.531#body-ref-RF14
and was downloaded from
<https://www.kaggle.com/datasets/crawford/gene-expression/>.

Download the data and extract the .csv files to the folder `_raw` that is in the same directory as the R project.

# Brief data description

There are 3 files of interest in `../_raw/`:

1.  `actual.csv`,

2.  `data_set_ALL_AML_independent.csv`, and

3.  `data_set_ALL_AML_train.csv`.

The first one contains (numeric) patient IDs in column 'patient' and cancer type
(ALL for acute lymphoblastic leukemia, AML for acute myeloid leukemia) in column
'cancer'. The remaining two contain gene expression data per gene in row, while
the columns hold information on each gene's description, its accession number,
patient ID and something denoted gene "call". The latter refers to whether the
authors of the paper deemed the gene present (P), marginal (M), or absent (A) in
the sample from each patient.
