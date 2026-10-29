# Methodology

## Data preparation

The recorded Azure ML Designer pipeline includes **Join Data**, **Execute Python Script**, and **Remove Duplicate Rows** components. These prepare a consolidated dataset for modelling.

## Train/test split

The pipeline uses **Split Data** to create training and test subsets.

## Model training and scoring

The **Train SVD Recommender** component learns patterns from user–movie ratings. **Score SVD Recommender** generates predicted ratings or recommendation scores on the records passed to it.

## Evaluation

The **Evaluate Recommender** component measures the quality of the recommendation rankings. The report records an NDCG score of **0.9639892**. NDCG rewards relevant items that appear nearer the top of a ranked recommendation list.

## Registration and deployment

The report records model Version 1 in the Azure ML model registry. An online endpoint was attempted, but it did not reach Ready and was later removed during cleanup.
