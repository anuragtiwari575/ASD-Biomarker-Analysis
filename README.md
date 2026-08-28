<img width="2559" height="934" alt="image" src="https://github.com/user-attachments/assets/de38bb96-db42-4e55-a127-b7d80a4fd027" /># ASD-Biomarker-Analysis
Reproducible machine learning framework for ASD classification and robust neuroimaging biomarker discovery across multi-site MRI datasets.
# Robust Neuroimaging Biomarker Discovery for Autism Spectrum Disorder

This repository contains the code and supporting materials for a machine learning framework for identifying robust neuroimaging biomarkers associated with Autism Spectrum Disorder (ASD) using multi-site MRI data.

## Overview

The project investigates whether reproducible neuroimaging patterns can be identified across independent datasets and acquisition sites while maintaining reliable ASD classification performance.

The framework includes data preprocessing, feature extraction, machine learning based classification, cross-validation, statistical evaluation, and biomarker stability analysis.

## Key Objectives

* ASD versus healthy control classification using structural neuroimaging data
* Evaluation across multiple independent datasets and sites
* Robust model validation with leakage-aware experimental design
* Identification of stable and reproducible neuroimaging biomarkers
* Assessment of biomarker consistency across resampling and validation procedures
* Comparison of different machine learning models and experimental settings

## Repository Structure

```text
.
├── data/                # Dataset information and preprocessing specifications
├── preprocessing/       # Data preprocessing scripts
├── features/            # Feature extraction and feature processing
├── models/              # Machine learning models
├── experiments/         # Experimental and evaluation scripts
├── analysis/            # Statistical and biomarker analyses
├── results/             # Experimental results and summaries
├── figures/             # Generated figures
├── tables/              # Generated tables
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Datasets

The experiments use publicly available neuroimaging datasets. Due to dataset-specific licensing and distribution policies, the original imaging data are not included in this repository.

Please obtain the datasets directly from their respective official sources and follow all applicable usage and citation requirements.

## Reproducibility

The repository is intended to support reproducible analysis. Experimental procedures, preprocessing steps, model configurations, evaluation protocols, and analysis scripts are provided where applicable.

Before running the experiments, configure the dataset paths according to the local directory structure.

## Requirements

The analysis is implemented in Python. Required packages are listed in:

```text
requirements.txt
```

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

After configuring the dataset paths, the analysis can be executed through the scripts provided in the corresponding experiment directories.

Detailed execution instructions and configuration parameters will be provided as the repository is finalized.

## Results

The repository contains scripts and supporting materials for reproducing the reported analyses, including classification performance, model comparisons, and biomarker stability analyses.

## Citation

If you use this code or methodology in your research, please cite the associated publication:

```text
Citation information will be added following publication.
```

## License

The license and conditions for reuse will be specified here.

## Contact

For questions regarding the code or methodology, please open an issue in this repository.
