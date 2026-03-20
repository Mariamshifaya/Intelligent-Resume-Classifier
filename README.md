# Intelligent Resume Classifier

## Overview

The Intelligent Resume Classifier is a machine learning-driven application designed to automate the resume screening process. By leveraging Natural Language Processing (NLP) techniques and supervised learning algorithms, the system classifies resumes into predefined job roles, enabling efficient and consistent candidate evaluation.

This project addresses the challenges of manual resume screening by providing a scalable, data-driven solution that improves recruitment efficiency and reduces human bias.

---

## Repository Structure

```
├── README.md                     # Project documentation
├── app.py                        # Streamlit-based web application
├── requirements.txt              # Project dependencies
├── resume_model.pkl              # Trained machine learning model
├── vectorizer.pkl                # TF-IDF vectorizer
├── tech_resume_dataset_600.csv   # Training dataset
```

---

## Core Functionality

* Automated classification of resumes into job categories
* Text preprocessing including normalization and stopword removal
* Feature extraction using TF-IDF vectorization
* Model inference using a pre-trained classification model
* Interactive interface for user input and prediction display

---

## Technology Stack

* Python
* Natural Language Processing (NLTK)
* Scikit-learn
* Pandas and NumPy
* Streamlit

---

## Data and Model

### Dataset

The project utilizes a labeled dataset (**tech_resume_dataset_600.csv**) containing resume text mapped to specific job roles. This dataset is used to train and evaluate the classification model.

### Model Artifacts

* **resume_model.pkl**: Serialized machine learning model trained on the dataset
* **vectorizer.pkl**: TF-IDF vectorizer used to convert textual data into numerical features

---

## System Workflow

1. Input: User provides resume text or uploads a document
2. Preprocessing: Text is cleaned and normalized
3. Feature Engineering: TF-IDF vectorization is applied
4. Prediction: The trained model classifies the resume
5. Output: Predicted job role is displayed to the user

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/intelligent-resume-classifier.git
cd intelligent-resume-classifier
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Execution

Run the application locally using:

```bash
streamlit run app.py
```

---

## Applications

* Recruitment process automation
* Applicant Tracking System (ATS) enhancement
* Candidate filtering and categorization
* HR analytics support

---

## Future Enhancements

* Integration with advanced transformer-based models (e.g., BERT)
* Resume-job description matching and ranking system
* API-based deployment for enterprise integration
* Performance optimization and model benchmarking

---

## Author

Mariam Shifaya
Email: [mariamshifaya2025@gmail.com](mailto:mariamshifaya2025@gmail.com)
GitHub: [https://github.com/Mariamshifaya](https://github.com/Mariamshifaya)
LinkedIn: [https://www.linkedin.com/in/mariam-shifaya-k-aa0273345/](https://www.linkedin.com/in/mariam-shifaya-k-aa0273345/)

---

If this repository contributes to your work, consider acknowledging it by providing a star.
