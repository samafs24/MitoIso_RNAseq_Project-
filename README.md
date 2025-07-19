# MitoIso_RNAseq_Project
## Tissue-Specific Isoform Switching and Mitochondrial Targeting in Human Transcriptomes

### Project Structure
```


├── data/                  # Input data (wget/curl links, raw files, processed, temp and metadata files)
├── scripts/               # R and Python analysis scripts
├── results/               # Plots, tables, and final outputs
├── MainQuarto.qmd         # Quarto markdown for full reproducible report
├── README.md              # Project overview (this file)

```

### Objective

This project explores transcript isoform diversity in mitochondrial biology using bulk RNA-seq data, with a focus on tissue-specific regulation and disease relevance.

- Analyse alternative transcript isoforms from the **MitoCarta gene set** using both short- and long-read RNA sequencing data.
  
- Distinguish between **MTS⁺ (mitochondrial-targeted)** and **MTS⁻ (mitochondrial non-targetted)** isoforms to evaluate their localisation potential.
  
- Identify **differential transcript usage (DTU)** across human tissues to reveal tissue-specific regulation of mitochondrial proteins.
  
- Map **transcriptional boundaries in mtDNA** to discover novel start and end sites using long-read RNA-seq data.
  
- Investigate how **isoform switching affects disease susceptibility**, focusing on the inclusion or exclusion of pathogenic variants or disease-associated exons.

- Evaluate how disease-associated variants in peptide sequences affect mitochondrial targeting signals and isoform function.


### Data Sources (wget/curl links are available in ~/data/links/)

- Human MitoCarta3.0 gene set from the Broad Institute
  
- Transcript annotations from GENCODE (v47, GRCh38)
  
- Transcript-level expression data (TPM and counts) from the GTEx project (v10)
  
- Nanopore long-read RNA-seq data from the GTEx project (v9)
  
- Peptide sequences from Ensembl Biomart (Human Genes 113)
  
- ClinVar variants and GWAS Catalog for disease variant annotation

