# Sentence-BERT Embeddings for Music Genre Classification

## Overview
This research explores the potential of using Sentence BERT embeddings for classifying music genres from lyrics alone. I used machine learning techniques, including random forest and multi-layer perceptron, to assess if these embeddings capture enough semantic detail to accurately determine music genres. My results show that while Sentence BERT can differentiate among genres like album rock, adult standards, alternative metal, alternative rock, and dance pop, its effectiveness is limited by the inherent complexity of music genres. This issue is exacerbated by notable similarities in lyrics across different genres. Future improvements could involve employing more complex models and adding additional variables such as the artist's background and release dates. This study provides a foundation for further development in automated music genre classification through lyrical analysis.

## About the Dataset
The dataset titled ["57,650 Spotify Songs"](https://www.kaggle.com/datasets/joebeachcapital/57651-spotify-songs/data) is from Kaggle. It contains 57,651 rows and 4 columns, named 'artist', 'song', 'link', and 'text'. All columns are of string type. It offers a comprehensive collection of Spotify song data, including the artist's name, song title, a link to the song's lyrics, and the lyrics text itself. This dataset is designed for analysis and could be used in various projects related to music, lyrics analysis, and natural language processing tasks. While the author of this dataset did not specify data extraction process (song selection criteria etc.), it's safe to assume all the data are extracted from Spotify.

More information about the dataset is available in the .pdf file (Paper).

## Code Execution
Please refer to jupyter notebook in the repository, simply clone the repository and execute all the code in the notebook. In general, the code pull data from dataset and Spotify Web API, process it, then train machine learning models using the cleaned data and provide visualizations. More code comments are available in the notebook.

## Link to Paper
Please refer to the .pdf file for the detailed research paper associated with the jupyter notebook.
