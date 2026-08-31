## Repository Contents

```text
CDV-Sapucaia/
│
├── host_mitochondrial_analises/
│   └── FASTA files containing the alignment of the five mitochondrial genes assembled from 
│       the study specimens and the entire dataset. ML trees generated for each gene and the 
│       tree of concatenated data.
│
├── phylogeny/
│   │
│   ├── ML/
│   │   └── Trimmed alignment in FASTA format, IQ-TREE log file, and resulting tree file.
│   │
│   ├── BEAST/
│   │   └── strict/
│   │       └── BEAST XML files and log files for strict molecular-clock analyses, including  
│   │           traits and general logs. Also includes the combined strict-clock trees and log 
│   │           file used for the TreeAnnotator analysis. 
│   │
│   ├── TreeTime/
│   │   └── Alignment and tree annotated with detected mutations.
│   │
│   └── HyPhy/
│       └── FEL and MEME selection analysis results for the full dataset and selected subtree.
│
├── structural_modelling/
│   └── Fold analysis outputs and FASTA files for the viral and host proteins.
│
├── viralQC/
│   └── Taxonomic classification results in TSV format. The corresponding .tbl files are 
│       available through GenBank.  
│
└── viral_unity/
    └── Krona plots summarizing taxonomic classifications generated using Kraken2 and DIAMOND 
        for samples NP523 and NP27.
```

## Study

This repository provides the datasets and analysis files supporting the genomic, phylogenetic, taxonomic, and structural analyses of CDV detected in *Callithrix penicillata* from Sapucaia, Minas Gerais, Brazil.

## Citation

DOI:
