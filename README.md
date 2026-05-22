# Nintendo Switch 2 YouTube Sentiment and Emotion Analysis

Semi-supervised sentiment and emotion analysis on Nintendo Switch 2's YouTube reactions, using Transformer embeddings and clustering.

## Project Overview

This project analyzes YouTube comments related to Nintendo Switch 2 announcements, focusing on sentiment, emotion detection, Transformer-based embeddings, and clustering.

The analysis compares reactions from two different YouTube videos and uses several NLP models to identify patterns in user responses.

## Methods

The notebook includes:

- YouTube comments preprocessing and cleaning
- Sentiment analysis with Transformer-based models
- Emotion classification
- Embedding extraction from Transformer models
- K-Means clustering
- Cross-model comparison using clustering evaluation metrics

## Reproducibility Note

This project was originally developed in Google Colab using YouTube comments collected through the YouTube Data API.

The API key is not included for security reasons, and the original raw datasets may no longer be available. For this reason, the notebook may not be fully executable from scratch without the original CSV files and generated embedding files.

The notebook is provided primarily as a documented analysis workflow, with preserved outputs where available.

## Important Notes

- The YouTube API extraction code is included for methodological transparency.
- API credentials are not included.
- Some intermediate files, such as generated embeddings, may be missing if they were not uploaded to the repository.
- The notebook should be interpreted as an analysis report and workflow documentation rather than a fully reproducible pipeline.

## Repository Content

NLP_project.ipynb   # Main notebook
README.md          # Project description and reproducibility notes

## Technologies Used
Python
Google Colab
pandas
NumPy
scikit-learn
PyTorch
Hugging Face Transformers
Matplotlib
Seaborn
