# rSWeeP
<button onclick="window.location.href='https://camilapperico.github.io/';">**HOME**</button>

rSWeeP is a Bioconductor package aimed to vectorze biological sequences (amino acids or nucleotides).

We've provided some tutorials on the rSWeeP package:
1. To get started, access the package's [**QuickStart**](https://camilapperico.github.io/rSWeeP_quickstart.html);
2. The [**Parameters**](https://camilapperico.github.io/rSWeeP_parameters.html) tutorial details the use of function parameters and indicates the best set of parameters for each application;
3. We provide an example with [**Azoarcus**](https://camilapperico.github.io/rSWeeP_Azoarcus.html) data from a study by [Raittz, *et al.* (2021)](https://doi.org/10.3390/genes12010071);
4. We provide an example with data from *Bacterial Proteomes* from a study carried out by Perico, *et al.* (2024) [in the process of being published].

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

## License

This package is released in the public domain under the creative commons license [CC0](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal). 
