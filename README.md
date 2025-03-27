#  Neural Networks and Machine Learning in Image Classification.

This repository contains the code and documentation for the tutorial:  
*Recognising Neural Networks and Machine Learning in Image Classification*  
Prepared for the Machine Learning and Neural networking Techniques module led by Peter Scicluna.

---

## Tutorial Overview

Using the Intel Image Classification Dataset, the lesson investigates the use of Convolutional Neural Networks (CNNs) for image classification, comparing the effectiveness of shallow and deep CNN models.
In order to increase dataset variability, data preprocessing procedures included scaling photos to 150x150 pixels, normalising pixel values, and using augmentation techniques such random flips and rotations.
While the deep CNN obtained 85% accuracy and showed superior handling of fine-grained patterns despite overfitting problems, the shallow CNN only managed 72% accuracy and had trouble with complex features.
Techniques like dropout and early stopping were used to solve the main issues of class imbalance, overlapping features (such as mountains and glaciers), and model overfitting.
To further enhance classification performance, future research recommends using pre-trained models, experimenting with higher resolutions, and integrating transfer learning.

---

## Repository Contents

| File/Folder        | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Muhammad_Usman javedMLNN.ipynb | Jupyter notebook containing the full tutorial and analysis   |
| README.md        | This documentation file with setup, usage, and accessibility notes |
| LICENSE          | MIT License for reuse and distribution                       |
| images/ (optional) | Folder for dendrograms and visual outputs                  |

---

## How to Run the Tutorial

### Requirements

Install the following Python packages:

```bash
pip install tensor flow,numpy, pandas, matplotlib, seaborn scikit-learn scipy jupyter
Also use Keras layers and keras models.
