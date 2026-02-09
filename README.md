Deep Generative Model for Synthetic Tabular Data
Overview

This project implements a deep generative model to generate synthetic tabular data using a GAN-based approach (CTGAN). The solution is designed to handle mixed data types (numerical and categorical) and evaluate the quality of synthetic data using machine learning performance comparison between real and synthetic datasets.

Technologies Used

Python

PyTorch

SDV (Synthetic Data Vault)

CTGAN

Pandas

Scikit-learn

Methodology
1. Data Processing

Loaded real-world tabular data using Pandas

Supported mixed data types without manual encoding

2. Model Implementation

Implemented CTGAN (Conditional Tabular GAN) using the SDV library

Trained the model on real data to learn feature distributions

3. Synthetic Data Generation

Generated N synthetic records using the trained CTGAN model

Maintained the same schema and feature structure as the real dataset

4. Evaluation

Trained a machine learning classifier on real data

Trained the same classifier on synthetic data

Compared model accuracy to assess synthetic data quality

Results

The generated synthetic data closely resembles real data

Machine learning models trained on synthetic data achieved comparable accuracy

This confirms the usefulness and realism of the synthetic dataset
