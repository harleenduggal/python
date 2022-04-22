# python


## Ex 1: Write a script to correctly format organism scientific names (eg Homo sapiens).
•	It should interactively ask for the Genus (eg homo) and Species (eg sapiens)
•	It should then print out the name with the Genus with an uppercase initial letter and the species all in lowercase.
•	Look at the methods in the str package for how to make these transformations.
## Your code ##

 

## Ex 2: You have been given some files with embedded sample names (for purpose for exercise, save them in a list)
lane1_NoCode_L001_R1.fastq.gz 
lane1_NoIndex_L001_R1.fastq.gz
lane1_NoIndex_L001_R2.fastq.gz
pipeline_processing_output.log
lane7127_ACTGAT_JH25_L001_R1.fastq.gz
lane7127_ACTTGA_E30_1_2_Hap4_24h_L001_R1.fastq.gz
lane7127_AGTTCC_JH14_L001_R1.fastq.gz
lane7127_CGGAAT_JH37_L001_R1.fastq.gz
lane7127_GCCAAT_E30_1_2l_Hap4_log_L001_R1.fastq.gz
lane7127_GGCTAC_E30_1_4_Hap4_48h_L001_R1.fastq.gz
We want to extract the sample name from these files.  The structure is:
1.	Written lane number
2.	Barcode
3.	Sample name
4.	Numeric lane number (starting with L)
5.	Read number (R1/2/3/4)
6.	File suffix (always .fastq.gz)
So, for lane7127_GCCAAT_E30_1_2l_Hap4_log_L001_R1.fastq.gz the sample name would be: E30_1_2l_Hap4_log


 
Extract the sample names from the file names, ignoring any files which do not match the expected pattern.
## Your code ##
## Ex 3: Take DNA FASTA file as input and return Accession number, Organism/Origin, Base count, Sequence length, GC content, AT content and whether the sequence is GC rich or AT rich. You can refer to Homo sapiens isolate 44 BRCA1 (BRCA1) gene, partial cds - Nucleotide - NCBI (nih.gov) to work as an example.
## Your code ##
  
 https://colab.research.google.com/drive/1juZcTEydSGtiudlC6oalNA6h2taUGHEj?usp=sharing


