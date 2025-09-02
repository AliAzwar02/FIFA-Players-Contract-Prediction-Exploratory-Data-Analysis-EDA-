# FIFA Players Contract Prediction – EDA

## Overview
This project focuses on the exploratory data analysis (EDA) of FIFA players' data to identify the key factors that influence contract durations. The insights from this analysis will serve as the foundation for building predictive models in the future.

## Dataset
- Source: FIFA player dataset
- Includes features like Age, Potential, Wages, Position, and Contract details
- Preprocessing steps: missing value treatment, label encoding, feature scaling

## Key Steps
1. **Data Cleaning & Preprocessing**  
   - Removed irrelevant and redundant columns  
   - Handled missing values and inconsistent data  
   - Encoded categorical variables  

2. **Handling Imbalanced Data**  
   - Applied **SMOTETomek** (SMOTE + Tomek Links) to balance contract class distribution  

3. **Feature Analysis & Visualization**  
   - Correlation heatmaps  
   - Histograms, boxplots, and distribution analysis  

## Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)
- Imbalanced-learn (SMOTE, Tomek Links)
- Matplotlib & Seaborn for visualization

## Insights
- Identified the most influential features affecting contract duration
- Balanced the dataset for better predictive modeling

## Future Work
- Build and evaluate machine learning models for contract prediction
- Feature importance ranking and optimization
- Deploy interactive dashboard for visualization

## License
This project is licensed under the MIT License.
