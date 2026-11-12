# Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination

## Overview

This repository contains the analysis code used in the study:

**Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination (Sadeghdoust et al)**

The study investigates the influence of aging and microglial glycolysis in de- and remylination in the context of Multiple Sclerosis and response to therapeutic targeting.

This repository contains workflows for:

- Bulk RNA sequencing (RNA-seq) with CHCA treatment analysis
- Single-cell RNA sequencing (scRNA-seq) analysis of GSE180759
- Generation of manuscript figures and results

All analyses were performed using R and Quarto.

---

## Repository Structure

```text
.
├── bulkRNAseq_CHCA/
│   ├── bulkRNAseq_CHCA.qmd/
│
├── scRNAseq_MS/
│   ├── scRNAseq_MS.qmd/
│
├── README.md
└── LICENSE
```

## Data Availability

Raw and processed bulk RNA-seq data are available through the Gene Expression Omnibus (GEO, GSM10180842)

Publicly available single-cell RNA-seq data were obtained from GEO (GSE180759)


## Running the Analyses

This repository contains all code used to generate the analyses and figures presented in the manuscript.The analyses are provided as Quarto workflows for bulk RNA-seq analyses (RNAseq_CHCA/RNAseq_CHCA.qmd) and for single-cell RNA-seq analyses (scRNAseq_Ms/scRNAseq_MS.qmd).

The workflows automatically create the necessary local directory structure for downloaded data, intermediate files, and generated outputs. These directories are not maintained within this repository.

To reproduce the results:

1. Download and open the corresponding `.qmd` file.
2. Download specified packages (versions supplied in publication)
3. Execute all code chunks sequentially.
4. Download data files as specified in the file.

## Citation

If you use code from this repository, please cite:

"Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination"

Raw sequencing data: GEO accession #GSM10180842

Repository DOI: 10.5281/zenodo.xxxxxxx


## License

This repository is distributed under the MIT License.

See the LICENSE file for details.


## Contact

Dr. Deepak Kaushik, dkaushik@mun.ca

Kaushik Laboratory

Memorial University of Newfoundland
