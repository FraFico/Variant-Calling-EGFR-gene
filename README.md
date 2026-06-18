# EGFR Project

Bioinformatics analysis of targeted EGFR amplicon sequencing data, with variant calling, coverage analysis, IGV validation, and AI/ML discussion questions on molecular digital twins and graph neural networks.

## Project overview

This project analyzes a targeted sequencing dataset focused on the **EGFR** gene. The workflow includes:

- read structure inspection from FASTQ files
- mapping and coverage analysis on the BAM file
- variant calling with **iVar**
- manual validation in **IGV**
- biological interpretation of the detected variants


## Main results

- The sequencing data showed a **primer + partial amplicon** structure.
- The main target region was mapped to **chromosome 7**, within the **EGFR** locus.
- Coverage analysis revealed **four true EGFR amplicons** and one weak off-target peak.
- Variant calling identified **three candidate EGFR variants**, including a clinically relevant **EGFR exon 19 deletion**.


## Repository contents

- `presentation/` — final PDF report
- `code/` — R code used for the analysis
- `README.md` — project description


## Software used

- R
- ShortRead
- Biostrings
- Rsamtools
- GenomicAlignments
- VariantAnnotation
- GenomicRanges
- IGV
- Galaxy / iVar

## Author

Francesco Fico
