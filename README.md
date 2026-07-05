# AI Fairness in Toxicity Classification

## Overview
This project investigates whether AI-based toxicity detection models exhibit bias toward comments referencing certain identity groups. Using the Jigsaw Unintended Bias in Toxicity Classification dataset, we developed and evaluated multiple machine learning models and used SHAP explainability to better understand model behavior and fairness.

## Project Objectives
- Evaluate bias in AI-based toxicity classification models.
- Compare the performance of Logistic Regression, Random Forest, and XGBoost.
- Assess the influence of identity-related features on predictions.
- Promote transparency and responsible AI practices through explainable machine learning.

## Dataset
**Jigsaw Unintended Bias in Toxicity Classification Dataset**
- Approximately 450,000 online comments
- Toxicity labels and identity attributes
- Demographic references including gender, race, religion, sexual orientation, and disability

## Methods
- Text preprocessing and TF-IDF vectorization
- Logistic Regression
- Random Forest
- XGBoost
- SHAP explainability analysis

## Key Results
| Model | Accuracy |
|-------|-----------|
| Logistic Regression | 0.5441 |
| Random Forest | 0.5449 |
| XGBoost | 0.5453 |

### Key Findings
- Vocabulary was the primary driver of model predictions.
- Identity attributes had relatively low influence on predictions.
- All models struggled to detect toxic comments due to class imbalance.
- Human oversight remains important for real-world moderation systems.

## Repository Contents
- `AI_Toxicity_Bias_Analysis_Report.pdf`
- `AI_Toxicity_Bias_Analysis_Presentation.pdf`

## Authors
Selena Cha, Loïs Kindomba, and Tejpreet Jaswal
