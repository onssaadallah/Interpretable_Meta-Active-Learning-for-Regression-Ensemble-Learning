# Meta-Active-Learning-for-Regression-Ensemble-Learning
Interpretable Meta-Active Learning for Regression Ensemble Learning
Active learning has been proven to efficiently decrease the required amount of labeled data for solving supervised learning tasks and reducing thus data annotation costs. While ensemble-based active learning schemes have been widely studied for classification problems, few works investigated their usability for regression tasks.
In this paper, we propose a novel active learning method for regression ensemble learning using meta-learning. Meta-learning is exploited to predict continuous utility values of candidate unlabelled data points. Sample selection is devised to take into account both ensemble accuracy and diversity at the same time.
In addition, the ensemble model and the meta-learner share the same features. This enables the provision of a suitable explanation for the reason behind selecting a specific sample during the active learning procedure to improve the ensemble performance.  
Empirical testing of the method is performed, assessing both its performance and scalability using several regression real-world datasets. Achieved results show its competitiveness in comparison to state-of-the-art approaches for active learning and ensemble learning for regression.
## Meta-Active-Learning-for-Regression-Ensemble-Learning Pipeline
![Beige Colorful Minimal Flowchart Infographic Graph (2)](https://github.com/onssaadallah/Meta-Active-Learning-for-Regression-Ensemble-Learning/assets/44116045/bf816c65-d1b4-41c0-a2e4-f46316259739)

1.SBTD: Sub Trained Labelled Data
2.SBUD: Sub update Labelled Data

3.SBED: Sub-Evaluation Data
4.ULTD: Unlabeled Training data

## Repository filefiles
1- Regression_Ensemble_Learning.ipynb is the notebook that follows this pipeline.
2- Datasets_data .json defines the regression datasets that we used in the experiments
3- Dataset.csv contains the CSV files of datasets.
4- METAL_EXP shows the outputs plots of features importance of the main model before and after adding the top k relevant data points from unlabeled train data in each number of iterations (numbers of iterations are 5,10,20 and 50).

## Tools and Frameworks Used
- [matplotlib] cross-platform, data visualization and graphical plotting library for Python
- [Keras] Deep Learning Library
- [NumPy] Scientific numerical calculations library
- [pandas]  Python library used for working with data sets
- [Scikit-learn] Machine learning algorithms tools
