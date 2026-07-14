# AI Fairness in Toxicity Classification

## Overview
This project explores fairness in AI-based toxicity classification by evaluating whether machine learning models exhibit bias toward comments referencing specific identity groups. Using the Jigsaw Unintended Bias in Toxicity Classification dataset, we built and compared multiple classification models and applied SHAP explainability to better understand feature importance and model behavior.

## Project Objectives
- Evaluate fairness in toxicity classification models.
- Compare the performance of Logistic Regression, Random Forest, and XGBoost.
- Analyze the impact of identity-related language on model predictions.
- Improve model transparency using explainable AI techniques.

## Dataset
**Jigsaw Unintended Bias in Toxicity Classification Dataset**

- ~450,000 online comments
- Binary toxicity labels
- Identity attributes including gender, race, religion, sexual orientation, and disability

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methods
- Text preprocessing
- TF-IDF vectorization
- Logistic Regression
- Random Forest
- XGBoost
- SHAP explainability analysis
- Model performance evaluation

## Results

| Model | Accuracy |
|-------|---------:|
| Logistic Regression | 54.41% |
| Random Forest | 54.49% |
| XGBoost | **54.53%** |

## Key Findings
- Vocabulary and linguistic patterns were the strongest predictors of toxicity.
- Identity-related features had relatively low influence on model predictions.
- The highly imbalanced dataset made toxicity detection challenging for all models.
- SHAP improved model interpretability by identifying the features that contributed most to predictions.
- Human oversight remains essential for responsible AI moderation systems.

## Repository Contents
- `AI_Toxicity_Fairness_Analysis.ipynb`
- `AI_Toxicity_Bias_Analysis_Report.pdf`
- `AI_Toxicity_Bias_Analysis_Presentation.pdf`

## Future Improvements
- Address class imbalance using resampling techniques or class weighting.
- Evaluate transformer-based language models such as BERT.
- Explore additional fairness metrics beyond overall accuracy.
- Compare performance across individual demographic groups.

## Authors
- Selena Cha
- Loïs Kindomba
- Tejpreet Jaswal
