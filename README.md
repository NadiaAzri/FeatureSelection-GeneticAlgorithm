# Feature Selection Genetic Algorithm and Classification


This repository contains Python code for feature selection using a genetic algorithm and various classification algorithms applied to a breast cancer dataset. The dataset is loaded from a CSV file using pandas, and preprocessing steps include handling missing values and label encoding.

## Feature Selection with Genetic Algorithm

The genetic algorithm is implemented using the DEAP library to evolve a population of binary strings representing selected features. 

## Classification Algorithms

The selected features are used to train SVM, Random Forest, Decision Tree, and Artificial Neural Network (ANN) classifiers. Additionally, a Multi-Layer Perceptron (MLP) classifier is included for comparison.

## Evaluation Metrics

The accuracy, precision, recall, and F1-score are calculated for each classifier. Confusion matrices are generated for the ANN classifier, and precision-recall metrics are computed for the MLP classifier.

## Dependencies

The code utilizes popular Python libraries such as NumPy, scikit-learn, pandas, Matplotlib, Seaborn, DEAP, Keras, and others. The data can be loaded either locally or from Google Colab.

## How to Use

1. **Environment Setup**
   - Make sure you have access to Google Colab.
   - Upload the dataset (`data.csv`) to your Google Colab environment.

2. **Install Dependencies**
   - Open a new Colab notebook.
   - Install the required libraries in requirements.txt file

3. **Run the Code**
   - Copy the provided code into separate cells in your Colab notebook.

4. **Adjust Parameters (Optional)**
   - You can customize parameters such as population size, generations, crossover probability, and mutation probability to suit your preferences.

5. **Review Results**
   - After running the code, the results, including classifier accuracies and evaluation metrics, will be printed in the Colab output.

6. **Explore and Experiment**
   - Feel free to experiment with different datasets, tweak the genetic algorithm parameters, or try other classifiers to see how the system behaves.

---

This updated section takes into account that Google Colab provides a pre-installed environment for many popular libraries, and users only need to install additional dependencies listed in the `requirements.txt` file.

---
