# ISU-Data-Scientist-1

### About Data

This dataset provides a comprehensive view of students enrolled in various undergraduate degrees offered at a higher education institution.It includes demographic data, social-economic factors and academic performance information that can be used to analyze the possible predictors of student dropout and academic success. 

Feature column names: Marital status, Application mode, Application order,Course,Daytime/evening attendance,Previous qualification,Nationality,Mother's qualification,Father's qualification,Mother's occupation,Father's occupation,Displaced,Educational special needs,Debtor,Tuition fees up to date,
Gender,Scholarship holder,Age at enrollment,International,Curricular units 1st sem (credited),Curricular units 1st sem (enrolled),Curricular units 1st sem (evaluations),Curricular units 1st sem (approved)

Note: Selected Features Relevant Case study.

Target column name: Target

### Implementation consist of three steps :

1) Data pre processing
2) Model Selection
3) Performance Metrics

### Results 

| Model               | Accuracy  | F1 Score | Precision | Recall   | Confusion Matrix                             |
|---------------------|-----------|----------|-----------|----------|---------------------------------------------|
| Decision Tree       | 69.72     | 0.702    | 0.709     | 0.697    | [[206, 44, 34], [44, 65, 42], [41, 63, 346]] |
| Random Forest       | 79.32     | 0.784    | 0.783     | 0.793    | [[219, 26, 39], [33, 65, 53], [15, 17, 418]] |
| Logistic Regression| 78.08     | 0.766    | 0.764     | 0.781    | [[218, 24, 42], [43, 52, 56], [12, 17, 421]] |
| KNeighbors          | 69.38     | 0.684    | 0.677     | 0.694    | [[201, 35, 48], [50, 42, 59], [45, 34, 371]] |
| AdaBoost            | 77.63     | 0.769    | 0.765     | 0.776    | [[220, 32, 32], [39, 61, 51], [17, 27, 406]] |
| XGBoost             | 78.98     | 0.783    | 0.780     | 0.790    | [[221, 29, 34], [40, 67, 44], [12, 27, 411]] |
| SVM                 | 76.95     | 0.758    | 0.757     | 0.769    | [[200, 39, 45], [38, 57, 56], [8, 18, 424]]  |
