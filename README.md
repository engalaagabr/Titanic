# Titanic Survival Prediction

This repository documents my end-to-end approach to the **Kaggle Titanic: Machine Learning from Disaster** challenge.  
The goal is to build a model that predicts whether a passenger survived the Titanic sinking based on features like age, gender, class, and ticket information.

I performed **data exploration**, **feature engineering**, and **model building** using Python’s scientific stack.  
Multiple algorithms were compared and tuned, and the best model was submitted to Kaggle, achieving a public score of **0.7799**.

---

##  What’s Inside

- **Exploratory Data Analysis (EDA):**
  - Visualizing distributions of Age, Fare, Passenger Class, Sex, Embarked, etc. and their relationships with survival.

- **Feature Engineering:**
  - Extracting passenger titles (Mr, Mrs, Miss…) from the Name field.
  - Combining `SibSp` and `Parch` into family size features.
  - Creating “IsAlone” flags, Fare and Age bins, and encoding categorical variables.

- **Modeling:**
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Random Forest
  - Voting Classifier ensemble

- **Evaluation & Submission:**
  - Models were evaluated with accuracy, confusion matrices, and classification reports.
  - The final notebook generates a Kaggle-ready `submission.csv` file.

---

## Results

- **Best Kaggle Public Score:** 0.7799  
- Random Forest and ensemble models performed better than baseline logistic regression.  
- Feature engineering and model comparison helped improve accuracy from ~0.76 to ~0.78+.  

---

## Tech Stack

Python • pandas • NumPy • Matplotlib/Seaborn • scikit-learn

---

## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/engalaagabr/Titanic.git
   cd Titanic
