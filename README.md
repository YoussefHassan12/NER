# NER
Entraînement d'un modèle de reconnaissance d'entités nommées dans le domaine biomédical

This repository contains code and resources related to the detection of environmental factors using Spacy models. The goal of this project is to detect and analyze various types of environmental factors, including biological and chemical factors, using natural language processing techniques.

## Repository Structure
The repository is structured as follows:

1. fact_env: This folder contains a Spacy model that specializes in detecting entities related to environmental factors.

2. model-best: This folder contains a Spacy model trained to detect a wide range of biological, chemical, and environmental factors. This model was trained using the result_entities.csv data.

3. glove.6B.100d.txt: This file is used in a Python script to vectorize the data. It provides pre-trained word embeddings for text processing tasks. you can download it from the following link:https://www.kaggle.com/datasets/danielwillgeorge/glove6b100dtxt

4. Model_combiner.ipynb: This Jupyter notebook demonstrates how to use and combine the Spacy models for detecting and studying the correlation between the entities. It provides examples and explanations of the code.

5. result_entities.csv: This CSV file contains the data from the Nero corpus that was used to train the model-best. It serves as the training data for the model.

6. report: This folder contains a report that describes the project in detail, including the methodology, results, and conclusions.

7. proposition_TER_NER-Biomed_S-Affeldt_2022-2023.pdf: This file provides an overview of the project idea, explaining the motivation, goals, and potential applications.

## Usage
1. To use the environmental factors entity detection models and explore the correlation between entities, follow these steps:

2. Ensure you have the required dependencies installed, such as Spacy and Jupyter Notebook.

3. Load the Spacy models provided in the fact_env and model-best folders.

4. Vectorize the input data using the pre-trained word embeddings from glove.6B.100d.txt.

5. Use the models to detect entities and study their correlation based on the examples and code provided in the Model_combiner.ipynb notebook.

## Contributions
Contributions to this project are welcome! If you have any suggestions, bug fixes, or improvements, please feel free to submit a pull request.
