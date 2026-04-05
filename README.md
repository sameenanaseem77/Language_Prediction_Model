# Language Prediction Model

## Overview
This project implements a language detection model using Natural Language Processing (NLP) techniques. The model predicts the language of a given text based on a dataset of multilingual sentences.

## Features
- Text preprocessing and feature extraction using CountVectorizer
- Language classification using Multinomial Naive Bayes
- Support for multiple languages

## Dataset
The model is trained on `language_dataset_2200.csv`, which contains text samples in various languages with corresponding language labels.

## Dependencies
- pandas
- numpy
- scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sameenanaseem77/Language_Prediction_Model.git
   cd Language_Prediction_Model
   ```

2. Install the required packages:
   ```bash
   pip install pandas numpy scikit-learn
   ```

## Usage
Run the Jupyter notebook `sameena.ipynb` to:
- Load and explore the dataset
- Train the language prediction model
- Evaluate the model's performance
- Make predictions on new text samples

## Model Details
- **Vectorizer**: CountVectorizer for converting text to numerical features
- **Classifier**: MultinomialNB for language classification
- **Evaluation**: Accuracy and other metrics on test data

## Contributing
Feel free to contribute by improving the model, adding more languages, or optimizing the code.

## License
This project is open-source. Please check the license file for details.
