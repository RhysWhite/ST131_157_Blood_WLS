# Genomic epidemiology reveals geographical clustering of multi-drug-resistant *Escherichia coli* sequence type (ST)131 associated with bacteraemia in Wales, United Kingdom
This repository provides *de novo* assemblies of paired-end short-read sequencing data for our phylogenomic study of *E. coli* sequence type (ST)131 in an accessible format. If you use this data in your publications please cite:

```
White RT, Bull MJ, Barker CR, Arnott JM, Wootton M, Jones LS, Howe RA, Morgan M, Ashcroft MM,
Forde BM, Connor TR^, Beatson SA^. Genomic epidemiology reveals geographical clustering of 
multidrug-resistant Escherichia coli sequence type (ST)131 associated with bacteraemia in 
Wales, United Kingdom. medRxiv:12073907v2 [Preprint]. 2021. Available from: <Publication>

^CORRESPONDING AUTHORS
```

The Illumina sequence read data have been submitted to the National Center for Biotechnology Information (NCBI) sequence read archive (SRA) under Bioproject number [PRJNA729115](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA729115) (157 paired reads).

## Manifest
Contains:
- Assemblies/ - the assembled contigs from Velvet that have been ordered against *E. coli* ST131 strain EC958 (GenBank: [HG941718.1](https://www.ncbi.nlm.nih.gov/nuccore/HG941718.1)) described by [Forde *et al.* (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4134206/).
  - Contigs from the draft assemblies were ordered against the complete chromosome of EC958 using [Mauve](http://darlinglab.org/mauve/mauve.html) by [Darling, *et al*. (2004)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC442156/).
- The assembly statistics are provided.

## Matching the SRA accession to strain identifier

The following table facilitates this:


## Getting the data
Note: The data is ~825 MB

**Option 1) Download the current release as an archive:**
```
$ wget https://github.com/RhysWhite/ST131_157_Blood_WLS/archive/master.zip -O ST131_157_Blood_WLS_v1.tar.gz
$ unzip ST131_157_Blood_WLS_v1.tar.gz
```

**Option 2) Clone the current master branch in this repository:**

Please ensure you have git installed. git can be really useful for scientists. See [here](http://blogs.biomedcentral.com/bmcblog/2013/02/28/version-control-for-scientific-research/) for some discussion.

With git:

```
$ git clone --recursive https://github.com/RhysWhite/ST131_157_Blood_WLS.git 
# The --recursive option is used to pull down all the smaller repositories
```
