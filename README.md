# Calibration curve

- It transforms predicted probabilities into 'realistic/real' probabilities of events.

- We can analyze the calibration curve to understand the interpretability of the model rather than only using score/accuracy measures(F1,Precision,Recall).

- Use CalibratedClassifierCV to calibrate a model using specific methods: sigmoid and isotonic operators to module according to the relationship between predicted and real values.

- We can select a model based on how it behaves according to the expected model (perfect calibration), and not necessarily only rely on accuracy predicted measures.

  

