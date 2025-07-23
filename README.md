# ChatGPT User Reviews: A Sentiment Analysis on 190,000+ Ratings

This repository presents a large-scale **sentiment analysis** of over **190,000 user reviews** on OpenAI's **ChatGPT**, with the goal of evaluating user satisfaction, uncovering common issues, and identifying key features users appreciate. The project combines natural language processing (NLP), exploratory data analysis (EDA), and visualization techniques to provide actionable insights into user feedback.

---

## Project Overview

With the widespread adoption of conversational AI systems like ChatGPT, there has been an explosion of user-generated feedback. This project analyzes that feedback using:

- **Sentiment Classification** using TextBlob  
- **Exploratory Data Analysis (EDA)**  
- **N-gram Phrase Extraction** for recurring themes  
- **Net Promoter Score (NPS)** computation

---

## Dataset

The dataset includes:
- **Review Texts**  
- **Star Ratings** (used for sentiment scoring and NPS)  
- **Timestamps** (used for trend analysis)

---

## Methodology

### 1. Data Preprocessing
- Removed duplicates and handled missing values
- Standardized data types
- Cleaned and normalized text data

### 2. Exploratory Data Analysis (EDA)
- Rating distribution and sentiment volume over time
- Identification of high-frequency review periods
- Data quality assessment

### 3. Sentiment Analysis
- Used **TextBlob** to assign polarity scores
- Labeled reviews as: **Positive**, **Neutral**, or **Negative**

### 4. N-gram Theme Extraction
- Applied **bigram** and **trigram** models
- Extracted common phrases for each sentiment category

### 5. Visualization
- Plotted sentiment distribution using **Seaborn** and **Plotly**
- Displayed temporal sentiment trends and review volume changes
- Bar charts for frequent phrases

### 6. Net Promoter Score (NPS)
- Estimated using star ratings:
  - 9–10 → Promoters
  - 7–8 → Passives
  - 0–6 → Detractors
- Computed NPS = %Promoters − %Detractors

---

## Key Findings

**Positive Sentiments:**
- Strong AI capabilities
- Ease of use and accessibility
- Helpful in academic and professional tasks

**Negative Sentiments:**
- Occasional inaccuracies or hallucinations
- Feature limitations (e.g., no memory, unclear context switches)
- Performance issues during peak usage

---

## Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **TextBlob**
- **Seaborn**, **Plotly**
- **NLTK** / **Scikit-learn** (for tokenization and n-grams)
- **Jupyter Notebooks**

---
