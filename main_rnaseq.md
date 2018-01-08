---
layout: workshop_main_3day
permalink: /rnaseq_2018
title: RNA-Seq
header1: Workshop Pages for Students
header2: Informatics for RNA-Seq Analysis
image: /site_images/CBW_RNA_seq_icon.jpg
---
# Welcome <a id="welcome"></a>

Welcome to Informatics for RNA-Seq Analysis 2018.  

## Read these before coming to the workshop:

* [Informatics for RNA Sequencing: A Web Resource for Analysis on the Cloud](https://www.ncbi.nlm.nih.gov/pubmed/26248053)  

* [Integrative Genomics Viewer (IGV): high-performance genomics data visualization and exploration](http://www.ncbi.nlm.nih.gov/pubmed/22517427)

* [Transcript-level expression analysis of RNA-seq experiments with HISAT, StringTie and Ballgown](https://www.ncbi.nlm.nih.gov/pubmed/27560171)
  
* [ENCODE RNA-Seq Standards](https://genome.ucsc.edu/ENCODE/protocols/dataStandards/ENCODE_RNAseq_Standards_V1.0.pdf)
  
* [Methods to study splicing from high-throughput RNA sequencing data](http://www.ncbi.nlm.nih.gov/pubmed/24549677)  
  
* [A comprehensive assessment of RNA-seq accuracy, reproducibility and information content by the Sequencing Quality Control Consortium](http://www.ncbi.nlm.nih.gov/pubmed/25150838)

* [De novo transcript sequence reconstruction from RNA-seq using the Trinity platform for reference generation and analysis](http://www.nature.com/nprot/journal/v8/n8/full/nprot.2013.084.html)

## Optional readings:

* [HISAT: a fast spliced aligner with low memory requirements](https://www.ncbi.nlm.nih.gov/pubmed/25751142)  

* [StringTie enables improved reconstruction of a transcriptome from RNA-seq reads](https://www.ncbi.nlm.nih.gov/pubmed/25690850)  

* [Ballgown bridges the gap between transcriptome assembly and expression analysis](https://www.ncbi.nlm.nih.gov/pubmed/25748911)  

* [HTSeq--a Python framework to work with high-throughput sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/25260700)  

* [edgeR: a Bioconductor package for differential expression analysis of digital gene expression data](https://www.ncbi.nlm.nih.gov/pubmed/19910308)  

* [Full-length transcriptome assembly from RNA-Seq data without a reference genome](http://www.nature.com/nbt/journal/v29/n7/abs/nbt.1883.html)  

## Do these before coming to the workshop:

1) **R Preparation tutorials**: You are expected to be familiar with **R** before the workshop. If you are unfamiliar with **R**, here are some suggested tutorials:  

* The [CBW R tutorial](http://bioinformatics-ca.github.io/CBW_R_Tutorial/) or [R Tutorial](http://www.cyclismo.org/tutorial/R/) 
* The [R command cheat sheet](https://github.com/bioinformaticsdotca/bioinformaticsdotca.github.io/blob/master/resources/R_Short-refcard.pdf)
* [R Plotting Reference](https://github.com/bioinformatics-ca/bioinformatics-ca.github.io/blob/master/resources/Plotting.Reference.ipynb)

2) **UNIX Preparation tutorials**: You are expected to be familiar with basic command line usage before the workshop. If you are unfamiliar with **the command line**, here are some suggested tutorials:   

* [UNIX Bootcamp](https://github.com/griffithlab/rnaseq_tutorial/wiki/Unix-Bootcamp)
* [UNIX Bootcamp alternative](http://rik.smith-unna.com/command_line_bootcamp/?id=9xnbkx6eaof) 
* [Unix Cheat sheet](http://www.rain.org/~mkummel/unix.html) 

3) [Sequencing Terminology](http://www.ncbi.nlm.nih.gov/projects/genome/glossary.shtml)

## Install these before coming to the workshop:

1) A robust text editor.   

* For Windows/PC - [notepad++](http://notepad-plus-plus.org/)  
* For Linux - [gEdit](http://projects.gnome.org/gedit/)  
* For Mac – [TextWrangler](http://www.barebones.com/products/textwrangler/download.html)

2) A file decompression tool.  

* For Windows/PC – [7zip](http://www.7-zip.org/).  
* For Linux – [gzip](http://www.gzip.org).   
* For Mac – already there.

3) A robust internet browser such as Firefox or Safari (Internet Explorer and Chrome are not recommended because of Java issues).

4) Java -The visualization program that we will be using (IGV) requires Java. Check if you have Java installed: https://www.java.com/verify/ and download Java if you do not have it installed (Java 8).

5) Integrative Genomics Viewer 2.3 (IGV) - Once java is installed, go to http://www.broadinstitute.org/igv/ and register in order to get access to the downloads page. Once you have gained access to the download page, click on the appropriate launch button that matches the amount of memory available on your laptop (if you have space, 1.2GB is good, more is better).   

**Note** Chrome does not launch "java webstart" files by default. Instead, the launch buttons below will download a "jnlp" file. This should appear in the lower left corner of the browser. Double-click the downloaded file to run.   

**Windows users:** To run with more than 1.2 GB you must install 64-bit Java. This is often not installed by default even with the latest Windows 7 machines with many GB of memory. In general trying to launch with more memory than your OS/Java combination supports will result in the obscure error "could not create virtual machine".

6) SSH client - Mac and Linux users already have a command line ssh program that can be run from the terminal. For Windows users, please download [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html).  

7) SCP/SFTP client - We will be moving data from the servers to the student laptops for visualization. Mac and Linux users already have a command line scp and sftp program. For Windows users, please install [WinSCP](http://winscp.net/eng/download.php).

8) A PDF viewer (Adobe Acrobat or equivalent).  

## Additional Optional Resources 

Additional resources can be found on the [RNA-Seq wiki](https://github.com/griffithlab/rnaseq_tutorial/wiki/Resources).

Please note that these instructions may change before the workshop.  
