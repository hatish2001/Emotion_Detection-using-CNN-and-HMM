# Emotion Classification Project

## Description

This project focuses on classifying human emotions from images using a Convolutional Neural Network (CNN) followed by a Hidden Markov Model (HMM). It aims to accurately predict the emotional state depicted in images by learning from a labeled dataset. This approach combines the feature extraction capabilities of CNNs with the sequence modeling strengths of HMMs.

## Getting Started

### Dependencies

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- hmmlearn

Ensure you have Python installed on your system and all the required libraries. You can install the dependencies via pip:

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn hmmlearn
```
## Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/emotion-classification.git
cd emotion-classification
```


## Executing Program
Ensure the dataset is structured properly, with separate folders for training and validation sets, and subfolders for each emotion category.

Run the Jupyter notebook to train and evaluate the model:

```bash
jupyter notebook Emotion_Classification.ipynb
```
## Dataset
- The dataset used for this project is structured into separate folders for training and testing. Each folder contains subfolders labeled by emotion categories (e.g., happy, sad, angry).

## Model Architecture
- The model consists of a CNN for feature extraction, followed by an HMM for sequence modeling. The CNN uses layers like Conv2D, MaxPooling2D, and Dense for learning spatial hierarchies, while the HMM models the sequence of emotions.

## Results
- Summarize the results, including accuracy and performance metrics. You may also include plots or confusion matrices to illustrate the model's performance.

## Contributing
- Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

Please ensure to update tests as appropriate.
