# iMAP Project Overview

This repository serves as the central entry point for the **iMAP (Integrated Microbiome Analysis Pipeline)**, a modular microbiome analysis framework published in *BMC Bioinformatics* (2019).

Following publication, the original iMAP workflow was decomposed into step-based repositories to improve clarity, reproducibility, and reuse. Each repository corresponds to a distinct stage of the microbiome analysis lifecycle, from data acquisition and processing to exploration, statistical analysis, and
downstream modeling.

**Start here** if you want to understand how the full iMAP pipeline fits together.

For readers primarily interested in **result interpretation and visualization**, the core downstream components are:
- **PART 08 – Exploratory Analysis:** visualization and exploratory reasoning on processed microbiome data
- **PART 09 – Statistical Analysis:** statistical testing and inference on microbiome features

This overview repository provides the routing structure that connects all iMAP components and links each stage to its corresponding documentation.

## Repositories Overview

Below is a summary of the ten repositories comprising the iMAP project. Each repository represents a distinct stage of the workflow; some components are more complete than others, but all are included to document the full analytical structure of the pipeline.

| Repository | Description | Documentation Link |
|------------|-------------|---------------------|
| [PART 01](https://github.com/tmbuza/imap-essential-software/) | Software requirement for microbiome data analysis with Snakemake workflows | [Documentation](https://tmbuza.github.io/imap-essential-software/) |
| [PART 02](https://github.com/tmbuza/imap-sample-metadata/) | Downloading and exploring microbiome sample metadata from SRA Database | [Documentation](https://tmbuza.github.io/imap-sample-metadata/) |
| [PART 03](https://github.com/tmbuza/imap-download-sra-reads/) | Downloading and filtering microbiome sequencing data from SRA database | [Documentation](https://tmbuza.github.io/imap-download-sra-reads/) |
| [PART 04](https://github.com/tmbuza/imap-read-quality-control/) | Quality Control of Microbiome Next Generation Sequencing Reads | [Documentation](https://tmbuza.github.io/imap-read-quality-control/) |
| [PART 05](https://github.com/tmbuza/imap-bioinformatics-mothur/) | Microbial profiling using MOTHUR and Snakemake workflows | [Documentation](https://tmbuza.github.io/imap-mothur-bioinformatics/) |
| [PART 06](https://github.com/tmbuza/imap-bioinformatics-qiime2/) | Microbial profiling using QIIME2 and Snakemake workflows | [Documentation](https://tmbuza.github.io/imap-qiime2-bioinformatics/) |
| [PART 07](https://github.com/tmbuza/imap-data-processing/) | Processing Output from 16S-Based microbiome bioinformatics pipelines | [Documentation](https://tmbuza.github.io/imap-data-preparation/) |
| [PART 08](https://github.com/tmbuza/imap-exploratory-analysis/) | Exploratory Analysis of 16S-Based Microbiome Processed Data | [Documentation](https://tmbuza.github.io/imap-data-exploration/) |
| [PART 09](https://github.com/tmbuza/imap-statistical-analysis/) | Statistical analysis of processed 16S-based microbiome data | [Documentation](https://tmbuza.github.io/imap-statistical-analysis/) |
| [PART 10](https://github.com/tmbuza/imap-machine-learning/) | Machine learning analysis of processed 16S-based microbiome data | [Documentation](https://tmbuza.github.io/imap-machine-learning/) |

## Getting Started

To explore the iMAP project in more detail, simply click on the provided links for each repository. Whether you're new to microbiome analysis or a seasoned researcher, the iMAP project offers valuable resources and tools to enhance your microbiome data analysis workflows.

We hope you find the iMAP project helpful and informative. Happy analyzing!


## Session information

For a detailed overview of the tools and versions suitable for this guide, explore the [session information](session_info.txt).

## Citation
> Please consider citing the [iMAP article](https://rdcu.be/b5iVj) if you find any part of the iMAP practical user guides helpful in your microbiome data analysis.

Buza, T. M., Tonui, T., Stomeo, F., Tiambo, C., Katani, R., Schilling, M., … Kapur, V. (2019). iMAP: An integrated bioinformatics and visualization pipeline for microbiome data analysis. BMC Bioinformatics, 20. https://doi.org/10.1186/S12859-019-2965-4

## :tada: Raise awareness
> Please help increase awareness of freely available tools for microbiome data analysis.
See [Dimensions of the iMAP article](https://badge.dimensions.ai/details/id/pub.1117740326)
