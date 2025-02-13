
Selecting a **sample size** for machine learning is a challenging open problem. Typically, there is a relationship between training data size and model performance, especially for nonlinear models. Apparently the caveat is that such a relation might not exist for some model algorithms and datasets. 

A **sensitivity analysis** forms the basis of testing different model algorithms and their configurations (statistical heuristics such as number of classes (for classification), number of input features, number of hyperparameters) with the data sizes used to train them. This helps in evaluating an algorithm (better) for a task and deciding an estimate (rough) of the training data size needed to build an optimally performing predictive model.  

<img width="341" alt="1" src="https://github.com/user-attachments/assets/e1ba4eb6-5330-44f4-aaa3-ec492621334d">


On the other hand, power analysis helps estimate the minimum sample size required in order to detect an effect in a statistical test.

Analysing power and sensitivity with examples: https://github.com/ranja-sarkar/power-sensitivity/blob/main/notebooks/sensitivity_analysis.ipynb

A good read on the **effectiveness of data in deep learning**:
https://arxiv.org/pdf/1707.02968


