# Fake News Classification

This repository contains code for a fake news classification task using the Passive Aggressive algorithm. The code is written in Python and utilizes various libraries from the scikit-learn (sklearn) package.

## Code Overview

The code performs the following tasks:

1. Import necessary libraries and modules for data manipulation, machine learning, and evaluation.
2. Read the dataset from a CSV file.
3. Print the shape and preview the dataset.
4. Extract and display the labels associated with the data.
5. Split the dataset into training and testing subsets.
6. Initialize a TF-IDF vectorizer and transform the text data.
7. Initialize a Passive Aggressive Classifier, fit it on the training data, and make predictions on the testing data.
8. Calculate and print the accuracy of the model's predictions.
9. Build a confusion matrix to evaluate the model's performance.

## Requirements

The code requires the following dependencies:

- Python 
- numpy 
- pandas 
- scikit-learn 

Install the dependencies using pip:

```
pip install numpy pandas scikit-learn
```

## Usage

To run the code:

1. Clone this repository to your local machine.
2. Ensure that you have the required dependencies installed.
3. Replace the file path in the code to point to your own dataset (if necessary).
4. Execute the code in a Python environment.
5. Review the output to see the dataset information, model accuracy, and confusion matrix.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.
