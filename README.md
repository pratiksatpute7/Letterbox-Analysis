# Movie Review - NLP Analysis

## Overview
This project focuses on analyzing movie reviews using Natural Language Processing (NLP) techniques. The goal is to extract insights from textual data, identifying trends like sentiment, sarcasm, and confidence levels in sarcasm detection across different film genres over time.

## Features
- **Sentiment Analysis**: Evaluate the general sentiment (positive, negative, neutral) of movie reviews.
- **Sarcasm Detection**: Identify and analyze sarcastic comments in reviews, which can offer deeper insights into viewer perceptions.
- **Trend Analysis**: Track how sentiments and sarcasm trends evolve over different release years.
- **Confidence Level Analysis**: Measure the confidence levels of sarcasm detection, which helps in understanding the effectiveness of the sarcasm detection model across genres.

## Dataset
The dataset used in this project contains various fields from movie reviews, including text content, sentiment scores, sarcasm flags, genre information, and more. This data is used to perform comprehensive textual analysis and visualization.

## Visualizations
The notebook includes several visualizations:
- Bar charts and line graphs to display sentiments and sarcasm frequency.
- Heatmaps to represent confidence levels of sarcasm detection across genres.

## Installation
To run this notebook:
1. Ensure you have Jupyter Notebook installed, or use Jupyter Lab.
2. Install the required Python packages:
   ```bash
   pip install pandas matplotlib seaborn nltk transformers torch scikit-learn

