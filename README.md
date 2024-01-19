# KpSC pan-metabolic model

This repository hosts a *Klebsiella pneumoniae* Species Complex pan-metabolic model (*Kp*SC-pan)

KpSC-pan v2 was constructed using the 507 strain-specific *Kp*SC genome-scale metabolic models described in [Cooper et al, 2023, *bioRxiv*](https://www.biorxiv.org/content/10.1101/2023.12.20.572682v1).

This model was designed as a reference model for input into [Bactabolize](https://github.com/kelwyres/Bactabolize), a pipeline for rapid construction of strain-specific genome scale metabolic models and phenotype prediction.


## Description of files

This repository contains files corresponding to the *Kp*SC-pan metabolic model. As these are not from a single genome, genomic information has been provided in multifasta files (.fna, .faa) instead of a .gbk. [BiGG](http://bigg.ucsd.edu/) nomenclature is used.

| File      | Description |
| ----------- | ----------- |
| KpSC_pan-metabolic_model_v2.xml      | *Kp*SC-pan v2 (.xml)       |
| KpSC_pan-metabolic_model_v2.json   | *Kp*SC-pan v2 (.json)        |
| KpSC_pan-metabolic_model_v2_nucl.fna      | Coding sequences of gene reaction rules (GPRs) from *Kp*SC-pan v2 (.fna)       |
| KpSC_pan-metabolic_model_v2_prots.faa   | Protein sequences of gene reaction rules (GPRs) from *Kp*SC-pan v2 (.faa)        |
| KpSC_pan_metabolic_model_v2_reaction_metadata.tsv | Metadata and external database IDs for the reactions from *Kp*SC-pan v2 (.tsv) | 
| Version-1/ | Directory containing the KpSC-pan v1 model and associated files|

## Citation

If you make use of the KpSC pan metabolic model v2, please cite A validated pangenome-scale metabolic model for the Klebsiella pneumoniae species complex, (2023), bioRxiv, https://doi.org/10.1101/2023.12.20.572682.

If you make use of the previous version (KpSC pan metabolic model v1), please cite Bactabolize: A tool for high-throughput generation of bacterial strain-specific metabolic models, (2023), eLife, https://doi.org/10.7554/eLife.87406.1.


## Contributors

- [Helena B. Cooper](https://scholar.google.com.au/citations?hl=en&user=Ho6svy8AAAAJ)
- [Ben Vezina](https://scholar.google.com/citations?user=Rf9oh94AAAAJ&hl=en&oi=ao)
- [Jane Hawkey](https://scholar.google.com/citations?user=4x4aT_oAAAAJ&hl=en&oi=ao)
- [Kelly L. Wyres](https://scholar.google.com/citations?user=anwFM9oAAAAJ&hl=en&oi=sra)
