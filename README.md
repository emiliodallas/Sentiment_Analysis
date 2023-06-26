# Project Name: Sentiment Analysis

## Introduction
This project, Sentiment Analysis, is a comprehensive sentiment analysis application built using various technologies and frameworks. It leverages the YouTube API, Streamlit, Flask, and Data Processing to provide insightful sentiment analysis of YouTube comments.

## Technologies Used
- **YouTube API:** The YouTube API enables the retrieval of channel information, video details, and comments from YouTube.
- **Streamlit:** Streamlit is a Python library that simplifies the development of interactive web applications for data analysis and visualization.
- **Flask:** Flask is a lightweight web framework used for building the backend API endpoints and handling HTTP requests.
- **Data Processing:** Data processing techniques are applied to clean, preprocess, and analyze the YouTube comments dataset.
- **TextBlob:** TextBlob is a Python library used for natural language processing tasks, including sentiment analysis.

## Functionalities
- **Channel Name Input:** Users can provide the name of a YouTube channel to analyze its comments' sentiment.
- **Sentiment Analysis:** The application performs sentiment analysis on the comments, categorizing them as positive, negative, or neutral.
- **Word Cloud:** The application generates a word cloud visualization based on the collected comments, providing a visual representation of the most frequent words used.
- **Sentiment Chart:** Users can view a bar chart that displays the distribution of sentiments (positive, negative, neutral) in the analyzed comments.
- **Comments Data Frame:** The application presents a tabular view of the comments dataset, allowing users to explore individual comments and associated sentiment labels.

## Docker
The project utilizes Docker for containerization, enabling easy deployment and portability across different environments. Docker allows the application and its dependencies to be packaged into containers, ensuring consistent and reproducible deployments.
