# HR Analytics Project

## Overview

This repository contains code for an HR Analytics project using machine learning techniques. 
The project involves analyzing HR data to predict employee promotions based on various features such as education, training scores, and previous performance ratings.

## Website
https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/

## Dataset

The project uses two datasets: train_LZdllcl.csv for training the machine learning models and test_2umaH9m.csv for making predictions.

## Prerequisites

Before running the code, make sure you have the following installed:

- Python (version 3.12)
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

## Instructions

1. Clone the repository to your local machine:

      git clone https://github.com/your-username/HR-Analytics.git
   
2. Navigate to the project directory:

      cd HR-Analytics
   
3. Install the required Python libraries:

      pip install -r requirements.txt
   
4. Run the Jupyter Notebook or Python script to execute the analysis and machine learning models.

      jupyter notebook HR_Analytics.ipynb
   
5. Once the models are trained and predictions are made, the results will be saved in CSV files (Logit.csv, tree1.csv, RF.csv, gbc.csv, mul.csv, bb.csv, svc.csv).

## Files

- HR_Analytics.ipynb: Jupyter Notebook containing the code for data analysis, preprocessing, and machine learning models.
- train_LZdllcl.csv: Training dataset.
- test_2umaH9m.csv: Testing dataset.
- sample_submission_M0L0uXE: sample datase
- Logit.csv, tree1.csv, RF.csv, gbc.csv, mul.csv, bb.csv, svc.csv: Output prediction files.

## Results

The project includes the following machine learning models with their respective accuracy scores:

- Logistic Regression         :0.9317617866004962
- Decision Tree               :0.93789229
- Random Forest               :0.999744562837542
- Gradient Boosting           :0.973398044081156
- Naive Bayes (Multinomial)   :0.8943767333236023
- Naive Bayes (Gaussian)      :0.6400890380966282
- Naive Bayes (Bernoulli)     :0.8741789519778135
- Support Vector Machine (SVC):0.9210334257772588

## Conclusion

In this HR Analytics project, various machine learning models were used to predict employee promotions based on different features. 
The best-performing model was XXX with an accuracy of XX%. The analysis provides valuable insights into the factors influencing promotions within the company.

Feel free to explore the Jupyter Notebook for detailed code implementation and analysis.

## Contributors

- [Durganadh](https://github.com/Durganadh3)

## Acknowledgments

Special thanks to :Rajesh Prabhakar
https://www.linkedin.com/in/rajeshprabhakar

