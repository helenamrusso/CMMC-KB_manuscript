# CMMC-KB Manuscript

This repository contains supplementary code and data processing workflows for the manuscript:

**"Community Curation of Microbial Metabolites Enables Biological Insights of Metabolomics Data"**

Preprint available at:

## Overview

The Collaborative Microbial Metabolite Center knowledgebase (CMMC-KB) is a community-curated platform for annotating microbial metabolites in metabolomics data. This repository provides reproducible workflows demonstrating CMMC-KB applications across diverse biological systems.

## Repository Contents

### Use Cases

Five demonstration use cases showcasing CMMC-KB functionality:

1. **HIV Drug Metabolism** - Investigation of microbial drug transformations across biofluids (stool, plasma, CSF) in people with HIV
   - Datasets: MSV000092833, MSV000094927, MSV000096476

2. **Germ-Free vs. Colonized Mice** - Body distribution of microbial metabolites comparing GF and SPF mice
   - Dataset: MSV000079949

3. **Cyanobacteria in Lake Marathon** - Detection of cyanobacterial metabolites in environmental water samples
   - Dataset: MSV000100269

4. **Leishmania Infection** - Amino acid-conjugated bile acids impacted by parasite infection
   - Dataset: MSV000085991

5. **Coral Symbiont Communities** - Metabolomic profiling of coral-bacteria-zooxanthellae interactions
   - Dataset: MSV000098895

## Key Resources

- **CMMC-KB Portal**: https://cmmc-kb.gnps2.org/
- **CMMC Dashboard**: https://cmmc-dashboard.gnps2.org/
- **Deposition Documentation**: https://cmmc.gnps2.org/deposition_documentation/
- **CMMC Enrichment Documentation**: https://cmmc.gnps2.org/network_enrichment/
- **CMMC-Dashboard Documentation**: https://wang-bioinformatics-lab.github.io/GNPS2_Documentation/metaboapp_CMMC_dashboard/
- **GNPS2 Platform**: https://gnps2.org/

## Workflow

Each use case follows this general pipeline:

1. **Data Processing**: MZmine for feature detection and alignment
2. **Molecular Networking**: Feature-Based Molecular Networking (FBMN) in GNPS2
3. **CMMC Enrichment**: Downstream analysis using CMMC-KB
4. **Visualization**: Cytoscape or CMMC Dashboard for interactive data exploration

## Citation

If you use this resource, please cite:

```
Mannochio-Russo, H., Gonçalves Nunes, W.D., et al. (2025). 
Community Curation of Microbial Metabolites Enables Biological Insights of Metabolomics Data.
bioRxiv, 2026
```
