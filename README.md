# Understanding pipelines better in machine learning and deep learning.

A machine learning pipeline is a way to codify and automate the workflow it takes to produce a machine learning model. Machine learning pipelines consist of multiple sequential steps that do everything from data extraction and preprocessing to model training and deployment.

Testing data needs to go through the same preprocessing as training data. For this iterative process, pipelines are used which can automate the entire process for both training and testing data. It ensures reusability of the model by reducing the redundant part, thereby speeding up the process. This could prove to be very effective during the production workflow.


Advantages of using Pipeline:
- Automating the workflow being iterative.
- Easier to fix bugs 
- Production Ready
- Clean code writing standards
- Helpful in iterative hyperparameter tuning and cross-validation evaluation
- 
Challenges in using Pipeline:
- Proper data cleaning
- Data Exploration and Analysis
- Efficient feature engineering

Scikit-Learn Pipeline
- The sklearn.pipeline module implements utilities to build a composite estimator, as a chain of transforms and estimators.


![pipeline-illustration](https://user-images.githubusercontent.com/42691222/153863417-94657954-0d06-48f9-a65c-1039f0156368.png)
