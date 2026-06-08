# IST707-math-misconceptions

# IST707 – Classifying Math Misconceptions with NLP

This project analyzes open-ended student math explanations and classifies them into 35 predefined misconception categories. The goal was to compare a supervised TF‑IDF + ensemble classifier against an unsupervised LDA topic model to understand both predictive performance and interpretability.

## Files in this Repository
- `IST707_FinalProject_Script.ipynb` — full analysis notebook  
- `train.csv` — labeled training data  
- `test.csv` — unlabeled test data  
- `sample_submission.csv` — sample output format for predictions  

## Tools & Technologies
Python, scikit‑learn, NLTK, TF‑IDF, Logistic Regression, Linear SVM, LDA topic modeling

## Key Findings
- The TF‑IDF hybrid ensemble achieved **89.6% accuracy** with strong F1 scores for frequent misconception categories.  
- LDA achieved **48.2% accuracy**, but produced interpretable topic clusters aligned with known student reasoning patterns.  
- Class imbalance across 35 categories significantly impacted performance, making F1 scores more meaningful than accuracy.  
- Supervised models performed best for prediction, while LDA offered insights useful for educators and EdTech applications.

## Author
Unur Gantulga  
MS in Applied Data Science, Syracuse University
