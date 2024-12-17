# Classifying Radiohead Lyrics with Super Vector Distribution

## Overview

This Jupyter notebook explores the classification of Radiohead song lyrics using techniques from Natural Language Processing (NLP). The primary focus is on utilizing word embeddings and clustering algorithms to analyze the semantic relationships within the lyrics.

## Motivation

The project stems from a thesis related to LLM-agents and NLP, inspired by the work of Mikolov et al. (2013) on word embeddings. The key questions addressed include:

- Can we use semantic representations of words for unsupervised clustering?
- What words are represented by a cluster, and do they form interpretable connections?
- Can these clusters be utilized for document classification?

## Methodology

The notebook follows the methodology proposed by Butnaru et al. (2017), which involves:

- Implementing **hierarchical clustering** to create **super word vectors**.
- Classifying documents based on the distribution of these super word vectors.
- Exploring **dimension reduction** techniques to enhance clustering quality.

## Key Findings

- Similar words tend to cluster together, indicating meaningful semantic relationships.
- Dimension reduction did not improve classification performance in this context.
- The analysis reveals relationships between super vectors and the evolution of Radiohead's lyrical themes across albums.

## Future Work

Future experiments may include:

- Testing other clustering methods
- Testing different cluster sizes to assess their impact on classification quality.
- Exploring relationships using statistical tests to filter for significant super vectors.
- Applying the approach to various music genres and artists to evaluate its broader applicability.

## Requirements

To run this notebook, ensure you have the following libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `plotly`
- `dotenv`
- `openai`

## Conclusion

This project highlights the potential of using super vectors for classifying song lyrics, while also acknowledging the limitations of traditional word embeddings in capturing the nuances of artistic expression.
