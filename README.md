# Product Recommendation System

## Overview
This project implements a collaborative filtering based product recommendation system using the Amazon Electronics Reviews dataset from Stanford SNAP.

The system predicts user preferences and recommends products based on historical ratings using Singular Value Decomposition (SVD).

## Dataset
Amazon Electronics Reviews Dataset

Source:
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Electronics_5.json.gz

Original Dataset Size:
472.88 MB

Sample Used:
100,000 user-product-rating interactions

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Surprise
- Matplotlib
- Google Colab

## Methodology
1. Download and preprocess Amazon review data.
2. Extract user IDs, product IDs, and ratings.
3. Create training and testing datasets.
4. Train an SVD recommendation model.
5. Evaluate model performance using RMSE.
6. Generate personalized recommendations.

## Results

RMSE: 1.1618

Example Recommendations:

| Product ID | Predicted Rating |
|------------|-----------------|
| B008LTBITY | 5.00 |
| B004S4R5CK | 5.00 |
| B000067SMH | 5.00 |

## Skills Demonstrated
- Machine Learning
- Recommendation Systems
- Collaborative Filtering
- Data Preprocessing
- Model Evaluation
- Python Programming

## Future Improvements
- Hybrid Recommendation System
- Deep Learning Based Recommendations
- Deployment as a Web Application
