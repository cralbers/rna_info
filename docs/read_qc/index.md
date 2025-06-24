# QC and getting rid of the crap 

These are the first steps in the analysis of your data- in order to have a quality dataset, there is some post-processing of the reads that get spit out by the sequencing machine that needs to happen to ensure we only use the reads we are confident in. 

To do this, we first run our reads through [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/), a program that assesses the quality of the fastq files based on a variety of parameters. 

