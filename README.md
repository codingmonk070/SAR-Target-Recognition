# Two-Stream CNN for SAR Target Recognition

This repository contains an implementation of a two-stream convolutional neural network (CNN) architecture for military vehicle recognition in Synthetic Aperture Radar (SAR) imagery.

## Features
- Two-stream CNN architecture for SAR target recognition
- Bilateral filtering for noise suppression while preserving edge information
- Stream 1 for fine-grained feature extraction using convolutional layers and global pooling
- Stream 2 for high-level feature aggregation using convolutional layers and dense networks with dropout regularization
- Achieved **98.10% overall accuracy** and **97.95% average accuracy** on the MSTAR-10 dataset
- Optimized model with **528,518 parameters** for resource-constrained environments
- Performance validated through **ROC curves** and **AUC metrics** (close to 1.0 for all classes)

## Dependencies
- TensorFlow
- OpenCV
- NumPy
- scikit-learn
- Matplotlib

## Installation
```bash
pip install tensorflow opencv-python numpy scikit-learn matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/codingmonk070/SAR-Target-Recognition.git
```
2. Install the dependencies.
3. Run the notebook or script to perform SAR target recognition.

## References
This project is inspired by:
Huang, X., Yang, Q., & Qiao, H. (2020). **Lightweight two-stream convolutional neural network for SAR target recognition**. *IEEE Geoscience and Remote Sensing Letters*, 18(4), 667-671.
[Link to Paper](https://doi.org/10.1109/LGRS.2020.2969969)

Note: This implementation is independently developed using TensorFlow, with modifications in noise handling and architecture.

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

