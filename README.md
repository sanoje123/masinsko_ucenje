**Machine learning**

└── 1/

    ├── lwlr_1.ipynb
    This notebook implements Locally Weighted Linear Regression (LWLR) from scratch using NumPy. It demonstrates the effect of different bandwidth parameters (τ) on model 
    fitting and visualizes predictions against training data.
    
    └── classifier_2.ipynb
    This notebook implements a custom Logistic Regression model from scratch, primarily using NumPy. It includes custom utilities for data standardization and splitting, and demonstrates the model's application to         multi-class classification using a one-vs-all approach. The notebook also visualizes aspects of the training process, such as the relationship between negative log-likelihood and the number of training samples.
└── 2/

    ├── svm_solution.ipynb
    This notebook implements both the primal and dual formulations of the Support Vector Machine (SVM) algorithm from scratch. It demonstrates the use of cvxopt to solve the optimization problems for both linear and       non-linear (RBF) kernels, includes 5-fold cross-validation for hyperparameter tuning, and visualizes decision boundaries, margins, and support vectors.
    
    └── trees_and_ensembles_solution.ipynb
    This notebook implements the training and evaluation of a Decision Tree model and two ensemble methods (Random Forest and Gradient Boosting) using the data_trees.csv dataset. It demonstrates the impact of     max_depth on Decision Tree performance, illustrating underfitting, overfitting, and optimal model scenarios. Additionally, it visualizes the decision boundary for the Decision Tree and feature importances derived from the Random Forest model.
