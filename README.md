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

(UPDATE IN README.md)

*EXAMPLE:*
*To accomplish this, we utilized the OpenAI API to interact with ChatGPT, and we designed a custom Python script to generate diverse prompts and collect corresponding responses. The data was then processed and analyzed using pandas, enabling us to detect patterns and biases in the AI model's outputs.*
*Engineered a Python script to generate over 1,000 prompts and elicit their responses from ChatGPT, utilizing pandas to collect the data. When prompted for solutions to this specific relevant crisis, nearly 80% of ChatGPT's responses promoted a certain worldview.*


## Data Sources <!--- do not change this line -->

*Kaggle Datasets: [https://www.kaggle.com/datasets/devdope/900k-spotify/data]*

## Technologies Used <!--- do not change this line -->

- *Python*
- *pandas*
- *HuggingFace*
- *DistilBERT*
- *Skitit-Learn*
- *Spotipy*
- *S3 Buckets*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Yves Velasquez([https://github.com/HallowsYves])*
