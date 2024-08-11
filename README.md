
# Resume Categorizer

The Resume Categorizer is a machine learning application that automatically categorizes resumes based on their content. This project utilizes Natural Language Processing (NLP) techniques and machine learning algorithms, specifically K-Nearest Neighbors (KNN) and Logistic Regression, to classify resumes into predefined categories, streamlining the hiring process.

## Features

- **Resume Upload**: Users can upload multiple resumes in PDF format.
- **Resume Categorization**: Automatically categorizes resumes into predefined job categories using machine learning models.
- **Downloadable Results**: Users can download the categorization results in CSV format.
- **User-Friendly Interface**: Built using Streamlit for an interactive web-based application.

## Categories

The application can categorize resumes into the various job categories like:

- Data Science
- HR
- Advocate
- Arts
- Web Designing
- Mechanical Engineer
- Operations Manager
- Python Developer
- DevOps Engineer
- Network Security Engineer
- PMO
- Database
- Hadoop
- Blockchain
- Testing

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/7anisha/resume-categorizer.git
   cd resume-categorizer
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the necessary NLTK or spaCy models, if applicable:
   ```bash
   # Download necessary NLTK models
   python -m nltk.downloader stopwords
   ```

## Usage

1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Upload Resumes**:
   - Go to the web interface at `http://localhost:8501/`.
   - Upload resumes in PDF format.

3. **Categorize Resumes**:
   - After uploading, click the "Categorize Resumes" button.
   - The application will process the resumes and display the categorization results.

4. **Download Results**:
   - Download the categorized results as a CSV file.

## Machine Learning Model

The categorization is performed using the following machine learning models:

- **K-Nearest Neighbors (KNN) Classifier**
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Classifier (SVC)**
- **Multinomial Naive Bayes**
- **OneVsRest Classifier (using KNN)**

The model performance is evaluated using accuracy metrics, with the Logistic Regression model achieving high accuracy on test data.

## Directory Structure

```
.
├── app.py                     # Main Streamlit application
├── model.pkl                  # Trained model file
├── tfidf.pkl                  # TF-IDF vectorizer file
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── categorized_resumes/       # Directory for storing categorized resumes
```


