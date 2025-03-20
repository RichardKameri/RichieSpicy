Title: Sentiment Analysis of  Customer Reviews Using Logistic Regression

Introduction

Kenya Airways is a leading airline in Africa and serves as Kenya's flag carrier. Since its inception in 1977, it has played a significant role in connecting Kenya to international and domestic destinations. The airline is known for its emphasis on safety, reliability, and customer experience. Understanding customer sentiment through reviews can provide actionable insights to improve service quality and maintain its strong brand reputation.

Project Overview

This project aims to conduct sentiment analysis on Kenya Airways customer reviews to extract insights into passenger experiences. By leveraging Natural Language Processing (NLP) techniques, we analyze textual feedback to classify sentiment and identify trends in customer satisfaction. This data-driven approach allows Kenya Airways to enhance service quality and refine operational strategies.

Objectives

Sentiment Classification - Develop a model that categorizes customer reviews into positive, negative, or neutral sentiments.

Feedback Analysis - Identify common themes and key aspects mentioned in customer reviews (e.g., in-flight services, customer service, booking process, seating comfort).

Model Evaluation - Compare different classification models to determine the most effective approach for sentiment analysis.

Project Methodology

Data Collection - Customer reviews were scraped from airlinequality.com and stored in a structured format.

Data Cleaning & Processing

Converted dates into standard formats

Removed stop words and performed text normalization (lemmatization, lowercasing)

Tokenized the text using NLTK

Exploratory Data Analysis (EDA)

Identified frequent words using word clouds and histograms

Visualized sentiment distributions

Extracted key topics from the reviews

Sentiment Analysis

Used Vader Sentiment Intensity Analyzer for initial sentiment classification

Implemented machine learning models for further classification

Machine Learning Models Used

We trained and evaluated multiple machine learning models to classify sentiment:

Logistic Regression: Achieved 84% accuracy, making it the best-performing model.

Decision Tree: Accuracy of 74% but prone to overfitting.

Random Forest: Accuracy of 81%, improved over Decision Trees but computationally expensive.

Support Vector Machine (SVM): Matched Logistic Regression at 84% accuracy but with higher complexity.

Key Findings & Business Insights

Punctuality Concerns - Many negative reviews highlighted delays and poor time management. Improving flight punctuality can significantly enhance customer satisfaction.

Customer Service Issues - Reports of unhelpful or rude staff indicate the need for enhanced customer service training.

Communication Gaps - Passengers expressed frustration over a lack of real-time updates regarding flight delays and cancellations. Implementing better communication strategies can mitigate this issue.

Passenger Comfort - Frequent complaints about seating space and in-flight amenities suggest an opportunity to improve customer experience, especially for long-haul flights.

Deployment & Next Steps

Model Deployment: Developed a Streamlit application for real-time sentiment analysis.

Future Enhancements:

Implement Word2Vec or BERT embeddings for improved feature representation.

Explore deep learning-based sentiment analysis models.

Continuously collect and analyze passenger feedback to enhance customer service strategies.

Conclusion

Sentiment analysis using NLP and machine learning provides valuable insights into customer experiences with Kenya Airways. By addressing key areas of concern such as punctuality, customer service, and communication, the airline can enhance overall passenger satisfaction and maintain a competitive edge in the industry
