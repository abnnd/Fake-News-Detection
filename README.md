# Fake News Detection Using NLP

This project uses Natural Language Processing and Machine Learning to detect fake news articles.

---

## 🔍 Problem Statement
Fake news has emerged as a significant threat to credible journalism and informed public discourse. This project aims to build an automated system to classify news as **real** or **fake** based on their textual content.

---

## 📁 Project Structure
```
├── fixedcode.ipynb             # Final working notebook
├── Untitled (1).ipynb          # Early version using Random Forest
├── Project Details.docx        # Problem definition and scope
├── Deliverables/               # Action Plan, Reports, EDA, Model summary
├── README.md                   # GitHub documentation
```

---

## 🛠️ Technologies Used
- Python (Pandas, NumPy)
- NLP (NLTK, WordNetLemmatizer)
- TF-IDF Vectorization
- Machine Learning (Scikit-learn: Logistic Regression, Random Forest)
- Visualization (Seaborn, WordCloud)
- Jupyter Notebook

---

## 📊 Dataset
- **Source**: Kaggle Fake and Real News Dataset
- **Attributes**: `title`, `text`, `label`
- **Classes**: Fake (0), Real (1)

---

## ⚙️ Key Steps
1. Data Cleaning and Preprocessing (lowercasing, removing stopwords, lemmatization)
2. Exploratory Data Analysis (class distribution, word clouds)
3. Feature Extraction using TF-IDF
4. Model Building:
   - ❌ Initial: Random Forest (overfitting, poor recall)
   - ✅ Final: Logistic Regression (balanced F1-score)
5. Evaluation with Confusion Matrix, Precision, Recall, F1-score

---

## 📈 Results
- Final Model: **Logistic Regression**
- Accuracy: ~92%
- F1-Score: ~91% (macro)

---

## 📎 How to Run
```bash
1. Clone this repo
2. Open `fixedcode.ipynb` in Jupyter Notebook
3. Run all cells sequentially
```

