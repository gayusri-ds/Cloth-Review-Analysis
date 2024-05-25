# Cloth Reviews Analysis

## Overview

This project focuses on analyzing Amazon cloth reviews to gain insights into customer sentiment and preferences. It involves data preprocessing, sentiment analysis, exploratory data analysis (EDA), and topic modeling using Latent Dirichlet Allocation (LDA). The dataset used for analysis was obtained from Kaggle and consists of Amazon cloth reviews.

## Kaggle Dataset

The dataset used in this project was sourced from Kaggle and contains Amazon cloth reviews, including information such as review text, ratings, cloth class, and various features related to cloth quality and attributes.The dataset can be accessed [https://www.kaggle.com/datasets/jocelyndumlao/consumer-review-of-clothing-product]

## Preprocessing

- Missing Values: Checked for missing values and handled them appropriately.
- Data Cleaning: Preprocessed the review text by removing stopwords and punctuation.
- Sentiment Analysis: Utilized NLTK's Vader sentiment analyzer to determine sentiment polarity scores and classify reviews as positive, negative, or neutral.

## Exploratory Data Analysis (EDA)

- Automated EDA: Generated an automated analysis report using Sweetviz to explore dataset characteristics and distributions.
- Visualization: Visualized sentiment distribution, correlation between features, and sentiment distribution across cloth classes.

## Topic Modeling

- Topic Extraction: Implemented Latent Dirichlet Allocation (LDA) to identify topics present in the review text.
- Word Clouds: Generated word clouds to visualize frequently occurring words in positive, negative, and neutral reviews.

## Conclusion

The analysis reveals that the majority of reviews are positive, indicating overall satisfaction with the products. However, there are still negative and neutral reviews, suggesting areas for improvement and the importance of ongoing customer feedback analysis.

## Dependencies

- pandas
- seaborn
- matplotlib
- nltk
- sklearn

## Usage

1. Install the required libraries listed in the Dependencies section.
2. Download the dataset from Kaggle and place it in the project directory.
3. Execute the provided Python script to preprocess the data, perform sentiment analysis, conduct EDA, and apply topic modeling.

## Files and Outputs

- data_amazon.xlsx: Input dataset containing Amazon cloth reviews.
- my_analysis_report.html: Automated exploratory data analysis report generated using Sweetviz.
- wordclouds: Folder containing word cloud images for positive, negative, and neutral reviews.
- lda_topics.txt: Text file containing the identified topics from the LDA model.
