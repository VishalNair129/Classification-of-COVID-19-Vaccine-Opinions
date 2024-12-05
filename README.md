# COVID-19 Vaccine Opinion Classification and Symptom Detection on Twitter

This repository contains a classification model developed to analyze and classify tweets related to COVID-19 vaccine opinions and symptom reporting using neural networks. The primary objective is to understand public sentiment towards COVID-19 vaccines and identify tweets reporting COVID-19 symptoms.

## Project Overview

This project uses a Multi-Layer Perceptron (MLP) model to perform classification tasks on tweets. The methodology involves preprocessing tweets, tokenization, stemming, and TF-IDF vectorization to prepare the data for training and classification. The goal is to classify tweets into specific categories related to vaccine opinion and symptom reporting.

### Author
- **Vishal Nair** - [v1292002@gmail.com](mailto:v1292002@gmail.com)

### Supervisor
- Dr. Kripabandhu Ghosh, Assistant Professor, CDS, IISER Kolkata

### Date
- December 4, 2024

---

## Contents

1. **Dataset and Tasks**
   - **Vaccine Opinion Classification**: 3-class classification (AntiVax, ProVax, Neutral).
   - **Symptom Reporting Detection**: 4-class classification (Primary Reporting, Secondary Reporting, Third-party Reporting, Non-Reporting).

2. **Data Exploration**
   - **Dataset Statistics**: Analysis of tweet datasets provided by the FIRE 2022 microblog track.
   - **Class Distribution**: Examination of class balance and distribution in both datasets.
   - **Attribute Analysis**: Preprocessing steps including tokenization, stemming, and TF-IDF vectorization.

3. **Experimental Setup**
   - **Algorithms Used**: 
      - *Multi-Layer Perceptron (MLP)*
   - **Evaluation Metrics**:
      - Macro F1-Score
      - Accuracy

4. **Results and Analysis**
   - **Performance Evaluation**: Analysis based on macro F1-Score and accuracy.

5. **Preprocessing and Feature Extraction**
   - **Preprocessing**: Removal of special characters, stop words, numbers, and short words.
   - **Tokenization**: Splitting text into tokens.
   - **Stemming**: Reducing words to their base form using the Lancaster stemmer.
   - **TF-IDF Vectorization**: Converting text into numerical features.

6. **Neural Network-Based Analysis**
   - **Model Architecture**: Multi-Layer Perceptron (MLP) implemented for classification.
   - **Training Strategy**: Training the MLP model using backpropagation and evaluating with test data.

---

## Installation and Setup

1. **Requirements**:
   - Python 3.x
   - Required libraries (listed in `requirements.txt`)


## Jupyter Notebook

The beginning of the Jupyter notebook `Summer_Internship_ML.ipynb` contains some of my work during my internship at IISER Kolkata on machine learning. The actual project work starts later in the notebook.

## Acknowledgments

This project is based on the datasets provided by the FIRE 2022 microblog track and supervised by Dr. Kripabandhu Ghosh, Assistant Professor, CDS, IISER Kolkata.

## References
1. [IRMiDis FIRE 2022 - Covid-19 datasets](https://sites.google.com/view/irmidis-fire2022/irmidis?authuser=0)
2. Christopher D. Manning, Prabhakar Raghavan, and Hinrich Schütze, *Introduction to Information Retrieval*, Cambridge University Press, 2008.
3. Aurélien Géron, *Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow*.
4. Dan Nelson, *Overview of Classification Methods in Python with Scikit-Learn*, StackAbuse.
5. [scikit-learn Documentation](https://scikit-learn.org)

## Contact
For any questions or inquiries, please contact:
- Vishal Nair
- Email: [v1292002@gmail.com](mailto:v1292002@gmail.com)
