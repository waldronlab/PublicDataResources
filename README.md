![.github/workflows/basic_checks.yaml](https://github.com/waldronlab/PublicDataResources/workflows/.github/workflows/basic_checks.yaml/badge.svg)

# Public data resources and Bioconductor

## Instructor names and contact information

* Levi Waldron <levi.waldron at sph.cuny.edu> (City University of New York, New York, NY, USA)
* Benjamin Haibe-Kains <benjamin.haibe.kains at utoronto.ca> (Princess Margaret Cancer Center, Toronto, Canada)
* Sean Davis <sdavis2 at mail.nih.gov> (Center for Cancer Research, National Cancer Institute, National Institutes of Health, Bethesda, MD, USA)

## Syllabus

### Workshop Description 

The goal of this workshop is to introduce Bioconductor packages for finding,
accessing, and using large-scale public data resources including the 
Gene Expression Omnibus [GEO](https://www.ncbi.nlm.nih.gov/geo), Sequence
Read Archive [SRA](https://www.ncbi.nlm.nih.gov/sra), the Genomic Data
Commons [GDC](https://portal.gdc.cancer.gov/), and Bioconductor-hosted 
curated data resources for metagenomics, pharmacogenomics [PharmacoDB](http://pharmacodb.ca/), and The Cancer 
Genome Atlas.

### Pre-requisites

* Basic knowledge of R syntax
* Familiarity with the ExpressionSet and SummarizedExperiment classes
* Basic familiarity with 'omics technologies such as microarray and NGS sequencing

Interested students can prepare by reviewing vignettes of the packages listed in "R/Bioconductor packages used" to gain background on aspects of interest to them.

Some more general background on these resources is published in @Kannan2016-yv.

### Workshop Participation 

Each component will include runnable examples of typical usage that students are encouraged to run during demonstration of that component.

### R/Bioconductor packages used

* `r BiocStyle::Biocpkg("GEOquery")`: Access to the NCBI Gene Expression Omnibus (GEO), a public repository of gene expression (primarily microarray) data.
* `r BiocStyle::Biocpkg("GenomicDataCommons")`: Access to the NIH / NCI Genomic Data Commons RESTful service.
* `r BiocStyle::Githubpkg("seandavi/SRAdbV2")`: A compilation of metadata from the NCBI Sequence Read Archive, the largest public repository of sequencing data from the next generation of sequencing platforms, and tools
* `r BiocStyle::Biocpkg("curatedTCGAData")`: Curated data from The Cancer Genome Atlas (TCGA) as MultiAssayExperiment Objects
* `r BiocStyle::Biocpkg("curatedMetagenomicData")`: Curated metagenomic data of the human microbiome
* `r BiocStyle::Biocpkg("HMP16SData")`: Curated metagenomic data of the human microbiome
* `r BiocStyle::Biocpkg("PharmacoGx")`: Curated large-scale preclinical pharmacogenomic data and basic analysis tools


### Time outline

This is a 1h45m workshop.

| Activity                            | Time    |
|-------------------------------------|---------|
| Overview | 10m |
| GEOquery | 15m |
| GenomicDataCommons | 20m |
| Sequence Read Archive | 20m |
| curatedTCGAData   | 10m |
| curatedMetagenomicData and HMP16SData | 15m |
| PharmacoGx | 20m |

### Workshop goals and objectives

Bioconductor provides access to significant amounts of publicly available 
experimental  data. This workshop introduces students to Bioconductor
interfaces to the NCBI's Gene Expression Omnibus, Genomic Data Commons,
Sequence Read Archive and PharmacoDB. It additionally introduces curated resources 
providing The Cancer Genome Atlas, the Human Microbiome Project and other 
microbiome studies, and major pharmacogenomic studies, as native Bioconductor
objects ready for analysis and comparison to in-house datasets.

### Learning goals

* search NCBI resources for publicly available 'omics data
* quickly use data from the TCGA and the Human Microbiome Project

### Learning objectives

* find and download processed microarray and RNA-seq datasets from the Gene Expression Omnibus
* find and download 'omics data from the Genomic Data Commons and Sequence Read Archive
* download and manipulate data from The Cancer Genome Atlas and Human Microbiome Project
* download and explore pharmacogenomics data
