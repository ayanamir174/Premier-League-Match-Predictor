This project uses machine learning to predict the outcome of English Premier League football matches based on historical match statistics. It explores real-world applications of classification models for sports analytics.

---

## 📄 Project Summary

👉 [View Slide Deck (PDF)](./Project%20Summary.pdf)

---

## 📊 Problem Statement
Can we predict whether a Premier League team will **win**, **lose**, or **draw** a match using past performance stats such as possession, shots, and xG?

---

## 🛠️ Tools Used
- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn, BeautifulSoup, Matplotlib, Seaborn
- **Data**: Match statistics scraped from [FBRef](https://fbref.com/)

---

## 🔁 Workflow
1. **Data Collection**:
   - Scraped match data for 1,300+ Premier League games using BeautifulSoup
2. **Feature Engineering**:
   - Created features like home/away indicator, shot accuracy, team strength
3. **Model Training**:
   - Trained multiple classifiers (Logistic Regression, SVM, Random Forest)
   - Split data into train/test using date-based split
4. **Evaluation**:
   - Used accuracy, precision, recall, F1-score, and confusion matrix

---

## ✅ Key Results
- **67.5% overall accuracy** on multi-class (Win/Draw/Loss) prediction
- **75% win/loss accuracy** when excluding draws
- **F1-score**: 0.73 for draws/losses (class 0), 0.42 for wins (class 1)
