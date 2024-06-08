# News-Feedback-System
The primary goal of this endeavor is to construct a machine learning model capable of accurately classifying the sentiment expressed in news articles pertaining to various ministries within India.

# Key Challenges Encountered:
Data Acquisition: No pre-existing dataset met the specific requirements of this project. Consequently, data had to be scraped from multiple news sources based on predefined criteria. This process was time-consuming and demanded careful planning and execution to ensure the dataset's relevance and comprehensiveness.

Data Labeling: The scraped data lacked sentiment labels, necessitating the creation of a labeled dataset for training the models. Initial attempts with weak labeling techniques yielded unsatisfactory accuracies, ultimately requiring manual data labeling – a labor-intensive task.

Data Preprocessing: The news headlines and articles underwent substantial preprocessing and cleaning to uphold data quality standards. This involved removing noise, handling missing values, and ensuring textual data consistency.

Class Imbalance: The sentiment labels (positive, negative, neutral) exhibited an imbalanced distribution, posing a challenge for training unbiased models. Specialized techniques were employed to mitigate this issue and prevent skewed predictions.

Model Performance and Generalization: Ensuring the developed models performed well on unseen data was crucial for reliable real-world predictions across new articles and news sources.

Feature Selection: Identifying the most informative and relevant features from the news articles was essential for developing an accurate sentiment analysis model, requiring determination of features most strongly correlated with sentiment.
# Objectives:
Data Acquisition: Scrape a comprehensive, well-curated dataset of news headlines related to different Indian ministries from various news sources.

Data Labeling: Manually label the dataset with sentiment categories (positive, negative, neutral) to establish a reliable ground truth for training and testing models.

Data Preprocessing: Clean and preprocess the dataset, addressing issues such as stop words, missing values, and inconsistencies to ensure data quality and integrity.

Model Development: Develop and train various machine learning models, including Support Vector Machines (SVM), Logistic Regression, BERT, Random Forest, and Naive Bayes, to predict sentiment based on selected features.

Model Evaluation: Evaluate model performance using appropriate metrics like accuracy, precision, recall, and F1-score, comparing models to identify the most effective one.

Model Generalization: Validate models on independent datasets and assess generalization capabilities to ensure reliability in real-world scenarios.

Data Visualization: Visualize predicted sentiments through graphs and charts for clear, intuitive representation aiding interpretation and communication of findings.

# Conclusion
The BERT model demonstrated superior performance compared to other models in this study, achieving the highest scores in accuracy, precision, and F1-score. Its advanced ability to understand the context and subtleties of language allowed it to excel in sentiment classification tasks. This suggests that BERT is highly effective for analyzing the sentiment of textual data within this domain. Specifically, the model reached an accuracy of 0.790, a precision of 0.810, a recall of 0.790, and an F1-score of 0.790.

