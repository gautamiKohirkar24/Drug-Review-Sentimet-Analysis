# Drug_Review_Sentimet_Analysis_using_LSTM


## Project Overview
This project applies Natural Language Processing (NLP) and machine learning techniques to analyze sentiments in drug reviews, uncovering insights into user experiences with different medications. With the rise of user-generated content, especially around healthcare, analyzing this data can provide invaluable feedback for healthcare practitioners, pharmaceutical companies, and regulatory bodies.

Our goal? To build a model that accurately identifies sentiment in drug reviews and highlights patterns in user perceptions of medication effectiveness and side effects.

---

## Hypothesis
We believe that user sentiments in medication reviews correlate closely with perceived drug efficacy and safety. Positive reviews typically mention effectiveness with minimal side effects, while negative reviews tend to highlight dissatisfaction due to lack of effectiveness or notable side effects. This sentiment analysis aims to reveal trends and insights in user experiences across a variety of medications.

---

## Techniques and Methodology

### Data Preprocessing
1. **Tokenization**: Splits text into words or tokens for detailed analysis.
2. **Stopword Removal**: Eliminates irrelevant words to focus on key information.
3. **Stemming & Lemmatization**: Reduces words to their root forms, aiding in consistent analysis.
4. **Word Embedding**: Transforms words into numerical vectors to capture semantic meanings.
5. **Negation Handling**: Detects and manages negations (like “not”) to correctly interpret sentiment.

### Model Development
- **Machine Learning Models**: Naive Bayes, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN).
- **Deep Learning Model**: Long Short-Term Memory (LSTM) network.
- **Unsupervised Learning**: K-means clustering to identify patterns in sentiment for specific drugs and conditions.

### Implementation Flow
1. **Data Collection**: Raw drug review data is cleaned and preprocessed.
2. **Training Models**: Both ML and DL techniques (Naive Bayes, SVM, KNN, LSTM) are trained to classify reviews as positive, neutral, or negative.
3. **Clustering Analysis**: K-means groups reviews into clusters for further analysis on recurring themes.

---

## Results and Findings

### Exploratory Data Analysis (EDA)
- **Ratings Distribution**: Positive reviews are more varied, while negative reviews cluster around specific issues.
- **Common Conditions**: Conditions like birth control, depression, and anxiety appear most frequently in reviews.
- **Keyword Analysis**: Specific words (e.g., "sleep" in insomnia reviews, "blood sugar" in diabetes reviews) highlight common concerns.

### Model Performance
- **LSTM** achieved the highest accuracy (75%), closely followed by Naive Bayes (74%), making them ideal for sentiment classification with varying needs for computational resources.

### Clustering Insights
Clustering grouped reviews by topic:
- **Cluster 0**: Acne treatment and skincare.
- **Cluster 1**: Pain relief experiences.
- **Cluster 2**: Weight management and birth control.
- **Cluster 4**: Side effects and general medication experiences.

---

## Key Takeaways
- **Naive Bayes** proved highly effective for sentiment classification with minimal resources.
- **LSTM** captured sentiment nuances better but required more resources.
- **Unsupervised clustering** provided thematic insights, helping to categorize reviews beyond simple sentiment.

---

## Conclusion
This project demonstrates how sentiment analysis in drug reviews can reveal patterns in medication effectiveness and user satisfaction. By leveraging both supervised and unsupervised learning techniques, we uncover how different treatments affect users, enhancing decision-making for healthcare professionals and organizations.

---

## Future Improvements
- **Expand Dataset**: Include broader drug categories and conditions.
- **Optimize Models**: Test additional deep learning architectures.
- **Real-Time Analysis**: Implement live data streaming for real-time sentiment insights.

---

## Repository Structure
- `data/`: Contains raw and processed drug review data.
- `notebooks/`: Jupyter notebooks for EDA and model training.
- `models/`: Saved model files for deployment.
- `scripts/`: Helper scripts for data preprocessing and training.

---

Feel free to explore the code and reach out if you have any questions or suggestions! 🚀
