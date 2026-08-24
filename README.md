# Machine Learning Discovery of Beryllium-Free Vitreloy 1 Replacements

This repository contains the dataset and Python code required to reproduce the machine learning screening pipeline presented in our manuscript: *"Data-Driven Discovery of a Beryllium-Free Vitreloy 1 via High-Throughput Machine Learning"*.

## Files Included
* `final_dataset.csv`: The dataset of 715 bulk metallic glasses and their pre-calculated thermodynamic/topological features.
* `bmg_discovery_pipeline.ipynb`: The complete Jupyter Notebook for preprocessing, Random Forest classification, threshold optimization, and high-throughput screening using `matminer`.
* `requirements.txt`: The list of Python dependencies required to run the code locally.

## How to Run
1. **Cloud Execution (Recommended):** You can upload the `bmg_discovery_pipeline.ipynb` and `final_dataset.csv` directly to Google Colab and run the cells sequentially. (Use `!pip install -r requirements.txt` in the first cell to install dependencies).
2. **Local Execution:** 
   * Ensure you have Python and Jupyter installed.
   * Install the required libraries by running: `pip install -r requirements.txt` in your terminal.
   * Open the notebook by running: `jupyter notebook bmg_discovery_pipeline.ipynb`
