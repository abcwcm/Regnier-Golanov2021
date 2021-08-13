# Scripts for the analysis of RNA-seq data for Regnier-Golanov et. al (2021)

See the methods file ([Rmd](methods.Rmd) or [PDF](https://github.com/abcwcm/Regnier-Golanov2021/blob/main/methods.pdf)) for a **verbose summary** of the steps we took to process and analyze the bulk RNA-seq data supporting the manuscript by Regnier-Golanov et al. (2021) including motif analysis and exploration of putative regulators.

The [makefile](preprocessing/makefile) in the folder `preprocessing` contains all details about the preprocessing, including read alignment and count matrix generation.
For details of the differential gene expression analysis, see [the Rmd in `deseq2_analysis`](deseq2_analysis/golanov_deseq2.Rmd).

The FASTQ files of the bulk RNA-seq data as well as a spreadsheet with differentially expressed genes can be found on **[GEO](https://www.ncbi.nlm.nih.gov./geo/query/acc.cgi) with accession number GSE167110**

All scripts were written by Paul Zumbo and Friederike Dündar.

Don't hesitate to [get in touch](https://abc.med.cornell.edu/) with questions related to the code.

![](WCM_MB_LOGO_HZSS1L_CLR_RGB.png)
