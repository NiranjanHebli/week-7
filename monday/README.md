# Day 37 (Monday) -  TF-IDF from Scratch

## Description

This task computes TF-IDF from scratch for a given corpus of text documents. The corpus is a subset of the Amazon product review dataset, filtered to only include reviews from the category "Electronics". The task tokenizes the text documents, computes raw term frequencies (TF), computes smooth inverse document frequencies (IDF), and assembles a TF-IDF matrix using the computed TF and IDF values.

## Key Learnings

- Tokenization is an important preprocessing step in text analysis.
- TF-IDF is a useful representation for text documents in many NLP tasks.
- Smooth IDF is a sklearn-compatible IDF formula that uses logarithmic normalization to prevent division by zero.
- TF-IDF matrix can be used as input features for many NLP models.

### Steps to Run

1. Open a terminal and navigate to the directory containing this README file.
2. Run the command `jupyter notebook` to start the Jupyter notebook server.
3. Open a web browser and navigate to `http://localhost:8888` to access the Jupyter notebook interface.
4. Select the `tf_idf_from_scratch.ipynb` notebook and click the "Run" button to execute the code in each cell in order.
5. Observe the output of each cell to verify that the code is working correctly.

## File:- 

### [`tf_idf_from_scratch.ipynb`](./tf_idf_from_scratch.ipynb)

