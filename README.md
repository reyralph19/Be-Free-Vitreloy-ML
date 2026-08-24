# Machine Learning Discovery of Beryllium-Free Vitreloy 1 Replacements

This repository contains the dataset and Python code required to reproduce the machine learning screening pipeline presented in our manuscript: *"Data-Driven Discovery of a Beryllium-Free Vitreloy 1 via High-Throughput Machine Learning"*.

## Files Included
* `final_dataset.csv`: The dataset of 715 bulk metallic glasses and their pre-calculated thermodynamic/topological features.
* bmg_discovery_pipeline.ipynb`: The complete Python script for preprocessing, Random Forest classification, threshold optimization, and high-throughput screening using `matminer`.
* `requirements.txt`: The list of Python dependencies required to run the code.

## How to Run
1. Ensure you have Python installed.
2. Install the required libraries by running: `pip install -r requirements.txt`
3. Run the pipeline: `python bmg_discovery_pipeline.py`
