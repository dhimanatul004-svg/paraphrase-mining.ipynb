# Paraphrase Mining Using Sentence Transformers

## Overview

This project demonstrates **Paraphrase Mining** using the **Sentence-Transformers** library. It identifies sentences with similar meanings by generating sentence embeddings and comparing their semantic similarity. The notebook also includes an example of **outlier sentence detection** by finding the sentence that is least similar to the rest of the corpus.

## Features

* Generate sentence embeddings using pretrained Sentence-Transformer models.
* Perform paraphrase mining on a collection of sentences.
* Calculate semantic similarity between sentences.
* Detect the most semantically different (outlier) sentence in a dataset.
* Compare multiple pretrained embedding models.

## Technologies Used

* Python
* Sentence-Transformers
* PyTorch
* TensorFlow/Keras

## Models Used

* `all-MiniLM-L6-v2`
* `distiluse-base-multilingual-cased-v1`

## Workflow

1. Install and import the required libraries.
2. Load a pretrained Sentence-Transformer model.
3. Encode sentences into vector embeddings.
4. Perform paraphrase mining to identify similar sentence pairs.
5. Compute cosine similarity between sentence embeddings.
6. Detect the outlier sentence based on average similarity scores.

## Learning Outcomes

This project provides hands-on experience with:

* Semantic Text Similarity (STS)
* Sentence Embeddings
* Paraphrase Detection
* Cosine Similarity
* Natural Language Processing (NLP)

## Future Improvements

* Visualize similarity scores using heatmaps.
* Support larger datasets.
* Build a simple web interface for paraphrase detection.
* Experiment with additional transformer models.
