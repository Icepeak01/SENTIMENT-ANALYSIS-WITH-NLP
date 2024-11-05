# SENTIMENT ANALYSIS USING NLP (SUPERVISED LEARNING)
This repository contains an advanced implementation of sentiment analysis, building on the foundational market-basket analysis with the Apriori algorithm. Leveraging insights from previous customer segmentation, this project aims to further enhance customer engagement strategies by interpreting sentiment from customer feedback using supervised learning models.


![WhatsApp Image 2024-11-05 at 2 43 19 PM](https://github.com/user-attachments/assets/4b266b54-46de-4c0e-9ac9-558b331832b8)

# Introduction
After identifying premium customer segments through customer segmentation and market-basket analysis, the focus shifted to sentiment analysis to understand and enhance customer interactions and satisfaction. This project uses various supervised learning techniques to classify customer sentiments, enabling the business to tailor communications and promotions effectively.

# Business Problem
Building on previous projects, the need arose to automate the interpretation of voluminous customer feedback, which was previously managed manually. The aim is to employ sentiment analysis to:

 - Streamline customer feedback analysis.
 - Enhance the responsiveness of customer service teams.
 - Identify critical sentiments that can affect customer satisfaction and loyalty.

## Challenges and Solutions
Data Handling Issues
- Sparse Data Handling: The models used in this project initially could not process the sparse matrices generated from text vectorization directly.
- Solution: Implemented a custom transformer within the pipeline to convert sparse matrices to dense format, ensuring compatibility with all models.

# Data Preprocessing
 - Streamlining Preprocessing: Leveraging custom transformers and function transformers to automate the preprocessing steps.
 - Application: Integrated steps like stemming, lemmatization, and creation of bag of words into seamless preprocessing pipelines.

# Key Learnings
 - Custom Transformers: Learned to create and integrate custom transformers for preprocessing in machine learning pipelines, enhancing model compatibility and preprocessing efficiency.
 - Text Preprocessing Techniques: Developed a deeper understanding of text manipulation techniques including tokenization, stemming, and lemmatization, critical for natural language processing.
 - Pipeline Integration: Utilized Scikit-learn pipelines to streamline the process from raw data to model input, improving code modularity and maintainability.

# Model Implementation
 - Model Exploration: Evaluated multiple classification models including Logistic Regression, Voting Classifier, Random Forest, and GaussianNB. The Voting Classifier emerged as the best model based on its superior generalization performance.
 - Performance Metrics: Employed confusion matrices and other metrics to evaluate model performance, ensuring robust sentiment analysis.

# Best Model Results
- The Voting Classifier, which combines multiple model predictions to improve accuracy, yielded the highest scores in our evaluations, confirming its effectiveness in classifying complex sentiment data accurately.

# Conclusion
The sentiment analysis implemented in this project significantly enhances the company's ability to engage with and understand their customers by automating the processing of customer feedback. This, combined with insights from previous market-basket and segmentation analyses, allows the company to craft highly targeted marketing campaigns and improve overall customer satisfaction.

For a detailed walkthrough of the implementations, please refer to the Jupyter notebook included in this repository.











![thank you](https://github.com/user-attachments/assets/6e79b3db-647f-4217-a4cc-3c710b54d9fc)
