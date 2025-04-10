
Selecting a **sample size** for making a machine learn from data is a challenging problem. Typically, there is a relationship between training data size and model performance, especially for nonlinear models. Apparently the caveat is that such a relation might not exist for some model algorithms and datasets. 

Read about power & sensitivity in (binary) classification task: https://ranjas.substack.com/p/power-analysis-24-02-02


**Sensitivity analysis** forms the basis of testing different model algorithms and their configurations (statistical heuristics such as number of classes (for classification), number of input features, number of hyperparameters) with the (train) data sizes. This helps in evaluating an algorithm (better) for a task and deciding an estimate (rough) of the training sample needed to build an optimally performing predictive model.  

<img width="493" alt="22" src="https://github.com/user-attachments/assets/b6023628-682c-45a2-a13a-39df76c62171" />



On the other hand, **power analysis** helps estimate the minimum sample size required in order to detect an effect in a statistical test.

<img width="386" alt="11" src="https://github.com/user-attachments/assets/74ca359b-2946-4f47-a4d4-6e40a11af71c" />



About determining a meaningful **effect size**: 

https://www.linkedin.com/pulse/effect-size-most-difficult-step-calculating-sample-wev0c/?trackingId=%2BxibBgXxHO2DyusWfU2E2Q%3D%3D

