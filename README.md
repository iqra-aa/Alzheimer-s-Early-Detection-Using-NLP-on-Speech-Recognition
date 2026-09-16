
# Alzheimer's Early Detection Using NLP on Speech Recognition

## Project Overview

This project focuses on developing an AI-based system for the early detection of Alzheimer's disease using **Natural Language Processing (NLP)** and speech recognition techniques.

The system analyzes speech recordings, converts spoken language into text, and examines linguistic patterns that may be associated with cognitive decline. Machine learning and deep learning models are then used to estimate the likelihood of Alzheimer's disease based on the analyzed speech data.

The project combines **speech recognition, NLP, machine learning, deep learning, and a React-based web interface** to provide an interactive platform for speech-based analysis.

## Table of Contents

* [Project Overview](#project-overview)
* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
* [Dataset](#dataset)
* [Model](#model)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Acknowledgments](#acknowledgments)
* [Website Interface](#website-interface)



## Features

### Speech Recognition

The application uses the **AssemblyAI speech-to-text API** to convert audio recordings into text for further analysis.

### NLP Analysis

The transcribed speech is processed using Natural Language Processing techniques to examine linguistic characteristics and patterns associated with Alzheimer's disease.

The project applies multiple NLP approaches to improve the analysis of speech transcriptions.

### Machine Learning Analysis

Different machine learning and deep learning approaches are used to analyze speech-derived text and classify the data.

### React-Based Interface

A modern web interface has been developed using **React**, allowing users to interact with the system and view speech analysis results in an accessible format.

The interface is designed to provide a straightforward workflow for submitting speech input and reviewing the resulting analysis.

## Dataset

The project uses the **DementiaBank** dataset.

### Source

**DementiaBank:**
https://www.tensorflow.org/datasets/catalog/dementiabank

### Dataset Description

The DementiaBank dataset contains audio recordings from:

* 117 individuals with Alzheimer's Disease
* 93 healthy individuals

The participants describe an image, and the project uses the available speech recordings for classification.

### Data Processing

Plain-text data was extracted from speech transcripts using the `pylangacq` library.

The extracted text was then prepared for NLP processing and model development.

## Model

The project explores several machine learning and deep learning models for identifying patterns within speech data.

### Models Used

1. **Random Forest**
2. **SVC with Grid Search**
3. **Naive Bayes SVC**
4. **LSTM**
5. **Bidirectional LSTM**

### Model Training

The models were trained using speech-derived data to identify patterns that may help distinguish between Alzheimer's Disease and healthy participants.

Different machine learning and deep learning approaches were explored to evaluate their ability to classify the available speech data.

### Evaluation

Model performance was evaluated using classification metrics including:

* Accuracy
* F1 Score
* ROC-AUC

## Results

The project achieved an overall reported accuracy of **84%**.

### ROC-AUC

The ROC-AUC curve for the **Naive Bayes SVC (NB_SVC)** model is shown below:

![NB-SVC ROC](images/NB-SVC_ROC.jpg)

## Contributing
## License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for additional information.

## Acknowledgments

Special thanks to the resources and technologies that supported the development of this project.

### DementiaBank

Thanks to **Dr. Brian MacWhinney** and the DementiaBank project for providing access to the dataset used for speech analysis.

### AssemblyAI

Thanks to **AssemblyAI** for providing the speech-to-text API and SDK used to convert audio recordings into text.

## Website Interface

The project includes a web-based interface for interacting with the speech analysis system.

### Home Page

![Home Page](images/homepage.png)

### Analysis Page

![Analysis Page](images/analysispage.png)

### Results Page

![Results Page](images/resultspage.png)

## Author

**Iqra**
