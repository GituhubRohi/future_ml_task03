# future_ml_task03
Resume Screening &amp; Candidate Ranking System (NLP + Machine Learning)

## Project Overview

Hiring teams often receive hundreds of resumes for a single job role. Manually reviewing each resume is time-consuming and inconsistent.

This project builds a **Machine Learning based Resume Screening System** that automatically:

* Processes resume text
* Extracts candidate skills
* Compares resumes with job descriptions
* Ranks candidates based on role fit
* Identifies missing skills

The system demonstrates how **Natural Language Processing (NLP)** can support real recruitment workflows.

## Key Features

* Resume text cleaning and preprocessing
* Skill extraction from resumes
* Job description analysis
* Resume-to-job similarity scoring
* Candidate ranking based on match score
* Skill gap identification
* Visualization of candidate match scores

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Machine Learning Workflow

1. **Data Collection**
   Resume dataset containing multiple job categories.

2. **Text Preprocessing**

   * Lowercasing text
   * Removing punctuation
   * Removing stopwords
   * Cleaning resume content

3. **Feature Extraction**

   * Convert text into numeric vectors using TF-IDF.

4. **Similarity Calculation**

   * Compare job description with resumes using cosine similarity.

5. **Candidate Ranking**

   * Rank resumes based on similarity scores.

6. **Skill Gap Analysis**

   * Extract candidate skills
   * Identify missing skills compared with job requirements.

## Example Output

| Candidate ID | Match Score | Skills Found   | Missing Skills   |
| ------------ | ----------- | -------------- | ---------------- |
| 1023         | 0.82        | python, pandas | deep learning    |
| 2104         | 0.79        | python, sql    | machine learning |

The system ranks resumes and highlights the skills missing for the target job role.

## Visualization

The project includes a chart showing the **top candidate match scores**, helping recruiters quickly identify strong applicants.

## Future Improvements

* Build a **Streamlit web interface for recruiters**
* Automatic resume upload (PDF parsing)
* Advanced skill extraction using spaCy
* Weighted skill scoring
* Integration with applicant tracking systems

This project is part of a Machine Learning portfolio demonstrating practical applications of NLP in recruitment and HR technology.

