# 16S Processing with dada2

## Theory
This is a basic protocol for 16S sequencing processing from raw files to ASV tables. This is for beginning/new lab members to familiarize with the 16S bioinformatics pipeline. This pipeline is only applicable to 16S sequencing data. This protocol includes mostly code and is designed as a reference and not a stand-alone tutorial.

## Before Start

1. Register for a ROAR account under Erika's allocation: https://www.icds.psu.edu/computing-services/account-setup/
2. Login to ROAR and set up your terminal environment with the BioStar Handbook Instructions: 
3. Set up a conda environment for R following instructions in /gpfs/group/evk5387/default/scripts/r-in-conda.txt  
*this script will start an R session and download R packages that are necessary in this pipeline*

❗**As you work through this pipeline, copy each script into your own directory. DO NOT CHANGE THE ORIGINAL SCRIPTS.❗

## Procedure

### Inspect the raw fastq files

1. Activate the bioinfo conda environment  
``` conda activate bioinfo ```
2. Open a fastq file and inspect the first 20 lines  
``` head FILE.fastq ```
