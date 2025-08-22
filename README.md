

### **US Congress Voting Classification Using Machine Learning**  

- **Objective**: Implemented **supervised machine learning** techniques to classify U.S. congresspersons as **Democrat (0) or Republican (1)** based on **voting records** from the U.S. Congressional Voting Records dataset.  

- **Technologies & Libraries**: Utilized **Python**, **pandas**, **numpy**, **scikit-learn**, **matplotlib**, and **seaborn** for data preprocessing, model training, evaluation, and visualization.  

- **Methods**:  
  - **Data Preprocessing**: Handled missing values using **mode imputation**, applied **label encoding** to categorical features, and split the dataset into **train (70%) and test (30%)** sets.  
  - **Classifiers Used**: Implemented **Logistic Regression**, **Naive Bayes (CategoricalNB)**, and **Decision Tree Classifier** to predict political affiliation.  
  - **Model Evaluation**: Assessed performance using **accuracy, precision, recall, F1-score**, and **confusion matrices**. Conducted **5-fold cross-validation** for robustness.  

- **Results & Achievements**:  
  - **Logistic Regression** achieved the highest accuracy (**96.18%**), followed by **Decision Tree (94.66%)** and **Naive Bayes (92.37%)**.  
  - Cross-validation confirmed **Logistic Regression as the most reliable classifier**.  
  - Visualized classifier performance using **bar charts, confusion matrices, and comparison heatmaps**

