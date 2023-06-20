# KpSC pan-metabolic model

This repository hosts a *Klebsiella pneumoniae* Species Complex pan-metabolic model (*Kp*SC-pan)

KpSC-pan v1 was constructed using the 37 strain-specific *Kp*SC genome-scale metabolic models described in [Hawkey et al, 2022, *Genome Research*](https://www.genome.org/cgi/doi/10.1101/gr.276289.121)

This model was designed as a reference model for input into [Bactabolize](https://github.com/kelwyres/Bactabolize), a pipeline for rapid construction of strain-specific genome scale metabolic models and phenotype prediction.


## Description of files

This repository contains files corresponding to the *Kp*SC-pan metabolic model. As these are not from a single genome, genomic information has been provided in multifasta files (.fna, .faa) instead of a .gbk. [BiGG](http://bigg.ucsd.edu/) nomenclature is used.

| File      | Description |
| ----------- | ----------- |
| KpSC_pan-metabolic_model_v1.xml      | *Kp*SC-pan v1 (.xml)       |
| KpSC_pan-metabolic_model_v1.json   | *Kp*SC-pan v1 (.json)        |
| KpSC_pan-metabolic_model_v1_nucl.fna      | Coding sequences of gene reaction rules (GPRs) from *Kp*SC-pan v1 (.fna)       |
| KpSC_pan-metabolic_model_v1_prots.faa   | Protein sequences of gene reaction rules (GPRs) from *Kp*SC-pan v1 (.faa)        |
| KpSC_pan_metabolic_model_v1_reaction_metadata.tsv | Metadata and external database IDs for the reactions from *Kp*SC-pan v1 (.tsv) | 

## Citation

If you make use of this model, please cite Vezinna et al. Bactabolize: A tool for high-throughput generation of bacterial strain-specific metabolic models *in prep*.


## Contributors

- [Jane Hawkey](https://scholar.google.com/citations?user=4x4aT_oAAAAJ&hl=en&oi=ao)
- [Ben Vezina](https://scholar.google.com/citations?user=Rf9oh94AAAAJ&hl=en&oi=ao)
- [Kelly L. Wyres](https://scholar.google.com/citations?user=anwFM9oAAAAJ&hl=en&oi=sra)
