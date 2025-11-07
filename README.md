# ChIP-seq-Analysis-

This repository contains the complete workflow for ChIP-seq analysis of the SEP3 transcription factor in Arabidopsis thaliana using 2-day samples (rep1 & rep2) and their input control from the public dataset BioProject PRJNA203220
.

The aim of this project is to identify SEP3 binding sites, annotate genomic regions, and visualize peak enrichment patterns to understand transcriptional regulation during early flower development.



## ⚙️ Workflow Summary

| Step | Description | Tool |
|------|--------------|------|
| 1️⃣ | Quality Control & Trimming | fastp |
| 2️⃣ | Alignment | Bowtie2 |
| 3️⃣ | Sorting & Indexing | SAMtools |
| 4️⃣ | Peak Calling | MACS2 |
| 5️⃣ | Peak Annotation | ChIPseeker |
| 6️⃣ | Visualization | deepTools, ggplot2 |


## 🧪 Dataset Details

- **Organism:** *Arabidopsis thaliana* (TAIR10)  
- **BioProject:** [PRJNA203220](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA203220)  
- **Samples Used:**  
  - SRR851702  
  - SRR1 
  - SRR1 
- **Read Type:** Single-end  
- **Reference Genome:** TAIR10
