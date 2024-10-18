# Microbiome Data Analysis with Autoencoders

## Overview

This project focuses on the analysis of microbiome data using Autoencoders. The primary goal is to reduce the dimensionality of high-dimensional microbiome datasets and reconstruct them back to their original format. The process includes measuring reconstruction loss to evaluate the performance of the model.

## Objectives

- Analyze and preprocess microbiome data.
- Develop an Autoencoder model to reduce feature dimensions.
- Reconstruct the low-dimensional data back to its original format.
- Calculate and visualize reconstruction loss to assess model performance.

## Dataset

The project utilizes microbiome data, which typically consists of both taxonomic and metadata features. The datasets used include:

## Microbiome Meta Data
- **Lung Baseline Data**: 590 rows x 604 columns
- **Lung Middle Data**: 159 rows x 604 columns
- **Lung Late Data**: 49 rows x 604 columns

## Microbiome Taxa Data
- **Lung Baseline Taxa Data**: 590 rows x 1461 columns
- **Lung Middle Taxa Data**: 159 rows x 604 columns
- **Lung Late Taxa Data**: 49 rows x 604 columns

## Methodology

1. **Data Preprocessing**:
    - Conversion of categorical meta data to numerical format.
    - Application of Min-Max scaling to normalize the data, improving model performance.

2. **Autoencoder Architecture**:
    - Construction of an Autoencoder with defined encoder and decoder components.
    - Implementation of latent space representation for dimensionality reduction.

3. **Model Training**:
    - Training the Autoencoder on the preprocessed microbiome data.
    - Monitoring training to prevent overfitting and ensure optimal performance.

4. **Evaluation**:
    - Calculation of reconstruction loss to evaluate the accuracy of data reconstruction.
    - Visualization of reconstruction loss over epochs to analyze model convergence.
  
5. **Results**:
   <img width="737" alt="Screenshot 2024-10-18 at 4 02 56 PM" src="https://github.com/user-attachments/assets/8655ef44-1749-4f92-9ab3-2f86b3389c7c">

## Installation

To run this project, clone the repository and install the required libraries:

```bash
git clone https://github.com/your-username/microbiome-autoencoder.git
cd microbiome-autoencoder
pip install -r requirements.txt
