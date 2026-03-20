# Intelligent Resume Classifier

A production-oriented AI system designed to automate resume screening using Natural Language Processing (NLP) and Machine Learning. The application classifies resumes into relevant job roles, enabling efficient and scalable candidate shortlisting for recruitment workflows.

---

## Overview

The Intelligent Resume Classifier processes unstructured resume data and transforms it into structured insights that support faster and more accurate hiring decisions. By leveraging text preprocessing, feature engineering, and supervised learning models, the system reduces manual screening effort and improves consistency in candidate evaluation.

---

## Key Features

* Automated resume classification into predefined job roles
* Robust text preprocessing and normalization pipeline
* Feature extraction using TF-IDF vectorization
* Support for multiple resume formats (PDF, DOCX)
* Scalable and interactive web interface using Streamlit
* Session-based candidate shortlisting mechanism

---

## Technology Stack

* Python
* Natural Language Processing (NLTK)
* Scikit-learn
* Pandas, NumPy
* Streamlit

---

## System Architecture

1. Data Ingestion: Resume files are uploaded via the user interface
2. Text Extraction: Content is extracted from PDF/DOCX formats
3. Preprocessing: Tokenization, stopword removal, and text cleaning
4. Feature Engineering: TF-IDF transformation of textual data
5. Model Inference: Trained classification model predicts job roles
6. Output: Results displayed with shortlisting capability

---

## Project Structure

```
├── app.py                # Streamlit application interface
├── train_model.py       # Model training and evaluation
├── model.pkl            # Serialized trained model
├── vectorizer.pkl       # TF-IDF vectorizer
├── resumes/             # Dataset containing sample resumes
├── requirements.txt     # Project dependencies
└── README.md            # Documentation
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/intelligent-resume-classifier.git
cd intelligent-resume-classifier
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Execution

Run the Streamlit application locally:

```bash
streamlit run app.py
```

---

## Methodology

The model is trained on labeled resume datasets using a supervised learning approach. Text data is converted into numerical representations through TF-IDF vectorization, followed by classification using machine learning algorithms such as Support Vector Machines or Logistic Regression.

---

## Use Cases

* Enterprise recruitment automation
* Applicant Tracking System (ATS) enhancement
* HR analytics and candidate filtering
* Resume categorization for job portals

---

## Future Scope

* Integration with advanced NLP models (BERT, Transformers)
* Resume-job description matching and ranking
* API-based deployment for enterprise integration
* Real-time analytics dashboard

---

## Contribution Guidelines

Contributions are encouraged to improve functionality, scalability, and model performance. Please follow standard Git workflows: fork the repository, create a feature branch, and submit a pull request.

---

## Contact

Mariam Shifaya
Email: [mariamshifaya2025@gmail.com](mailto:mariamshifaya2025@gmail.com)
GitHub: [https://github.com/Mariamshifaya](https://github.com/Mariamshifaya)
LinkedIn: [https://www.linkedin.com/in/mariam-shifaya-k-aa0273345/](https://www.linkedin.com/in/mariam-shifaya-k-aa0273345/)

---

If this project is helpful, consider giving it a star.
