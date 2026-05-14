# Machine Learning Projects

## Overview

This repository contains three machine learning projects from my Introduction to Machine Learning coursework. Each project focuses on a different area of machine learning, including supervised learning, image classification, and probabilistic graphical models.

Each folder includes the Jupyter Notebook used for the project and a PDF version of the code for easier viewing.

The projects in this repository helped me practice the full machine learning workflow, including data preprocessing, model training, evaluation, visualization, and interpretation of results.

## Purpose

The purpose of this repository is to organize and document my machine learning coursework in one place. These projects demonstrate my ability to work with datasets, apply machine learning algorithms, evaluate model performance, and explain technical results clearly.

The main goals of these projects were to:

- Apply machine learning concepts to real datasets
- Preprocess and clean data before model training
- Train and evaluate supervised learning models
- Use neural network-based image classification techniques
- Work with probabilistic models and Bayesian networks
- Interpret model performance using metrics and visualizations
- Present code and results in a clear, reproducible format

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- TensorFlow/Keras
- VGG16
- NetworkX
- Machine learning evaluation metrics

## Repository Structure

```text
machine-learning-projects/
├── Project 1/
│   ├── Project 1 notebook/code files
│   └── Project 1 PDF code export
├── Project 2/
│   ├── Project 2 notebook/code files
│   └── Project 2 PDF code export
|   └── Project 2 answers from instructor questions
├── Project 3/
│   ├── Project 3 notebook/code files
│   └── Project 3 PDF code export
└── README.md
```

Note: Each project folder contains both the original Jupyter Notebook and a PDF version of the code.

## Project Descriptions

## Project 1: Linear Classification and Model Evaluation

Project 1 focused on supervised machine learning and linear classification. The project involved preparing data, training classification models, testing model performance, and comparing results across different approaches.

This project helped me understand how preprocessing and model selection affect classification performance.

Concepts demonstrated:

- Data preprocessing
- Feature normalization
- Linear classification
- Perceptron-style learning
- Logistic regression concepts
- Training and testing splits
- Cross-validation
- Model accuracy evaluation
- Performance comparison
- Feature transformation and analysis

Skills practiced:

- Loading and preparing datasets
- Cleaning and transforming input features
- Training classification models
- Evaluating model performance
- Interpreting results from multiple experiments
- Explaining how preprocessing affects model behavior

## Project 2: Image Classification with VGG16

Project 2 focused on image classification using a pretrained deep learning model. The project used VGG16 to classify images and explore how pretrained convolutional neural networks can be applied to visual recognition tasks.

This project helped me understand how transfer learning and pretrained image models can be used when building classification systems.

Concepts demonstrated:

- Image classification
- Convolutional neural networks
- Transfer learning
- VGG16 pretrained model usage
- Image preprocessing
- Feature extraction
- Model prediction
- Classification output interpretation
- Visual data analysis

Skills practiced:

- Preparing image data for model input
- Using pretrained neural network models
- Running predictions on image datasets
- Interpreting classification results
- Understanding how deep learning models process visual features
- Evaluating model behavior on image-based tasks

## Project 3: Bayesian Networks and Probabilistic Reasoning

Project 3 focused on Bayesian networks and probabilistic reasoning. The project involved working with graph-based models to represent relationships between variables and reason about probabilities.

This project helped me understand how machine learning can be used not only for prediction, but also for modeling uncertainty and relationships between events.

Concepts demonstrated:

- Bayesian networks
- Probabilistic graphical models
- Conditional probability
- Markov blankets
- Graph-based reasoning
- Network structure analysis
- Dependency relationships between variables
- Probabilistic inference concepts

Skills practiced:

- Building and analyzing graph structures
- Representing dependencies between variables
- Interpreting probability relationships
- Using NetworkX for graph-based modeling
- Understanding how probabilistic models support decision-making
- Explaining uncertainty in machine learning systems

## How to Use This Repository

Each folder contains a separate machine learning project. To review the work:

1. Open the project folder.
2. Review the Jupyter Notebook file for the full code and workflow.
3. Open the PDF version if you want a static view of the code.
4. Review the project outputs, visualizations, and explanations inside the notebook.

Because these projects were completed as separate coursework assignments, each folder may have slightly different setup requirements depending on the libraries used.

## General Setup

To run the notebooks locally, install Python and Jupyter Notebook.

### 1. Clone the repository

```bash
git clone <repository-url>
cd machine-learning-projects
```

### 2. Create a virtual environment

On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install common dependencies

```bash
pip install numpy pandas scikit-learn matplotlib jupyter networkx tensorflow
```

Depending on the project, additional packages may be required.

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open the notebook inside the project folder you want to review.

## Machine Learning Concepts Demonstrated

This repository demonstrates several important machine learning concepts:

- Supervised learning
- Linear classification
- Logistic regression
- Feature preprocessing
- Cross-validation
- Model evaluation
- Image classification
- Transfer learning
- Convolutional neural networks
- VGG16
- Bayesian networks
- Probabilistic reasoning
- Graph-based modeling
- Conditional probability
- Model interpretation

## Security and Cybersecurity Relevance

Although these projects were created for a machine learning course, the concepts are relevant to cybersecurity and security analytics.

Machine learning can support cybersecurity work in areas such as:

- Intrusion detection
- Malware classification
- Phishing detection
- Anomaly detection
- User behavior analytics
- Security event classification
- Risk scoring
- Pattern recognition in logs and network data

These projects helped build the foundation needed to understand how machine learning models can be applied to security-related problems.

## What I Learned

Through these projects, I gained hands-on experience with:

- Preparing datasets for machine learning
- Training and evaluating classification models
- Understanding the impact of preprocessing on model performance
- Using pretrained neural networks for image classification
- Working with VGG16 and transfer learning concepts
- Building and analyzing Bayesian networks
- Modeling uncertainty with probabilistic methods
- Using Python libraries for machine learning and data analysis
- Interpreting model results and explaining technical findings
- Organizing machine learning work in Jupyter Notebooks

These projects helped me understand that machine learning is not just about running a model. It requires preparing the data correctly, choosing the right algorithm, evaluating results carefully, and explaining what the model is actually doing.

## Future Improvements

Future improvements for this repository could include:

- Adding individual README files inside each project folder
- Adding a `requirements.txt` file
- Adding screenshots of important visualizations and results
- Adding confusion matrices and performance tables
- Adding short summaries of each dataset used
- Adding clearer explanations of model results
- Adding links to public datasets where allowed
- Refactoring notebooks into Python scripts
- Adding comments to explain important code sections
- Adding a security-focused machine learning example, such as anomaly detection or phishing classification
- Renaming project folders to make them more descriptive

## Disclaimer

This repository was created for educational purposes as part of an Introduction to Machine Learning course. The notebooks and PDF exports are intended to demonstrate machine learning concepts, coursework, and applied practice.

The models and results are for academic use and are not intended for production deployment without additional testing, validation, documentation, and review.
