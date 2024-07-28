Name: Chaitali Jain

Company: Codtech It Solutions

ID: CT6WDS1358

Domain: Data Analytics

Duration: July to August 2024

Mentor: Muzammil Ahmed


SOCIAL MEDIA SENTIMENT ANALYSIS

This project demonstrates the process of analyzing social media data to understand public sentiment towards specific topics, products, or events using natural language processing (NLP) techniques. The project includes preprocessing text data, extracting sentiment scores using VADER and TextBlob, and visualizing sentiment trends over time.

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

This project successfully demonstrates the application of natural language processing (NLP) techniques to analyze social media data and extract meaningful insights about public sentiment towards various topics, products, or events. By leveraging both the VADER sentiment analysis tool and TextBlob, the analysis captures the nuanced expressions of sentiment in textual data, providing a comprehensive understanding of the overall emotional tone.

1.	Sentiment Distribution by Rating: Higher-rated reviews show more positive sentiment, indicated by higher compound scores in VADER and higher polarity scores in TextBlob. Lower-rated reviews have more negative sentiment, highlighting the correlation between user satisfaction and expressed sentiment.
   
2.	Sentiment Score Distribution: The sentiment score distribution shows a generally balanced spread with a slight skew towards positive sentiment, which may reflect a trend where users are more inclined to share positive experiences or the specific nature of the dataset used.
   
3.	Time Series Analysis: The analysis of sentiment scores over time reveals significant trends and potential events influencing public opinion. Monthly average sentiment scores help understand the dynamics of public sentiment in response to specific events or changes in products or services.
   
4.	Word Cloud: The word cloud visualization highlights the most frequently occurring words in the reviews, offering an intuitive grasp of dominant themes and topics discussed by users. This complements the sentiment analysis by providing context to the sentiment scores.
   
5.	Comparison of VADER and TextBlob Sentiment Scores: The comparison shows that both tools generally align in detecting positive and negative sentiment, with some differences due to their distinct methodologies. VADER's rule-based approach is effective for social media text, while TextBlob's machine learning techniques offer robustness across diverse textual data.
