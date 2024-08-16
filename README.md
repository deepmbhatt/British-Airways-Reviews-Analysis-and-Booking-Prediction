# British Airways Reviews Analysis and Booking Prediction

![image](https://github.com/user-attachments/assets/d1e47422-52f5-4f27-a697-a300fed8974e)


## Overview

This project involves the collection and analysis of customer reviews for British Airways through web scraping, sentiment analysis, and predictive modeling for booking completion. The goal is to derive insights from the reviews and predict the likelihood of booking completion using historical company data.

## Features

- **Web Scraping**: Collected reviews from online sources using BeautifulSoup.
- **Data Cleaning and Preprocessing**: Handled missing data, removed duplicates, and performed text preprocessing.
- **Sentiment Analysis**: Analyzed customer sentiments using natural language processing (NLP) techniques.
- **Topic Modeling**: Identified key themes in reviews using LDA.
- **Time-Series Analysis**: Examined sentiment trends over time.
- **Predictive Modeling**: Developed a model to predict booking completion using the company's dataset.
- **Visualization**: Presented data insights through various visualizations including word clouds, bar plots, and heatmaps.

## Installation

Clone the repository and install the required dependencies.

    git clone https://github.com/deepmbhatt/British-Airways-Reviews-Analysis-and-Booking-Prediction.git
Pip the Requirements
    
    pip install -r requirements.txt

## Usage
- **Data Scraping:** Run scrape_reviews.py to collect reviews from the specified sources.
- **Data Analysis:** Use the data_analysis.ipynb notebook to clean data, perform sentiment analysis, and visualize the results, including:
- **Sentiment Count:** The number of positive, neutral, and negative reviews.
- **Sentiment Distribution:** Distribution of sentiments across different aspects.
- **Word Clouds:** Generated word clouds for positive, negative, and neutral reviews.
- **Most Frequent Words:** Analysis of the most frequently mentioned words in the reviews.
- **Predictive Modeling:** Execute booking_prediction.py to train and evaluate the model for booking completion prediction, reporting various model accuracies.
## Dataset
- **Reviews Dataset:** Collected through web scraping.
- **Booking Dataset:** Provided by the company (details not included due to confidentiality).
## Results
- **Sentiment Analysis:** Found that:
  
![image](https://github.com/user-attachments/assets/2dc4aecd-e0b3-424a-a90f-69281bdf2818)

  neutral     568
  positive    313
  negative    119

- **Sentiment Distribution:** Visualized the distribution of sentiments across different aspects of the flight experience.
![image](https://github.com/user-attachments/assets/85e74523-6ac7-401b-aaaa-07d2cd6c9474)

- **Word Clouds:** Created word clouds highlighting the most prominent words in positive, negative, and neutral reviews.
  
![image](https://github.com/user-attachments/assets/bb58dd3b-b362-443b-9f41-f62aa9e2030f)

![image](https://github.com/user-attachments/assets/2e93518b-f5e5-4fe9-b1e6-031064c3111c)

![image](https://github.com/user-attachments/assets/a0678f2e-ce90-48ac-8200-b414279fb579)

- **Most Frequent Words:** Identified common words such as:
  
![image](https://github.com/user-attachments/assets/62964417-64ff-4656-854c-8f03091dcd21)

- **Booking Prediction:** Achieved an accuracy of:
  
![image](https://github.com/user-attachments/assets/e25137d3-2f1d-4569-bc96-2398c1ec187f)

- **Most Important Features:**
  
![image](https://github.com/user-attachments/assets/52ecfb02-9012-466b-92c0-75b4637eba72)

## Technologies Used
- Python
- BeautifulSoup
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK
- imblearn
- Jupyter Notebook
