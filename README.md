# LD-Detection-ML-Stacking
Machine Learning Stacking Model for Early Detection of Learning Difficulties

Project Overview

This project implements a Machine Learning Stacking Ensemble framework for the early detection of learning difficulties (LDs) among basic school learners in Ghana's basic education system. 
The framework combines psychometric, behavioral, and demographic data to classify learners into Low, Moderate, and High LD risk groups**, supporting teachers in making timely interventions.

Dataset

Sample Size: 2,115 learners
Period: 2021–2023 (two academic years)
Data Sources:

  Learning Disabilities Checklist (LDC)
  Conners’ Teacher Rating Scale (CTRS)
  WRAT subtests (math fluency, reading comprehension, etc.)
Features:

Psychometric (working memory, rapid naming, phonological awareness, ADHD symptoms, etc.)
Behavioral and demographic attributes

Methodology

1. Preprocessing

   * One-hot encoding for categorical variables
   * Feature scaling for numerical variables
   * Class balancing using SMOTE

2. Models Implemented

   * Random Forest (RF)
   * XGBoost
   * Support Vector Machine (SVM)
   * Logistic Regression (LR)
   * **Stacking Ensemble (Meta-learner: Logistic Regression)**

3. Evaluation Metrics

   * Accuracy
   * Precision, Recall, F1-Score
   * ROC-AUC
   * Confusion Matrix
   * Execution time


Results

Stacking Ensemble Performance:

  * Accuracy: 96%
  * Macro-average F1-Score: 94%
  * ROC-AUC: 99.7%

Key Predictors Identified:

  * Working memory
  * Rapid naming
  * Math attitude
  * ADHD symptoms
  * Vocabulary

Repository Structure

├── stacking_model.ipynb      # Jupyter Notebook with full implementation
├── requirements.txt          # Python dependencies
├── README.md                 

Installation & Usage

1. Clone the repository:

   bash
   git clone https://github.com/samuelodoom-coder/LD-Detection-ML-Stacking.git
   cd LD-Detection-ML-Stacking
 

2. Install dependencies:

   bash
   pip install -r requirements.txt


3. Run the Jupyter Notebook:

   bash
   jupyter notebook stacking_model.ipynb
   


License

This project is licensed under the MIT License.


Acknowledgements

* Teachers and learners who participated in data collection
* Research collaborators and institutions that supported this work

