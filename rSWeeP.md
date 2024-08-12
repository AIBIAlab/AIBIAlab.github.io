# rSWeeP

<button onclick="window.location.href='https://aibialab.github.io/';">**HOME**</button>

The *rSWeeP* package is an R implementation of the Spaced Words Projection (SWeeP) method (De Pierri, 2019). The main function of this package is to provide a vector representation of biological sequences (nucleotides or amino acids), and thus favor alignment-free phylogenetic studies. Each sequence provided is represented by a compact numerical vector which is easier to analyze. SWeeP uses k-mers counting for representing the sequences in high dimensional vector (HDV) and then projected into a low dimensional vector (LDV) through random projection using an orthonormal base. The LDV represents the biological sequence and is handable for comparative analisys and machine learning implements.
In addition, the package allows general dimensionality reduction of RNAseq data and generic matrices. 

  
rSWeeP is a Bioconductor package:

- Use the [link](https://github.com/CamilaPPerico/rSWeeP) to access the package at github
- Use the [link](https://bioconductor.org/packages/devel/bioc/html/rSWeeP.html) to access the last version package at Bioconductor
- For aditional datasets, access the [link](https://github.com/CamilaPPerico/rSWeeP_datasets).
- [FAQ](https://github.com/orgs/AIBIAlab/discussions)

## Tutorial pages

We've provided some tutorials on the rSWeeP package:
1. To get started, access the package's [**QuickStart**](https://aibialab.github.io/rSWeeP_quickstart.html);
2. The [**Parameters**](https://aibialab.github.io/rSWeeP_parameters.html) tutorial details the use of function parameters and indicates the best set of parameters for each application;
3. We provide an example with [**Azoarcus**](https://aibialab.github.io/rSWeeP_Azoarcus.html) data from a study by [Raittz, *et al.* (2021)](https://doi.org/10.3390/genes12010071);
4. [**under construction**]We provide an example with data from *Bacterial Proteomes* from a study carried out by Perico, *et al.* (2024) [in the process of being published].

## Instalation

The current release can be installed from [Bioconductor](https://bioconductor.org/packages/release/bioc/html/rSWeeP.html):

```r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("rSWeeP")
```

## Citation

Please cite this package as follows:

De Pierri, Camilla Reginatto, Ricardo Voyceik, Letı́cia Graziela Costa Santos de Mattos, Mariane Gonçalves Kulik, Josué Oliveira Camargo, Aryel Marlus Repula de Oliveira, Bruno Thiago de Lima Nichio, et al. 2020. “SWeeP: Representing Large Biological Sequences Datasets in Compact Vectors.” Scientific Reports 10 (1): 1–10. <https://doi.org/10.1038/s41598-019-55627-4>. 
