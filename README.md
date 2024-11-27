# Disease-Diagnoser

## Introduction
Many people experience symptoms and struggle to understand their potential causes. This application bridges that gap by leveraging a dataset of diseases, their symptoms, and treatments to predict the most relevant condition based on user input.

This program uses machine learning techniques, such as TF-IDF Vectorization and Cosine Similarity, to determine the closest match for a given set of symptoms.

## Features

Accepts user-inputted symptoms as free text.
Matches user symptoms to the most similar disease/disorder in the dataset.

### Displays:
The name of the closest-matched disease.
Common symptoms associated with the disease.
Recommended treatments for managing the condition.
Easy-to-use interface via a command-line prompt.

## Dataset
The application uses a dataset of diseases, their symptoms, and treatments. Each row in the dataset contains:

#### Code: A unique identifier for the condition.
#### Name: The name of the medical condition.
#### Symptoms: Common symptoms associated with the condition.
#### Treatments: Recommended treatments or therapies for management.

## Technologies Used

#### Programming Language: Python

#### Libraries:
pandas: For data manipulation and preprocessing.
scikit-learn: For TF-IDF vectorization and similarity computation.
