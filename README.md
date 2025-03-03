# **Comprehensive Sequence Analysis of the Human TNF Gene**

## 1. **Project Overview**

This project aims to analyze the sequence of the human TNF (Tumor Necrosis Factor) gene using using various bioinformatics tools such as NCBI, BioEdit, PROMO, MEME Suite, and GENSCAN. This project involves downloading the sequence, translating it, finding ORFs, analyzing sequence composition, identifying transcription factor binding sites, searching for functional motifs, predicting coding/non-coding regions, and converting sequence file formats. 


## 2. **GitHub repository folders**

* Data \- contains the FASTA sequence of the human TNF gene. 
* Images \- contains the images of results generated from the sequence analysis.
* Outputs \- contains the results generated from the analysis. 


## 3. **Methodology**

### **Task 1: Download the human TNF gene sequence** 
* Search for 'human TNF gene' in [NCBI](https://www.ncbi.nlm.nih.gov/).
* Locate the correct sequence record (e.g., 'Homo sapiens TNF')
* Download the sequence in FASTA format.
* Open the sequence in BioEdit and view it.

### **Task 2: Translate the DNA Sequence of the TNF gene into Amino Acids** 
* Open the downloaded TNF gene sequence in [BioEdit](https://bioedit.software.informer.com/download/).
* Use the 'Translate' feature in BioEdit to generate the amino acid sequence.

### **Task 3: Identify the ORFs (Open Reading Frames) within the TNF gene sequence** 
* Use BioEdit's ORF Finder tool to find ORFs in the TNF gene sequence.
* Record the start and stop positions, lengths, and protein translations of the ORFs.

### **Task 4: Analyze the Nucleotode Composition of the TNF gene sequence** 
* Use BioEdit to analyze the sequence composition of the TNF gene.
* Calculate the frequencies of each nucleotide and the overall GC content.

### **Task 5: Identify Transcription Factor Binding Sites in the TNF gene promoter region** 
* Access the [PROMO tool](http://alggen.lsi.upc.es/cgi-bin/promo_v3/promo/promoinit.cgi?dirDB=TF_8.3) and select 'Homo sapiens' as the species.
* Input the promoter region of the TNF gene or use the entire gene sequence.
* Identify potential transcription factor binding sites.

### **Task 6: Search for Functional Motifs in the TNF gene sequence** 
* Access the [MEME Suite](https://meme-suite.org/meme/tools/meme) and upload the TNF gene sequence in FASTA format.
* Use the default settings to search for motifs.

### **Task 7: Predict the Coding and Non-Coding Regions within the TNF gene sequence** 
* Access the [GENSCAN tool](http://hollywood.mit.edu/GENSCAN.html) or run it locally if installed.
* Input the TNF gene sequence in the appropriate format.
* Run the analysis to predict coding and non-coding regions.

### **Task 8: Convert the TNF gene sequence from FASTA file format to PHYLIP format** 
* Open the TNF gene sequence in BioEdit 
* Use the 'Save As...' feature to convert the file to PHYLIP format.
* Verify the conversion by opening the PHYLIP file in a text editor.

