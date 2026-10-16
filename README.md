# Machine Learning Discovery of Beryllium-Free Vitreloy 1 Replacements

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22108520.svg)](https://doi.org/10.5281/zenodo.22108520)

This repository contains the dataset and Python code required to reproduce the machine learning screening pipeline presented in our manuscript: *"Data-Driven Discovery of a Beryllium-Free Vitreloy 1 via High-Throughput Machine Learning"*.

## Files Included

* `final_dataset.csv`: The dataset of 715 bulk metallic glasses (dynamically deduplicated to 704 unique alloys in the pipeline) and their pre-calculated thermodynamic/topological features.
* `bmg_discovery_pipelinev2.1.ipynb`: The complete Jupyter Notebook containing the dual-model Random Forest architecture, Repeated Stratified k-Fold Cross-Validation, SHAP (SHapley Additive exPlanations) interpretability analysis, threshold sensitivity, and high-throughput screening using `matminer`.
* `requirements.txt`: The list of Python dependencies required to run the code locally.

## How to Run

1. **Cloud Execution (Recommended):** You can upload the `bmg_discovery_pipelinev2.1.ipynb` and `final_dataset.csv` directly to Google Colab and run the cells sequentially. (The first cell automatically installs the dependencies listed in `requirements.txt`).
2. **Local Execution:**
   * Ensure you have Python and Jupyter installed.
   * Install the required libraries by running: `pip install -r requirements.txt` in your terminal.
   * Open the notebook by running: `jupyter notebook bmg_discovery_pipelinev2.1.ipynb`
