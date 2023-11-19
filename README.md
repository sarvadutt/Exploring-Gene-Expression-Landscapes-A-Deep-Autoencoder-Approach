# Exploring-Gene-Expression-Landscapes-A-Deep-Autoencoder-Approach
"Unlocking Genetic Insights: Our project employs autoencoder neural networks to perform dimensionality reduction on diverse gene expression datasets. Explore reproducible analyses, hyperparameter tuning, and visualization for deep insights into genomic patterns."


# Gene Expression Autoencoder Project

## Overview
This project implements a gene expression autoencoder designed for dimensionality reduction and analysis of genomic datasets. The autoencoder is trained on FPKM (Fragments Per Kilobase Million) gene expression data, providing a powerful tool for researchers and bioinformaticians to explore complex genomic patterns.

## Code Structure
- `autoencoder.py`: The main script for training and evaluating the gene expression autoencoder.
- `grid_search.py`: Hyperparameter tuning using GridSearchCV for optimizing model performance.
- `notebooks/create_datasets.ipynb`: A Jupyter notebook facilitating the creation of genomic datasets.
- `results/`: A directory containing visualizations and evaluation results.
- `docs/`: A documentation folder that includes a Jupyter notebook detailing the process of data creation for reproducibility.

## Datasets
The project incorporates diverse genomic datasets:
- Human non-TATA promoters
- Human enhancers (FANTOM5 Project)
- Drosophila enhancers (Stark dataset)
- Human open chromatin regions (Ensembl dataset)

## Setup and Usage
1. **Dependencies Installation:** Execute `pip install -r requirements.txt` to install necessary packages.
2. **Dataset Creation:** Utilize the Jupyter notebook `notebooks/create_datasets.ipynb` for dataset generation.
3. **Model Training and Evaluation:** Run `python autoencoder.py` to train and evaluate the gene expression autoencoder.
4. **Hyperparameter Tuning:** Fine-tune hyperparameters using `python grid_search.py` with GridSearchCV.

## Visualization
Explore visualizations in the `results/` folder, providing insights into the original and reconstructed genomic data.

## Model Evaluation
Evaluate the model's performance on the test set using Mean Squared Error (MSE) as a metric.(0.085)

## Saving the Model
The final trained autoencoder model is saved to a file (`GSE18.pkl`) using joblib for future use.

## Reproducibility
Refer to the Jupyter notebook in the `docs/` folder for detailed instructions on dataset creation, ensuring full reproducibility of results.


