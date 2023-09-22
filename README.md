# Interpretable-Meta-Active-Learning-for-Regression-Ensemble-Learning
Active learning is a technique that can greatly reduce the amount of labeled data required for supervised learning tasks, thereby decreasing data annotation costs. While ensemble-based active learning schemes have been widely studied for classification problems, few investigations have been conducted on their usability for regression tasks.

This paper proposes a novel method for active learning in regression ensemble learning that uses meta-learning to predict continuous utility values of candidate unlabelled data points. The method takes into account both ensemble accuracy and diversity during sample selection to enhance performance. Additionally, the ensemble model and the meta-learner share the same features, which enables the provision of a suitable explanation for the reason behind selecting a specific sample during the active learning procedure to improve ensemble performance.

Several real-world regression datasets were used to test the method empirically to assess its performance and scalability. The achieved results show the competitiveness of our method with state-of-the-art approaches for active learning and ensemble learning in regression.
## Meta-Active-Learning-for-Regression-Ensemble-Learning Pipeline
The METAL pipeline is composed of 2 main parts:
META M and AL process



![5](https://github.com/onssaadallah/Meta-Active-Learning-for-Regression-Ensemble-Learning/assets/44116045/3c7b322d-35a0-4099-84eb-cd4e876ba805)
![2](https://github.com/onssaadallah/Meta-Active-Learning-for-Regression-Ensemble-Learning/assets/44116045/ba9f456e-997e-4258-814b-59fc8fb8e88d)





## Repository files
1- Regression_Ensemble_Learning.ipynb is the notebook that follows this pipeline.
2- Datasets_data .json defines the regression datasets that we used in the experiments
3- Dataset.csv contains the CSV files of datasets.
4- METAL_EXP shows the output plots of features importance of the primary model before and after adding the top k relevant data points from unlabeled train data in each number of iterations (numbers of iterations are 5,10,20 and 50).

## Tools and Frameworks Used
- [matplotlib] cross-platform, data visualization and graphical plotting library for Python
- [Keras] Deep Learning Library
- [NumPy] Scientific numerical calculations library
- [pandas]  Python library used for working with data sets
- [Scikit-learn] Machine learning algorithms tools
