Adera GAN Model
This repository contains the implementation of a Generative Adversarial Network (GAN) model for generating and analyzing T-cell receptor (TCR) sequences. The project uses deep learning techniques to study real, fake, and generated TCR sequences, with a focus on amino acid sequence analysis and visualization.

Features
Data Preprocessing:

Converts amino acid sequences to numerical representations using predefined mappings.
Normalizes sequence data using robust scaling.
GAN Architecture:

Generator with dense and LSTM layers.
Discriminator for distinguishing real and fake/generated sequences.
Training Process:

Implements early stopping based on discriminator loss, AUC, and accuracy.
Metrics: Precision, Recall, F1-Score, AUC.
Visualization:

t-SNE plots for real, fake, and generated data.
Violin plots showing amino acid frequency distributions.
Metrics analysis using Shannon entropy, Hurst exponent, Gini index, and spectral entropy.
Evaluation:

Computes Euclidean, cosine similarity, KL divergence, and Earth Mover's distance between real, fake, and generated sequences.
Performs Kolmogorov-Smirnov test to compare distributions.
