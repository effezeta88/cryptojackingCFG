# Cryptojacking CFG Dataset

Due to the large size of the files, the dataset is available at the following link: [10.5281/zenodo.20053301](https://doi.org/10.5281/zenodo.20053301)

The repository contains the dataset of **Control Flow Graphs (CFGs)** used in the paper *Linking Structure and Time: A Lineage-Based Framework for Cryptojacking Analysis*.

The dataset includes **all CFGs extracted from the CJ executables considered during the analysis**. It is provided to support reproducibility, independent verification of results, and further research on cryptojacking malware analysis.

## Open Science and Reproducibility

We fully acknowledge the importance of **open science policies** in facilitating sharing, transparency, and collaboration within the research community. In line with these principles, we make the full dataset publicly available.

## Data Collection

Our study is based on data collected from **MalwareBazaar** (https://bazaar.abuse.ch/), a public malware repository operated by **abuse.ch** and widely used in large-scale malware analysis.

Malware samples from **March 2020 to October 2025** were collected, covering multiple years and enabling a longitudinal analysis of the evolution of cryptojacking malware.

Cryptojacking (CJ) malware samples were selected by retrieving a predefined set of CJ-related tags, including *coinminer*, *cryptominer*, *miner*, and *crypto*.

This collection resulted in a total of **5,352 samples**, consisting primarily of:

- **Windows PE executables** (`.exe`): 4,505 samples
- **Linux ELF binaries** (`.elf`): 366 samples

The dataset also includes a smaller number of script-based and compressed formats, such as `.sh`, `.zip`, and `.ps1`.

To ensure compatibility with the analysis pipeline, only executable formats that could be consistently processed were retained: **`.exe`, `.elf`, and `.dll`**.

After this filtering step, the final dataset consists of **4,078 samples**.

## Dataset Description

The repository contains the **control flow graphs (CFGs)** extracted from the analyzed cryptojacking executables. Each graph represents the control-flow structure of one binary considered in the study.

These CFGs were generated as part of the experimental workflow described in the paper and constitute the primary structural artifacts used during the analysis.

## Repository

The dataset is available at:

**[https://github.com/effezeta88/cryptojackingCFG.git](https://doi.org/10.5281/zenodo.20053301)**

## Intended Use

This dataset may be useful for:

- reproducing the experiments reported in the paper;
- benchmarking malware analysis methods;
- comparative studies on binary similarity and structural analysis;
- further research on cryptojacking detection and characterization.

## Citation

If you use this dataset in your work, please cite the corresponding paper.
