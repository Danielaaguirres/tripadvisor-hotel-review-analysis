# 🏨 TripAdvisor Hotel Review Analysis

This project analyzes over 20,000 TripAdvisor hotel reviews to uncover key factors influencing customer ratings.  
Using Natural Language Processing (NLP), sentiment analysis, and predictive modeling, we explored how customer feedback aligns with numerical ratings and what themes drive satisfaction or dissatisfaction.

> 📊 **Goal**: Identify patterns, themes, and predictors that differentiate 1-star from 5-star hotel reviews.

---

## 🔍 Key Questions

1. Do review sentiments align with user ratings?
2. Can we predict hotel ratings based on review content?
3. What recurring themes appear in positive vs. negative reviews?

---

## 🧰 Tools & Techniques

- **Python** (NLP, Scikit-learn, NLTK, Gensim, VADER)
- **Models:** Logistic Regression, Random Forest, Naïve Bayes, SVM
- **Text Preprocessing:** Tokenization, stopword removal, lowercasing
- **Visualization:** WordClouds, bar charts
- **Unsupervised Learning:** LDA Topic Modeling, K-Means Clustering

---

## 📂 Project Structure

- `/notebooks`: Jupyter notebooks with analysis and modeling
- `/images`: Visual outputs (wordclouds, graphs)
- `README.md`: Overview and documentation

---

## 📊 Dataset

- Source: [TripAdvisor Hotel Reviews on Kaggle](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews)
- 20,491 hotel reviews with associated ratings (1–5 stars)
- Variables:  
  - `Review`: free-text hotel review  
  - `Rating`: numerical satisfaction score (1 = poor, 5 = excellent)

---

## 📌 Highlights

- 📈 **Sentiment-Rating Correlation:** 0.55  
- 🧠 **Best Model:** SVM with 96.8% classification accuracy  
- 💬 **Common Complaints:** "noisy room", "dirty bathroom", "poor Wi-Fi"  
- 💙 **Positive Themes:** "great location", "friendly staff", "clean rooms"

---

## 🔬 Topic Modeling & Clustering

- **LDA:** Extracted 10 key topics in user reviews (e.g., cleanliness, staff, amenities)
- **K-Means:** Grouped reviews into 3 meaningful clusters to identify sentiment-based patterns

---

## 💡 Business Recommendations

- Improve training & cleanliness protocols
- Address common complaints (Wi-Fi, noise)
- Emphasize strong points in marketing (location, amenities)
- Use review-based modeling for early detection of service issues

---

## 🤝 Team
 **Daniela Aguirre**, Anuna Neyoti, Prisha Chawla, Shao Tung Hsu, Xiaohui Lu, Xiaoyang Cao

---

## 🗂️ Project Assets

📄 [View Project Presentation (Canva)](https://www.canva.com/design/DAGhTU1YF5A/jAA-NFkw7ohK2MsOzfdVIA/edit)

---


## 📫 Connect with me

📧 dcaguirr@uci.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/danielaaguirres)
