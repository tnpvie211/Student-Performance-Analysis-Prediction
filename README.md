# Project Overview
This project analyzes large-scale student learning interaction data to predict academic performance and learning outcomes over time. Using machine learning and knowledge tracing techniques, the model identifies learning patterns, engagement signals, and performance drivers to support data-driven educational interventions and personalized learning strategies.
For a full report, visit: https://drive.google.com/file/d/1ZbjQq2LTt_mNnOsfnK3xHrIf94QlX2T3/view?usp=sharing

## Objectives
- Understand student learning behavior through interaction and performance data
- Predict future learning outcomes and mastery levels
- Identify key behavioral and content-related factors influencing student success
- Support early intervention and adaptive learning recommendations

## Data Description
- 1M+ students, 100M+ learning interactions
- Time-series data including:
  - Student–question interactions
  - Correctness and attempt history
  - Learning progression across skills/topics

## Tools & Technologies
- Python (pandas, NumPy)
- Machine Learning & Modeling: LightGBM, XGBoost, Keras (Deep Learning), Knowledge Tracing techniques
- Visualization & Analysis: Matplotlib, Seaborn

## Methodology & Approach
1. Data Processing & Feature Engineering
2. Exploratory Data Analysis (EDA)
  - Analyzed learning progression and performance distributions
  - Identified patterns in student engagement and outcome variability
  - Examined difficulty levels and skill mastery dynamics
3. Predictive Modeling
  - Implemented and compared multiple modeling approaches:
    - Knowledge Tracing models for temporal learning prediction
    - Regression and classification techniques for outcome prediction
4. Model Evaluation
  - Performance measured using accuracy and error-based metrics
  - Model comparison to assess trade-offs between interpretability and predictive power
  - Optimization for scalability and training efficiency on large datasets

## Key Findings & Insights
- Historical performance and recent interactions are strong predictors of future outcomes
- Learning progression is non-linear and varies significantly across students
- Temporal models outperform static models in predicting mastery
- Engagement frequency and consistency strongly correlate with success
- Certain skills exhibit higher learning decay, requiring targeted reinforcement

## Business & Educational Impact
- Enables early identification of at-risk students
- Supports personalized learning pathways
- Improves curriculum design through skill-level insights
- Scales learning analytics for large educational platforms

## Suggestions & Future Plans
- Incorporate real-time prediction pipelines
- Extend models to multi-skill and cross-course learning
- Deploy model outputs into learning management systems (LMS)
- Explore explainability techniques for instructor-facing insights
