I'm currently a Senior Principal Scientist and Group Leader in the gRED Computational Sciences Hub at Genentech.
My group focuses on developing robust and modular software tools for implementing computational methods applied to large genomics data. 
Selected works:
- [crisprVerse: design of CRISPR guide RNAs across nucleases and technologies](https://www.nature.com/articles/s41467-022-34320-7), *Nature Communications*
- [Biases in genome-wide pooled CRISPR screening](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1621-7), *Genome Biology*
- [AsCas12a ultra-compact CRISPR screening libraries](https://www.biorxiv.org/content/10.1101/2024.05.30.596755.abstract), *bioRxiv*

Before Genentech, I got my PhD degree in Biostatistics at Johns Hopkins University under the supervision of [Dr. Kasper Hansen](https://www.hansenlab.org), during which I focused on developing statistical methodology for the analysis of methylation array. I then pursued a postdoctoral degree in Neuroinformatics at the University of Pennsylvania with [Dr. Taki Shinohara](https://www.dbeicoe.med.upenn.edu/pennsive). My work focused on the multi-scanner harmonization and normalization of different neuroimaging modalities (MRI, DTI, etc). Selected works from my PhD and Postdoc:

- [Functional normalization for methylation arrays (minfi)](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0503-2), *Genome Biology*
- [Hi-C reconstruction from methylation data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-015-0741-y), *Genome Biology*
- [Processing of Illumina EPIC arrays](https://pubmed.ncbi.nlm.nih.gov/28035024/), *Bioinformatics*
- [shinyMethy: interactive visualization of methylation arrays](https://www.google.com/search?q=shinymethyl+f1000&client=safari&sca_esv=2d0ef86f978a5b91&sca_upv=1&rls=en&sxsrf=ADLYWIKA0JSaPQZcATsYk0wPQQ-OmEsLfQ%3A1722444967776&ei=p2yqZo2JL46V0PEP7tCjoAQ&ved=0ahUKEwjN-MvD39GHAxWOCjQIHW7oCEQQ4dUDCBE&uact=5&oq=shinymethyl+f1000&gs_lp=Egxnd3Mtd2l6LXNlcnAiEXNoaW55bWV0aHlsIGYxMDAwMgcQIRigARgKMgcQIRigARgKMgcQIRigARgKMgcQIRigARgKMgcQIRigARgKSKMLUNMEWKcKcAF4AJABAJgBc6ABxgSqAQM2LjG4AQPIAQD4AQGYAgegArAEwgIIEAAYgAQYsAPCAgsQABiABBiwAxiiBMICBRAhGKsCmAMAiAYBkAYFkgcDNi4xoAeYHg&sclient=gws-wiz-serp), *F1000Research*
- [Harmonization of structural MRI](https://www.sciencedirect.com/science/article/pii/S1053811916001452), *Neuroimage*
- [Harmonization of DTI](https://pubmed.ncbi.nlm.nih.gov/28826946/), *Neuroimage*
- [Harmonization of cortical thickness measurements](https://pubmed.ncbi.nlm.nih.gov/29155184/), *Neuroimage*


## [Bioconductor](https://bioconductor.org) contributions

### As maintainer

|Package|BioC-release|BioC-devel|Description
|---|---|---|---|
|[crisprVerse](https://github.com/crisprVerse/crisprVerse)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprVerse.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprVerse/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprVerse.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprVerse/)|Easily install of the crisprVerse ecosystem|
|[crisprDesign](https://github.com/crisprVerse/crisprDesign)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprDesign.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprDesign/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprDesign.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprDesign/)|Core gRNA design package across nucleases and applications|
|[crisprBase](https://github.com/crisprVerse/crisprBase)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprBase.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprBase/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprBase.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprBase/)|Base functions and classes for CRISPR gRNA design|
|[crisprBowtie](https://github.com/crisprVerse/crisprBowtie)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprBowtie.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprBowtie/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprBowtie.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprBowtie/)|Alignment of gRNA spacer sequences using bowtie|
|[crisprBwa](https://github.com/crisprVerse/crisprBwa)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprBwa.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprBwa/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprBwa.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprBwa/)|Alignment of gRNA spacer sequences using BWA|
|[crisprScore](https://github.com/crisprVerse/crisprScore)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprScore.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprScore/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprScore.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprScore/)|On-target and off-target scoring for CRISPR gRNAs|
|[crisprScoreData](https://github.com/crisprVerse/crisprScoreData)|[![Release OK](https://bioconductor.org/shields/build/release/data-experiment/crisprScoreData.svg)](http://bioconductor.org/checkResults/release/data-experiment-LATEST/crisprScoreData/)|[![Devel OK](https://bioconductor.org/shields/build/devel/data-experiment/crisprScoreData.svg)](http://bioconductor.org/checkResults/devel/data-experiment-LATEST/crisprScoreData/)|Pre-trained models for the crisprScore package|
|[crisprViz](https://github.com/crisprVerse/crisprViz)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprViz.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprViz/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprViz.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprViz/)|Visualization of CRISPR gRNAs using genomic tracks |
|[crisprShiny](https://github.com/crisprVerse/crisprShiny)| [![Release OK](https://bioconductor.org/shields/build/release/bioc/crisprShiny.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/crisprShiny/)| [![Devel OK](https://bioconductor.org/shields/build/devel/bioc/crisprShiny.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/crisprShiny/)| Shiny interface for CRISPR gRNAs 
|[Rbwa](https://github.com/crisprVerse/Rbwa)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/Rbwa.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/Rbwa/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/Rbwa.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/Rbwa/)|R wrapper for BWA-backtrack and BWA-MEM aligners|
|[ARRmNormalization](https://github.com/Jfortin1/ARRmNormalization)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/ARRmNormalization.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/ARRmNormalization/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/ARRmNormalization.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/ARRmNormalization/)|Normalization for methylation arrays|
|[shinyMethyl](https://github.com/Jfortin1/shinyMethyl)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/shinyMethyl.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/shinyMethyl/)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/shinyMethyl.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/shinyMethyl/)|Interactive visualization for Illumina methylation arrays|

## [Neuroconductor](https://neuroconductor.org) contributions

### As maintainer
