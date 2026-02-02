# Zodiac-Sign-Prediction-with-Machine-Learning
This project explores whether **personality traits** can be used to predict a person’s **zodiac sign** using **machine learning** techniques.  The goal is not to prove astrology scientifically, but to analyze how well personality-based survey data can be classified into zodiac categories using a data-driven approach.


## Project Overview

- **Problem Type:** Multi-class classification  
- **Number of Classes:** 12 zodiac signs  
- **Model Used:** Random Forest Classifier  
- **Dataset Size:** 48 samples  
- **Features:** 15 personality-based questions (Likert scale)

Zodiac signs are calculated **programmatically from birth dates** and used as labels.

---

##  Features Used

The model is trained using answers to the following questions:

- I enjoy being in social environments  
- Meeting new people excites me  
- I like spending time alone thinking  
- I prefer being planned and organized  
- I enjoy making spontaneous decisions  
- My emotions affect my decisions  
- Logic is more important than emotions for me  
- I am not afraid of taking risks  
- I pay attention to details  
- Seeing the big picture is more important to me  
- I enjoy taking leadership roles  
- I am sensitive to criticism  
- I can stay calm in stressful situations  
- I adapt easily to change  
- Following rules is important to me  

---

##  Technologies & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

##  Model & Methodology

- Zodiac signs are derived from **birth dates**
- Data is split into **70% training / 30% testing**
- **Random Forest Classifier** is used
- Evaluation metrics:
  - Accuracy
  - Classification Report
  - Confusion Matrix
  - Feature Importance

---

##  Results

- **Accuracy:** ~13%
- Due to:
  - Small dataset size
  - Class imbalance
  - High number of classes

This accuracy is expected and highlights the limitations of predicting zodiac signs solely based on personality traits.

---

##  Feature Importance

The most influential features include:

- Adapting easily to change  
- Enjoying leadership roles  
- Making spontaneous decisions  
- Staying calm under stress  
- Emotional influence on decision-making  

This suggests that behavioral flexibility and leadership tendencies play a stronger role in classification.

---

##  Confusion Matrix Analysis

The confusion matrix shows that:
- Some zodiac signs are occasionally predicted correctly
- Many signs are confused with each other
- Predictions tend toward dominant classes due to imbalance

---

##  Limitations

- Very small dataset
- Unequal class distribution
- Personality traits are subjective
- Zodiac signs may not have strong behavioral boundaries

---

##  Future Improvements

- Collect a larger and more balanced dataset  
- Experiment with other models (SVM, XGBoost)  
- Predict zodiac **elements** instead of individual signs  
- Try clustering instead of classification  

---

##  Medium Article

A detailed explanation of this project is available on Medium:  
👉 *(Add your Medium link here)*

---

##  Author

**Başak Biçer**  
Computer Engineering Graduate  
Interested in Machine Learning & Data Analysis  

---

⭐ If you find this project interesting, feel free to star the repository!
