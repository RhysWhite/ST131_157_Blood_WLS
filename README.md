# Genomic epidemiology reveals geographical clustering of multi-drug-resistant *Escherichia coli* sequence type (ST)131 associated with bacteraemia in Wales, United Kingdom
This repository provides *de novo* assemblies of paired-end short-read sequencing data for our phylogenomic study of *E. coli* sequence type (ST)131 in an accessible format. If you use this data in your publications please cite:

```
White RT, Bull MJ, Barker CR, Arnott JM, Wootton M, Jones LS, Howe RA, Morgan M, Ashcroft MM,
Forde BM, Connor TR^, Beatson SA^. Genomic epidemiology reveals geographical clustering of 
multidrug-resistant Escherichia coli sequence type (ST)131 associated with bacteraemia in 
Wales, United Kingdom. medRxiv:21257487v1 [Preprint]. 2021. Available from: 
https://www.medrxiv.org/content/10.1101/2021.05.21.21257487v1 doi: 10.1101/2021.05.21.21257487

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

| Strain | BioSample accession | SRA Accession |
| :---         |          ---: |          ---: | 
| BA16 | SAMN19110938 | SRR14519463 | 
| BA42 | SAMN19110990 | SRR14519440 | 
| BA43 | SAMN19110991 | SRR14519439 | 
| BA44 | SAMN19110995 | SRR14519435 | 
| BA47 | SAMN19111001 | SRR14519428 | 
| BA68 | SAMN19111013 | SRR14519415 | 
| BA70 | SAMN19111015 | SRR14519414 | 
| BA108 | SAMN19110868 | SRR14519482 | 
| BA115 | SAMN19110873 | SRR14519481 | 
| BA116 | SAMN19110874 | SRR14519480 | 
| BA130 | SAMN19110889 | SRR14519479 | 
| BA133 | SAMN19110892 | SRR14519478 | 
| BA155 | SAMN19110928 | SRR14519506 | 
| BA156 | SAMN19110930 | SRR14519504 | 
| BA164 | SAMN19110941 | SRR14519460 | 
| BA166 | SAMN19110942 | SRR14519459 | 
| BA167 | SAMN19110943 | SRR14519458 | 
| BA176 | SAMN19110945 | SRR14519456 | 
| BA177 | SAMN19110946 | SRR14519455 | 
| BA178 | SAMN19110947 | SRR14519454 | 
| BA187 | SAMN19110949 | SRR14519451 | 
| BA203 | SAMN19110951 | SRR14519449 | 
| BA210 | SAMN19110967 | SRR14519555 | 
| BA264 | SAMN19110976 | SRR14519545 | 
| BA306 | SAMN19110977 | SRR14519544 | 
| BA307 | SAMN19110978 | SRR14519542 | 
| BA337 | SAMN19110979 | SRR14519541 | 
| BA352 | SAMN19110980 | SRR14519540 | 
| BA377 | SAMN19110981 | SRR14519539 | 
| BA389 | SAMN19110982 | SRR14519538 | 
| BA392 | SAMN19110983 | SRR14519537 | 
| BA394 | SAMN19110984 | SRR14519536 | 
| BA397 | SAMN19110985 | SRR14519535 | 
| BA408 | SAMN19110986 | SRR14519534 | 
| BA412 | SAMN19110987 | SRR14519533 | 
| BA417 | SAMN19110988 | SRR14519442 | 
| BA418 | SAMN19110989 | SRR14519441 | 
| BA434 | SAMN19110992 | SRR14519438 | 
| BA435 | SAMN19110993 | SRR14519437 | 
| BA437 | SAMN19110994 | SRR14519436 | 
| BA440 | SAMN19110996 | SRR14519434 | 
| BA445 | SAMN19110997 | SRR14519433 | 
| BA446 | SAMN19110998 | SRR14519431 | 
| BA461 | SAMN19110999 | SRR14519430 | 
| BA464 | SAMN19111000 | SRR14519429 | 
| BA487 | SAMN19111002 | SRR14519427 | 
| BA490 | SAMN19111003 | SRR14519426 | 
| BA494 | SAMN19111004 | SRR14519425 | 
| BA496 | SAMN19111005 | SRR14519424 | 
| BA497 | SAMN19111006 | SRR14519423 | 
| BA515 | SAMN19111007 | SRR14519422 | 
| BA517 | SAMN19111008 | SRR14519420 | 
| BA523 | SAMN19111009 | SRR14519419 | 
| BA575 | SAMN19111010 | SRR14519418 | 
| BA655 | SAMN19111011 | SRR14519417 | 
| BA669 | SAMN19111012 | SRR14519416 | 
| BA694 | SAMN19111014 | SRR14519493 | 
| BA730 | SAMN19111016 | SRR14519492 | 
| BA810 | SAMN19111017 | SRR14519491 | 
| BA829 | SAMN19111018 | SRR14519490 | 
| BA871 | SAMN19111019 | SRR14519489 | 
| BA876 | SAMN19111020 | SRR14519488 | 
| BA901 | SAMN19111021 | SRR14519486 | 
| BA909 | SAMN19111022 | SRR14519485 | 
| BA910 | SAMN19111023 | SRR14519484 | 
| BA942 | SAMN19111024 | SRR14519483 | 
| BA1110 | SAMN19110869 | SRR14519567 | 
| BA1112 | SAMN19110870 | SRR14519566 | 
| BA1123 | SAMN19110871 | SRR14519498 | 
| BA1128 | SAMN19110872 | SRR14519487 | 
| BA1165 | SAMN19110875 | SRR14519476 | 
| BA1170 | SAMN19110876 | SRR14519529 | 
| BA1214 | SAMN19110877 | SRR14519518 | 
| BA1215 | SAMN19110878 | SRR14519507 | 
| BA1243 | SAMN19110879 | SRR14519464 | 
| BA1256 | SAMN19110880 | SRR14519453 | 
| BA1257 | SAMN19110881 | SRR14519565 | 
| BA1274 | SAMN19110882 | SRR14519554 | 
| BA1275 | SAMN19110883 | SRR14519543 | 
| BA1279 | SAMN19110884 | SRR14519532 | 
| BA1287 | SAMN19110885 | SRR14519432 | 
| BA1292 | SAMN19110886 | SRR14519421 | 
| BA1293 | SAMN19110887 | SRR14519413 | 
| BA1295 | SAMN19110888 | SRR14519412 | 
| BA1320 | SAMN19110890 | SRR14519411 | 
| BA1327 | SAMN19110891 | SRR14519499 | 
| BA1341 | SAMN19110893 | SRR14519497 | 
| BA1344 | SAMN19110894 | SRR14519496 | 
| BA1345 | SAMN19110895 | SRR14519495 | 
| BA1347 | SAMN19110896 | SRR14519494 | 
| BA1353 | SAMN19110897 | SRR14519477 | 
| BA1355 | SAMN19110898 | SRR14519475 | 
| BA1368 | SAMN19110899 | SRR14519474 | 
| BA1387 | SAMN19110900 | SRR14519473 | 
| BA1390 | SAMN19110901 | SRR14519472 | 
| BA1391 | SAMN19110902 | SRR14519471 | 
| BA1393 | SAMN19110903 | SRR14519470 | 
| BA1397 | SAMN19110904 | SRR14519469 | 
| BA1404 | SAMN19110905 | SRR14519468 | 
| BA1408 | SAMN19110906 | SRR14519531 | 
| BA1413 | SAMN19110907 | SRR14519530 | 
| BA1418 | SAMN19110908 | SRR14519528 | 
| BA1422 | SAMN19110909 | SRR14519527 | 
| BA1431 | SAMN19110910 | SRR14519526 | 
| BA1435 | SAMN19110911 | SRR14519525 | 
| BA1441 | SAMN19110912 | SRR14519524 | 
| BA1442 | SAMN19110913 | SRR14519523 | 
| BA1446 | SAMN19110914 | SRR14519522 | 
| BA1447 | SAMN19110915 | SRR14519521 | 
| BA1458 | SAMN19110916 | SRR14519520 | 
| BA1477 | SAMN19110917 | SRR14519519 | 
| BA1482 | SAMN19110918 | SRR14519517 | 
| BA1490 | SAMN19110919 | SRR14519516 | 
| BA1496 | SAMN19110920 | SRR14519515 | 
| BA1507 | SAMN19110921 | SRR14519514 | 
| BA1509 | SAMN19110922 | SRR14519513 | 
| BA1511 | SAMN19110923 | SRR14519512 | 
| BA1512 | SAMN19110924 | SRR14519511 | 
| BA1517 | SAMN19110925 | SRR14519510 | 
| BA1542 | SAMN19110926 | SRR14519509 | 
| BA1543 | SAMN19110927 | SRR14519508 | 
| BA1553 | SAMN19110929 | SRR14519505 | 
| BA1561 | SAMN19110931 | SRR14519503 | 
| BA1570 | SAMN19110932 | SRR14519502 | 
| BA1575 | SAMN19110933 | SRR14519501 | 
| BA1581 | SAMN19110934 | SRR14519500 | 
| BA1585 | SAMN19110935 | SRR14519467 | 
| BA1588 | SAMN19110936 | SRR14519466 | 
| BA1593 | SAMN19110937 | SRR14519465 | 
| BA1606 | SAMN19110939 | SRR14519462 | 
| BA1637 | SAMN19110940 | SRR14519461 | 
| BA1688 | SAMN19110944 | SRR14519457 | 
| BA1843 | SAMN19110948 | SRR14519452 | 
| BA2000 | SAMN19110950 | SRR14519450 | 
| BA2055 | SAMN19110952 | SRR14519448 | 
| BA2056 | SAMN19110953 | SRR14519447 | 
| BA2057 | SAMN19110954 | SRR14519446 | 
| BA2065 | SAMN19110955 | SRR14519445 | 
| BA2075 | SAMN19110956 | SRR14519444 | 
| BA2078 | SAMN19110957 | SRR14519443 | 
| BA2079 | SAMN19110958 | SRR14519564 | 
| BA2080 | SAMN19110959 | SRR14519563 | 
| BA2081 | SAMN19110960 | SRR14519562 | 
| BA2082 | SAMN19110961 | SRR14519561 | 
| BA2088 | SAMN19110962 | SRR14519560 | 
| BA2090 | SAMN19110963 | SRR14519559 | 
| BA2091 | SAMN19110964 | SRR14519558 | 
| BA2097 | SAMN19110965 | SRR14519557 | 
| BA2098 | SAMN19110966 | SRR14519556 | 
| BA2102 | SAMN19110968 | SRR14519553 | 
| BA2105 | SAMN19110969 | SRR14519552 | 
| BA2112 | SAMN19110970 | SRR14519551 | 
| BA2113 | SAMN19110971 | SRR14519550 | 
| BA2121 | SAMN19110972 | SRR14519549 | 
| BA2123 | SAMN19110973 | SRR14519548 | 
| BA2133 | SAMN19110974 | SRR14519547 | 
| BA2134 | SAMN19110975 | SRR14519546 | ![image](https://user-images.githubusercontent.com/28285670/119422409-5667c880-bd44-11eb-8be3-7d8121109c3d.png)


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
