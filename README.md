# Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination

## Overview

This repository contains the analysis code used in the study:

**Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination (Sadeghdoust et al)**

The study investigates the influence of aging and microglial glycolysis in de- remylination in the context of Multiple Sclerosis and response to therapeutic targeting.

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
├── scRNAseq_GSE180759/
│   ├── scRNAseq_GSE180759.qmd/
│
├── README.md
├── LICENSE
└── sessionInfo.txt
```

### Workflow Descriptions

#### RNAseq_CHCA

Bulk RNA-seq workflow used for differential expression analysis, pathway analysis, and figure generation.

#### scRNAseq

Single-cell RNA-seq workflow based on GEO dataset GSE180759 used for data processing, integration, clustering, annotation, targeted microglial gene expression analysis, pathway analysis, and figure generation.

## Data Availability

### Bulk RNA-seq

Raw and processed bulk RNA-seq data are available through:

**GEO accession:** GSE________

### Single-cell RNA-seq

Publicly available single-cell RNA-seq data were obtained from:

**GEO accession:** GSE180759

## Running the Analyses

This repository contains all code used to generate the analyses and figures presented in the manuscript.The analyses are provided as Quarto workflows.

```text
RNAseq_CHCA/RNAseq_CHCA.qmd
```

for bulk RNA-seq analyses, and

```text
scRNAseq/scRNAseq_GSE180759.qmd
```

for single-cell RNA-seq analyses.

The workflows automatically create the necessary local directory structure for downloaded data, intermediate files, and generated outputs. These directories are not maintained within this repository.

To reproduce the results:

1. Obtain the sequencing data from the accession numbers listed above.
2. Download and open the corresponding `.qmd` file.
3. Update file paths if required.
4. Execute all code chunks sequentially.



## Software Requirements

Analyses were performed using:

- R (version ________)
- Quarto (version ________)

Package versions are recorded in:

```text
sessionInfo.txt
```



## Citation

If you use code from this repository, please cite:

"Therapeutic relevance of targeting microglia glycolysis in an aging model of de- and remyelination"

DOI: [DOI]

Raw sequencing data: GEO accession: GSEXXXXX

Reproducible environment: renv::restore()

Repository DOI: 10.5281/zenodo.xxxxxxx


## License

This repository is distributed under the MIT License.

See the LICENSE file for details.

## Contact

Dr. Deepak Kaushik, dkaushik@mun.ca

Kaushik Laboratory

Memorial University of Newfoundland
