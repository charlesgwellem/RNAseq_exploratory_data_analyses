# Project title: Explorytory data analysis on RNA sequencing data.

# Description
I am a Bioinformatician/Data Scientist by profession and I am a data enthusiast. I have already analysed several RNAseq datasets. I believe in skill-sharpening and professional development via constant self-teaching. 
In this project I perform an end-to-end analysis of public data related to RNAseq data, some of which are provides in Bioconductor packages. 

My goal in this project is to learn and familiarise myself more deeply with various tools and approaches used in the analysis of RNAseq data and have a better understanding why certain approaches are chosen 
by the bioinformaticians as standards. I also want to set myself to develop or contribute to the development of my own methods in future.

I have neither developed any of the tools nor approaches used in this project. I am greatly inspired, supported and guided by material and ideas from https://github.com/genomicsclass. 
I am very grateful for the EDX platform and Prof. Rafael Irizarry  for their very high quality MOOC on the topics covered. 

I am still adding content to this repository and I am actively following the functional genomics case studies classes by Prof. Rafael Irizarry, provided on 
[EDX](https://learning.edx.org/course/course-v1:HarvardX+PH525.6x+2T2022/home). In this particular topic on exploratory data analysis of RNAseq, I have acquired atomic-size understanding of the following topics:
- Transcriptome alignment assessment by making a histogram of the FPKM(fragments per kilobase of sequence per million mapped reads) and other metrics
- Normalisation of gene counts for sequencing depth by using `log2` and `rlog`,
- Principal components analysis and hierarchical clustering of counts after normalisation.
  
# Packages
The packages I use are mainly Bioconductor as well as CRAN packages. Details can be found in the html files of the report folder in the repository. In addition to the 
commonly used packages used for basic visualisation and statistics, the most important packages I have used so far are:
- DESeq2 used for normalisation and differential analysis of count data.
- airway public dataset published by [Himes, E. B et al](http://www.ncbi.nlm.nih.gov/pubmed/24926665)
- Rsamtools provides an interface to the samtools, bcftools, and tabix utilities for manipulating SAM (Sequence Alignment / Map), FASTA, binary variant call (BCF) and compressed indexed tab-delimited (tabix) files.
- GenomicAlignments provides efficient containers for storing and manipulating short genomic alignments (typically obtained by aligning short reads to a reference genome)
- Rsubread for alignment, quantification and analysis of RNA sequencing data (including both bulk RNA-seq and scRNA-seq) and DNA sequenicng data (including ATAC-seq, ChIP-seq, WGS, WES etc).

# Credits
I am very grateful for the following platforms and indivisuals who have made very high quality Bioinformatics content available online and mostly for free.
- EDX
- Prof. Rafael Irizarry and Co. 
