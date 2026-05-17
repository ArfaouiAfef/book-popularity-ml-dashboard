# 📚 Book Popularity Prediction

A complete end-to-end Machine Learning project that predicts whether a book is likely to become **Popular** or **Unpopular** based on:

- Book title
- Authors
- Categories
- Reviews
- Descriptions
- Price
- Helpful votes

The project combines:

✅ Data Cleaning  
✅ NLP & TF-IDF  
✅ Feature Engineering  
✅ Machine Learning Models  
✅ Flask Web Application  
✅ Power BI Dashboard  

---

# 🚀 Technologies Used

## Python & Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Random Forest
- Gradient Boosting
- Naive Bayes
- XGBoost

## Data Visualization
- Matplotlib
- Seaborn
- Power BI

## Web Application
- Flask
- HTML
- CSS
- Bootstrap

---

# 📊 Project Features

## Machine Learning
- Text preprocessing
- TF-IDF vectorization
- Feature engineering
- Multiple model comparison
- ROC-AUC evaluation
- F1-score analysis
- Model export with Joblib

## Power BI Dashboard
- Popular vs Unpopular analysis
- Sentiment analysis
- Category insights
- Authors analysis
- Price analysis
- Model performance comparison
- Advanced analytics

## Flask Web App
Users can:
- Enter book information
- Write review text
- Predict popularity instantly
- View prediction probabilities

  ![Uploading 5.png…]()

---

# 🧠 Machine Learning Models Compared

- Logistic Regression
- Random Forest
- Gradient Boosting
- Naive Bayes
- XGBoost

The best model was selected based on:
- F1 Weighted Score
- Accuracy
- ROC-AUC Score

---

# 📈 Dashboard Pages

1. Overview Dashboard
   <img width="1320" height="743" alt="1" src="https://github.com/user-attachments/assets/288c8b47-66bb-4665-a976-abec293b12b5" />

3. Review & Sentiment Analysis
   <img width="1321" height="743" alt="2" src="https://github.com/user-attachments/assets/294ab41f-3137-466a-b80c-2fe20013f12d" />

5. Authors & Categories Analysis
   <img width="1323" height="745" alt="3" src="https://github.com/user-attachments/assets/5dfb7bca-cbf9-48f0-bb35-2074dbdc14b5" />

7. Advanced Analytics & ML Performance
   <img width="1323" height="744" alt="4" src="https://github.com/user-attachments/assets/b65d374a-605e-4f5c-938c-cd265d3dcef0" />

---

# 📂 Project Structure

```bash
BOOK/
│
├── Models/
│   └── book_popularity_model.pkl
│
├── templates/
│   └── index.html
│
├── app.py
├── books.csv
├── models_comparison_dashboard.csv
├── powerbi_books_dashboard.csv
└── README.md
