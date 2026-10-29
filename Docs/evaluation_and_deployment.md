# Evaluation and Deployment Record

## Evaluation result

| Field | Value recorded in report |
|---|---|
| Evaluation component | Evaluate Recommender |
| Metric | NDCG (Normalized Discounted Cumulative Gain) |
| Recorded value | **0.9639892** |
| Pipeline and child jobs | Completed |

NDCG measures how effectively relevant items are ranked near the top of a recommendation list. The value is reported exactly as shown in the supplied project documentation.

## Model registration and endpoint

| Stage | Recorded outcome |
|---|---|
| Model registry | Version 1 registered |
| Online endpoint | Did not reach Ready; subsequently removed during cleanup |
| Compute cluster | Removed during cleanup |

The documented project demonstrates model training, evaluation, and registration, alongside an attempted deployment. It did not finish with a live recommendation API.
