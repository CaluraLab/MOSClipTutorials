
# MOSClip Tutorials

## Welcome to MOSClip tutorial series!

[`MOSClip`](https://github.com/CaluraLab/MOSClip) is an R package that allows performing multi-omic survival analysis exploiting pathway topology. 

![Cover](figures/cover.png)


## Start guide

If you are looking for tutorials you are in the right place.

In this section you can find a [series of tutorials](https://caluralab.github.io/MOSClipTutorials):

- [how to download data from TCGA](https://caluralab.github.io/MOSClipTutorials/downloadData.html)
- [how to format the dataset for `MOSClip`](https://caluralab.github.io/MOSClipTutorials/formatTCGAdatasets.html) (Needs [functions-to-process-TCGA-data.R](https://caluralab.github.io/MOSClipTutorials/functions-to-process-TCGA-data.R) in the downloadTCGA directory)
- [how to perform a two-class analysis](https://caluralab.github.io/MOSClipTutorials/analysisTCGA2class.html) ([Results](https://github.com/CaluraLab/MOSClipTutorials/tree/main/Rmd/MOSresults/twoClass) of this tutorial are available)


## Data availability

You can download the data generated in these tutorials.

* [pre-processed ovarian cancer dataset](https://caluralab.github.io/MOSClipTutorials/Rmd/downloadTCGA/TCGA-OV-pre-processed.RData)
* [reactome pathways (EntrezIDs)](https://caluralab.github.io/MOSClipTutorials/Rmd/downloadTCGA/reactome-entrez-2024-05-27.RData)
* [two-class analysis results](https://caluralab.github.io/MOSClipTutorials/Rmd/MOSresults/twoClass)


## Installation

You can install `MOSClip` from Bioconductor.

``` r
# Install the package from Bioconductor
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("MOSClip")
```


## References

Paolo Martini, Monica Chiogna, Enrica Calura, and Chiara Romualdi. 2019.
“MOSClip: Multi-Omic and Survival Pathway Analysis for the
Identification of Survival Associated Gene and Modules.” Nucleic Acids
Research 47 (14): e80. <https://doi.org/10.1093/nar/gkz324>