One of the main challenges facing the telecom companies is loosing their customers to competitors. Thus, having a clear understanding of the factors resulting in loosing their customer to competitors will go a long way a deveoping strategies to retain their customers. Thus, this task aim at analyzing a dataset from a telecom company containing information about their customers. The goal is to develop a predictive model to identify customers who are likely to churn, i.e., discontinue their service with the company. The tasks to accompanish this gaol are highligted below:

Exploratory Data Analysis (EDA): Perform a comprehensive exploratory analysis of the dataset. Identify and extract key insights, patterns, and trends that can inform model development and business strategies.

Data Preparation: Spliting the dataset into training and testing subsets. And making a justification for approach to splitting the data, considering factors such as data balance, temporal aspects, and generalizability of the model.

Model Development: Build a predictive model to estimate the likelihood of customer churn. Explain the rationale behind selecting the chosen algorithm, discussing its advantages and any specific considerations relevant to the dataset.

Model Evaluation: Establish and apply metrics to evaluate the performance of the predictive model. Include appropriate measures such as accuracy, precision, recall, F1 score, and ROC-AUC, and explain their relevance to the problem

The current task explored different machine learning algorithms (Nearest_Neighbors, Random_forest, Linear_SVM, Nonlinear_SVM, Gaussian_RBF_kernel, Gaussian_Pro, Stochastic_Grad, Neural_Network, Decision_Tree, Grad_Boost, Hist_Grad_Boost, and XGB_Boost') were considered for the training the train data set and their performances were evaluated using the cross-validation function with the f1-score and accuracy were used as performance metrics. The algorithm with the highest f1-score (0.82) and accuracy (0.95) scores is histogram basegriedient boost classifier, which was chosen for hyperparameter tuning using random search to determine the best parameters and estimatpr for final model selection.

The chosen algorithm was evaluated on the test set. The evaluation on test set gave f1-score, precision and recall scores of 0.83 and 0.85, 0.82 respectively.
