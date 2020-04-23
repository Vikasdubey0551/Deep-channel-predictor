# Deep-channel-predictor
Bi-LSTM based model to predict open ion-channels 

This repository is based on kaggle competition called 'liverpool-ion-switching' (https://www.kaggle.com/c/liverpool-ion-switching).

Jupyter notebook 'Remove_Drift+Class_Reweighing+Bi-LSTM.ipynb' contains some initial analysis and a Bi-LSTM model.

Model specifications are : 

|     Method    |   Numbers
| ------------- | ------------- |
|       LSTM    | 3  layers |
| Droput Value  | 0.5       |
| Bidirectional | 3 layers  |
| Optimizer     | adam    |
| Class reweighing | yes (μ=0.15)    |
| Sequence Length | 1000 |
|Accuracy Score | 0.969 |
|F1 Score  |    0.939|
|Precision Score | 0.939|
|Recall Score | 0.939|
| Submission Score | 0.934|
