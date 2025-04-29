This Notebook corresponds to the experiment developed by Bruno Eduardo Madeira, under the
supervision of Flávio Arthur Leal Ferreira, as the final project of the specialization course in Data
Science and Artificial Intelligence from PUCRS (Brazil). The goal of the project was to analize if
the simulated data available in the 3W dataset (https://www.kaggle.com/datasets/afrniomelo/3w-dataset)
could be used in models that do not use feature engineering in order to detect problems
in oil wells. The results show evidences that the signals of sensor created by simulation in the 3W
dataset present patterns that are not presented in real ones. As a consequence, models trained
without feature engenieering must be used with caution. In our experiment we have used a Dilated
Causal Convolution Network in order to show that it makes a good classification of faults when
both training and test sets are real or simulated, but it performs bad when the model is trained
with simulated data and tested in real one. In this case, the model has not been able to detect
any defect in the oil wells. In our experiment, we just have considered the detection of RAPID
PRODUCTIVITY LOSS problems.
