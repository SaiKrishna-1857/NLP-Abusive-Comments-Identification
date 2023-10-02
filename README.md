
# Detecting Abusive Comments in Multiple Languages: A Multilingual Approach

## Authors:
- Sai Krishna Sangeetha
- Venkata Sai Kumar Ganesula
- College of Engineering and Computer Science, University of Central Florida, Orlando, Florida 32816

## Overview:
This project aims to utilize Natural Language Processing (NLP) techniques to identify negative comments posted on social media platforms. By highlighting these comments, the objective is to promote positive content and foster a more constructive online community.

## Notebooks:

### 1. **baseline_model_1.ipynb**:
- **Purpose**: Establishes a basic model for the project.
- **Key Features**:
  - Installation of `indic-nlp-library`.
  - Usage of `LogisticRegression` and `TfidfVectorizer`.
  - Data loading from Google Drive.

### 2. **baseline_model_2.ipynb**:
- **Purpose**: Explores a more advanced model for the project.
- **Key Features**:
  - Utilizes deep learning libraries like `keras`.
  - Imports a diverse set of libraries for data processing and modeling.

### 3. **hypothesis_1.ipynb**:
- **Purpose**: Experiments with transformer-based models for NLP tasks.
- **Key Features**:
  - Installation and use of the `transformers` library.
  - Configuration settings for model parameters, data paths, and more.
  - Data loading and preprocessing.

### 4. **hypothesis_2.ipynb**:
- **Purpose**: Possible extension or modification of the experiments conducted in "hypothesis_1.ipynb".
- **Key Features**: Similar to "hypothesis_1.ipynb".

### 5. **proposed_model.ipynb**:
- **Purpose**: This notebook presents the culmination of insights gathered from previous experiments and introduces the finalized model for detecting negative comments.
- **Key Features**:
  - Utilizes advanced NLP techniques, hinting at a possible blend of traditional and transformer-based approaches.
  - Streamlined preprocessing and data handling to ensure optimal model input.
  - Incorporates refined hyperparameters and model configurations based on prior results from hypothesis testing.
  - Includes model evaluation metrics, visualizations, and comparisons to baseline models, showcasing the improvements achieved with the proposed approach.

## Report:
The accompanying report provides detailed insights into the objectives, methodologies, and findings of the project. Key highlights:
- Use of the MuRIL model, which outperforms other models in interpreting semantic expressions.
- References to previous works in the domain of hate speech detection, primarily in English.
- A brief overview of the BERT-based architecture utilized.
