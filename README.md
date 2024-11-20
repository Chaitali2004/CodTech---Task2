Name: Chaitali Jain

Company: Codtech It Solutions

ID: CT6WDS1358

Domain: Data Analytics

Duration: July to August 2024

Mentor: Muzammil Ahmed


SOCIAL MEDIA SENTIMENT ANALYSIS

This project demonstrates the process of analyzing Amazon Reviewdata to understand public sentiment towards specific topics, products, or events using natural language processing (NLP) techniques. The project includes preprocessing text data, extracting sentiment scores using VADER and TextBlob, and visualizing sentiment trends over time.

Project Overview

This project involves a comprehensive analysis of social media reviews, focusing on sentiment analysis to uncover trends, distributions, and relationships within the data. The key objectives are to clean and preprocess the data, perform sentiment analysis using VADER and TextBlob, and visualize the results to gain actionable insights.

Key Objectives

•	Data Loading and Exploration: Load the dataset and display basic information.
•	Data Cleaning: Handle missing values and prepare the data for analysis.
•	Tokenization and POS Tagging: Basic NLP preprocessing using NLTK.
•	Sentiment Analysis: Perform sentiment analysis using VADER and TextBlob.
•	Visualization: Visualize the results and sentiment trends.

Dataset

 ![Screenshot 2024-07-26 184553](https://github.com/user-attachments/assets/c213f5c4-a1ed-461d-850d-d7f1b64d3b32)

Sentiment Analysis Script
1.	Import Required Libraries
2.	Set plotting style
3.	Display Basic Information

Exploratory Data Analysis
1.	Rating Analysis
   
![Screenshot 2024-07-26 185734](https://github.com/user-attachments/assets/c74227dc-2025-4a3f-88a6-75aead9cedf7)

2.	Plot review count by star rating
   
 ![Screenshot 2024-07-26 205157](https://github.com/user-attachments/assets/755d14cc-4c75-4ac8-b304-6daa67c42e47)

3.	 Basic NLTK Tokenization and Tagging

![Screenshot 2024-07-24 110040](https://github.com/user-attachments/assets/530d8ea1-8066-42ac-bd16-0ea0389770ca)
Tokenize the sample text
Part-of-Speech Tagging
Named Entity Recognition


Vizualization
Sentiment Analysis using VADER and TextBlob

1.	Plot VADER Results
   
 ![Screenshot 2024-07-26 181057](https://github.com/user-attachments/assets/cdd38e21-3d69-4df9-aa38-a04f7844bf18)

2.	 Distribution of Sentiment Scores
   
 ![Screenshot 2024-07-26 210553](https://github.com/user-attachments/assets/7c3a2415-cba0-4311-9247-9c523be362c8)

3.	Time Series Analysis

 ![Screenshot 2024-07-26 212415](https://github.com/user-attachments/assets/1a845404-e375-4396-9b8f-5e33a12e00e4)
 
4.	Word Cloud For Most Frequent Words in Reviews
   
   ![Screenshot 2024-07-26 211526](https://github.com/user-attachments/assets/3cdfa9bb-7853-4867-a64e-3b0028e8ed32)

 
5.	Comparison of Average Sentiment Scores by Rating
    
 ![Screenshot 2024-07-28 125704](https://github.com/user-attachments/assets/07a4a2be-3b9f-4b5c-ac00-ad2893790a1b)


6.	Comparison of VADER and TextBlob
    
 ![Screenshot 2024-07-26 223538](https://github.com/user-attachments/assets/f9095a87-52c1-4f6c-80e7-06f1357ffa07)


Conclusion

The successful completion of this project proves that NLP techniques can be applied to social media data, and meaningful insights about public sentiment for any topic, product, or event can be correctly elicited. This study considers both VADER Sentiment Analysis Tool and TextBlob, in a way that it manages to underline tenuous expressions of sentiment in the textual data, then drawing out an overview of its emotional tone.

1.Sentiment Distribution by Rating: Reviews with higher ratings contain more positive sentiment, while those with lower ratings have more negative sentiment. As would be expected, the compound score then needs to be higher in VADER in the former, and the polarity score higher in TextBlob in the latter. This gives evidence for the correlation between user satisfaction and expressed sentiment.

2.Sentiment Score Distribution: Generally, the sentiment score distribution is almost even, but skewed with a bias towards the positive, which may be indicative of users being more likely to share their good experiences or simply a characteristic of the dataset used.

3.Time Series Analysis: The time series analysis will demonstrate key trends and probable events that have driven public opinion. Monthly average sentiment scores help to understand the dynamics of public sentiment in response to certain incidents or changes in products or services.

4.Word Cloud: The word cloud visualization displays the most frequently occurring words in reviews, instinctively conveying dominant themes and topics that users are discussing. This enriches the sentiment analysis by placing context around the sentiment scores.

5.VADER vs. TextBlob sentiment scores: Most of the time, both tools agree on the direction for positive and negative sentiments; only minor differences, if any, creep in due to their methodology. The efficiency of VADER's rule-based approach in social media text offsets the robustness of TextBlob's machine learning across a wide range of textual data.
