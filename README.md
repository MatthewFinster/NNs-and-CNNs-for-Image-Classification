# NNs and CNNs for Multi-Class Image Classification

This repository showcases a project focused on designing, implementing, and evaluating neural networks (NNs) and convolutional neural networks (CNNs) for a multi-class classification task using the MNIST dataset. It includes experiments on model architecture and hyperparameter optimisation to achieve high accuracy.

## Objectives
- Build and evaluate baseline NN and CNN models for image classification.
- Explore various NN and CNN architectures to improve accuracy.
- Optimise hyperparameters to enhance performance while reducing training time.
- Summarise findings and provide insights into model selection.

## Dataset
- **MNIST Dataset**: Handwritten digits (0-9) represented as 28x28 pixel grayscale images. The dataset is included as part of the `keras` library.

## Files
- `NNs and CNNs for image classification - code.ipynb`: Python notebook containing the implementation and experimentation for NNs and CNNs.
- `NNs and CNNs for image classification - report.pdf`: Detailed report documenting methodology, results, and analyses.

## Methodology
1. **Neural Networks (NNs):**
   - Baseline NN model with one dense layer.
   - Enhanced models with additional layers and neurons.
   - Performance comparison across architectures.

2. **Convolutional Neural Networks (CNNs):**
   - Baseline CNN with two convolutional layers and a dense layer.
   - Advanced CNN architectures with more layers and filters.
   - Exploration of dropout layers to prevent overfitting.

3. **Hyperparameter Optimisation:**
   - Experimented with optimisers (`SGD`, `Adam`) and learning rates.
   - Tested combinations of batch sizes and number of epochs.
   - Final model achieved an accuracy of 99.19% on the MNIST dataset.

## Results
- Deep architectures (both NNs and CNNs) generally outperformed shallow ones.
- The best performance was achieved by fine-tuning the CNN model with Adam optimiser and a learning rate of 0.002.

## License

This repository is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivs (CC BY-NC-ND)](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

The content is shared for educational purposes and as part of a portfolio. Redistribution, reuse for academic submissions, or plagiarism is strictly prohibited.

---

DISCLAIMER: This repository and its contents are shared for educational purposes and as part of a portfolio. Redistribution or reuse for academic submissions or plagiarism is strictly prohibited.
