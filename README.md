# Topic 1: Out-of-Domain Text Classification

## How well do text classification models perform outside their training domain?

This project focuses on analyzing the robustness of text classification models to changes in the data domain (out-of-domain text classification). The goal is to investigate to what extent models trained on one type of text can correctly classify data originating from a different source.

As part of the project, a sentiment classification task (positive/negative) will be conducted.

The models will be trained on one dataset (e.g., movie reviews from the IMDb Dataset) and then tested:
* on data from the same domain (in-domain),
* on data from a different domain (out-of-domain, e.g., Amazon Reviews).

This will allow assessing the models' generalization capabilities and comparing the performance drop between in-domain and out-of-domain environments.

The results will be analyzed using metrics such as accuracy and F1-score. The final outcome of the project will be a comparison of model effectiveness and an evaluation of whether more advanced architectures handle out-of-domain data better.

## Models
The project will compare models of varying complexity:
* Logistic Regression + TF-IDF
* LSTM
* BERT
* DistilBERT

## Proposed Datasets
* **IMDb Dataset** (review, rating, pos/neg) - movie reviews
  * Link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
* **Amazon Reviews Dataset** (review title, review text, rating) - product reviews
  * Link: https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset
* **Yelp Reviews** (text, stars) - restaurant and service reviews
  * Links: 
    * https://business.yelp.com/data/resources/open-dataset/
    * https://www.kaggle.com/datasets/omkarsabnis/yelp-reviews-dataset