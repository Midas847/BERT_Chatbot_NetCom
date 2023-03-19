# BERT Product Rating Predictor

## Overview

- **Year:** 2023
- **Language(s):** Python, R
- **Discipline(s):** Machine Learning, Natural Language Processing (NLP)
- **Keywords:** `Reviews`, `BERT`, `Classification`, `Clustering`, `Machine Learning`, `NLP`

## Description

The _BERT Product Rating Predictor_ is a natural language processing model based on the _Bidirectional Encoder Representations from Transformers (BERT)_ model developed to predict star ratings for textual product reviews. It was created by fine-tuning the BERT model, training it with a custom dataset containing 195,765 reviews gathered from Amazon’s electronic products section. From this model, a _k_-means clustering model was then employed to explore interesting relationships between the predicted star ratings and their associated reviews.

This model was then used as part of a research project titled _Using the BERT Model to Predict and Analyze Star Ratings from Reviews in the given dataset_.

### Team Members

- Atharv Mahesh Gote
- Priyanshi Gupta
- Apoorv Gupta
- Saswata Ghosh

## Build Instructions

1. Download the `bert-product-rating-predictor.ipynb` Jupyter notebook.
2. Download the [pretrained model](https://bit.ly/2VENkSB).
3. In the notebook, set up the pretrained model by adding the pretrained model to the same directory and including it as the `file_path`. More instructions can be found in the notebook.
4. Reach the end of the notebook and define a custom `review`.
5. Run the notebook. The last block will contain your predicted star rating.
