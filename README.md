# Ensemble Approach for Alzheimer's Disease Detection

This repository contains the implementation of the paper "An Efficient Ensemble Approach for Alzheimer's Disease Detection Using an Adaptive Synthetic Technique and Deep Learning" (Diagnosis 2023, 13(15), 2489; https://doi.org/10.3390/diagnostics13152489).

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Files Description](#files-description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

Alzheimer's disease (AD) is a progressive neurodegenerative disorder that affects millions of people worldwide. Early detection of AD is crucial for effective treatment and management. This project implements an ensemble approach combining EfficientNet-B2 and VGG16 models for the detection of Alzheimer's disease using MRI images.

Key features of this implementation include:
- Use of ADASYN (Adaptive Synthetic) technique for addressing class imbalance in the dataset
- Ensemble approach combining EfficientNet-B2 and VGG16 models
- Feature concatenation to leverage the strengths of both models

The motivation behind this research is to improve the accuracy and reliability of AD detection using deep learning techniques. By leveraging the strengths of multiple models, addressing class imbalance issues, and combining features through concatenation, we aim to contribute to the development of more effective diagnostic tools for AD.

## Dataset

The project uses the Alzheimer's Dataset (4 class of images) available on Kaggle:

https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images

This dataset contains MRI images categorized into four classes:
- Mild Demented
- Moderate Demented
- Non Demented
- Very Mild Demented

## Files Description

1. `Alzheimers_EffNetB2_and_VGG.ipynb`: Jupyter notebook containing the implementation and training of individual EfficientNet-B2 and VGG16 models, including the application of ADASYN for data balancing.

2. `Ensemble.ipynb`: Jupyter notebook with the implementation of the ensemble model, combining EfficientNet-B2 and VGG16 using a feature concatenation process.

3. `best_model_effnetb2.pth`: Saved weights for the trained EfficientNet-B2 model.

## Installation

To run this project, you need to have Python 3.7+ installed. Clone this repository and install the required packages:

```bash
[git clone https://github.com/yourusername/alzheimers-detection-ensemble.git](https://github.com/junayed-hasan/alzheimers-disease-detection.git)
cd alzheimers-disease-detection
```

## Usage

1. Download the notebooks 

2. Go to Kaggle > Code > New notebook

3. Import the notebook

4. Add the Alzheimer's Dataset (4 class of Images) dataset as input.

5. Run the cells!

## Contributing

Contributions to this project are welcome. Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## Copyright

© 2023 Mohammad Junayed Hasan. All rights reserved.

This project is a reproduction of the work presented in:

Qin, B.; Gao, X.; Zhan, Z.; Fan, W.; Wu, Y.; Salehi, S.; Zhang, Y.-D. An Efficient Ensemble Approach for Alzheimer's Disease Detection Using an Adaptive Synthetic Technique and Deep Learning. Diagnostics 2023, 13, 2489. https://doi.org/10.3390/diagnostics13152489
