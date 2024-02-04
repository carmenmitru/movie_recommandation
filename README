# Vector-Based Movie Recommendation System Using Qdrant DB

## Technology Stack

- Python
- Qdrant DB vector SB
- Libraries: torch, transformers, moviepy

## Description

Movies are recommentded based on sentiment observed by the model generated.

The first step is to create a video dataset in mp4 format. Then we create textul video embedding using video transcript and use Cosine Similarity with HTNSW algorithm.

The second step is to convert video into embedding based on transcript. The output can be used by a model on Hugging Face that can transform textul information into vector embeddings. To extract the textual information we need to extract the audio from the video. To do that we use model SpeechRecognition so we can retrive textul information as a transcript.

Using the embedding model we will convert the textul infromation into vector embeddings. The embeddings will be saved in a Qdrant database. We wil obtain similar video based on the
cosine similarity search of the Qdrant database.
