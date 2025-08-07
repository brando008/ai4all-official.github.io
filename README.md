# SoundsLike

## What is it? / How do I use it? 
SoundsLike is a music recommendation system that takes your natural language prompts to suggest songs you might like. It combines a specified song, artist, or mood to find new music with similar characteristics.

Simply enter a prompt, adjust the number of recommendations you want, and get new songs that sound like your input!

**Example:** *"Chill songs like Let It Happen by Tame Impala"* 


## Problem Statement <!--- do not change this line -->

By avoiding reliance on popularity metrics and instead using mood-based embeddings, our system promotes discovery of lesser-known songs that match user intent, helping reduce exposure bias. We designed our model to prioritize user emotion and input over trends. By carefully selecting features and removing hardcoded filters, we increased personalization and fairness, aligning with ethical AI practices.


## Key Results <!--- do not change this line -->

(UPDATE IN README.md)
Enumerate the main results of this project in a list and describe them.
1. *Cleaned over 500K song database*
2. *Vector Embedded the points into a KNN Model*
3. *Took User Input via a NER Model*
4. *Identified entities in the prompt to calculate its vecotor point*
5. *Returned the closests songs through a the KNN vector search*


## Methodologies <!--- do not change this line -->

- *NER Fine-Tuning: Trained a DistilBERT model to extract artists, songs, emotions, and genres from prompts.*
- *Prompt Embedding: Used MiniLM to convert user input into vectors.*
- *Vector Similarity Search: Matched prompts to songs using cosine similarity.*
- *Emotion Vector Mapping: Created average vectors for emotions to improve mood-based recommendations.*
- *Dataset Curation: Labeled and balanced song data from Spotify to reduce genre bias.*
- *Evaluation & Visualization: Used PCA and graphs to analyze vector quality and genre distribution.*


## Data Sources <!--- do not change this line -->

*Kaggle Datasets: [https://www.kaggle.com/datasets/devdope/900k-spotify/data]*

## Technologies Used <!--- do not change this line -->

- *Python*
- *pandas*
- *HuggingFace*
- *DistilBERT*
- *Scikit-Learn*
- *Spotipy*
- *S3 Buckets*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Yves Velasquez([https://github.com/HallowsYves])*
