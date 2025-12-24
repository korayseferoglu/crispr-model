# CRISPR-Cas9 Efficiency Predictor Model (Deep Learning)
This repository hosts the trained weights and architecture for a CNN-based model designed to predict sgRNA cleavage efficiency.

### Technical Details
- **Architecture:** Convolutional Neural Network (CNN).
- **Format:** Exported for **TensorFlow.js** (Client-side inference).
- **Training Data:** Based on the **Doench et al. (2016)** dataset and Microsoft Research Azimuth project.
- Designed the biological algorithms and scoring logic independently, leveraging AI-augmented coding techniques to accelerate software development and prototype deployment.

### File Descriptions
- `model.json`: The neural network's topology and layer configuration.
- `group1-shard1of1.bin`: The binary weight data for the trained model.

### Purpose
This model analyzes 30-nucleotide DNA sequences to provide efficiency scores, helping researchers optimize their gene-editing experiments by selecting the most potent sgRNAs.
