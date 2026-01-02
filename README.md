# Student Performance Prediction — Decision Tree Classifier

## Project Overview
This project predicts whether students will pass or fail based on study hours, attendance, and prior scores using a Decision Tree Classifier. 
It is aligned with **SDG 4 (Quality Education)**, aiming to provide insights for educators and learners.

## Dataset
- Source: [UCI Student Performance Dataset] 
- Features include:
  - `study_hours`: Hours studied per week
  - `attendance`: Class attendance percentage
  - `prior_scores`: Average previous grades
- Target variable:
  - `pass_fail`: 1 = Pass, 0 = Fail

## Steps / Workflow
1. **Data Inspection & Preprocessing**
   - Checked for missing values, cleaned dataset, encoded categorical variables
   - Split into training and testing sets
2. **Model Training**
   - Trained Decision Tree Classifier
   - Evaluated accuracy on test set
3. **Visualization**
   - Plotted the tree to visualize decision paths
   - Saved visualization as `Outputs/student_prediction_tree_figure.png`
4. **Evaluation**
   - Accuracy = `66%`  
   - Confusion matrix included in notebook

## How to Run
1. Clone repo:
```bash
git clone <[https://github.com/MarvellousAdedokun/student-performance-prediction]>
```
2. Install requirements:
```bash
pip install -r requirements.txt
```
3. Run the notebook in notebooks/student_performance_decision_tree.ipynb

## Key Learnings

- Understanding feature importance in predicting student outcomes
- Applying decision trees in an educational context
- Aligning data projects with SDG goals

## Future Improvements
- Expand dataset for more real-world coverage
- Compare with other models (Random Forest, XGBoost)
- Integrate feature selection for performance optimization
