# Iris Flower Classification using Decision Tree

This project demonstrates how to build, train, and evaluate a Decision Tree Classifier on the classic Iris dataset using Python and scikit-learn.  
It also includes data exploration, visualizations, model training, evaluation, and hyperparameter tuning.

---

## Dataset

- **Name**: Iris Dataset (from scikit-learn)  
- **Features**:  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target (Labels)**:  
  - Setosa  
  - Versicolor  
  - Virginica  
- **Size**: 150 samples (50 per species)

---

## Dependencies

- scikit-learn  
- pandas  
- matplotlib  
- seaborn  
- numpy

---

## Workflow

- Import Libraries – load scikit-learn, pandas, matplotlib, seaborn  
- Load Dataset – Iris dataset from sklearn.datasets  
- Explore Data – shape, info, stats, distributions  
- Visualize Features – histograms of sepal/petal features  
- Split Data – training and testing sets  
- Train Model – decision tree with criterion="gini"  
- Evaluate Model – accuracy, classification report, confusion matrix  
- Visualize Tree – using plot_tree()  
- Hyperparameter Tuning – test different max_depth values

---

## Results

- Training Accuracy: ~1.0 (perfect fit)  
- Testing Accuracy: ~0.96 (96%)  
- Best performance was achieved with max_depth = 3 or 4
