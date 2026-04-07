
# Fertilizer Recommendation using Machine Learning

This project applies ensemble machine learning models to recommend optimal fertilizers based on soil and environmental conditions.

##  Overview
Efficient fertilizer use is critical for improving agricultural productivity and sustainability. This project explores how machine learning can support **data-driven fertilizer recommendations**.

##  Dataset
- Source: Kaggle
- File: `fertilizer_recommendation_dataset.csv`
- Type: Supervised multi-class classification
- Features:
  - Soil nutrients (N, P, K)
  - Environmental factors (temperature, moisture)
  - Crop type

## Models Used
- Random Forest
- XGBoost

##  Results
| Model | Accuracy | F1 Score |
|------|--------|----------|
| Random Forest | 99.52% | 99.50% |
| XGBoost | 98.39% | 98.32% |

Random Forest slightly outperformed XGBoost.

## 🔍 Model Explainability
SHAP (SHapley Additive exPlanations) was used to interpret model predictions and identify key drivers of fertilizer recommendations.

## Key Insights
- Machine learning can improve fertilizer efficiency
- Reduces environmental impact
- Supports precision agriculture practices

##  Limitations
- Dataset sourced from Kaggle
- May not fully represent real-world farming conditions
- Requires validation using local field data

## Presentation
Slides available in the `/presentation` folder.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- SHAP

## Contributors
- Memory Chibwe
- Pilirani Mogha
- Everson Hara
