# Electricity Forecasting Interpretability
<p align="justify">
This repository contains the code of my master's thesis with the title "Interpretability of Machine Learning Methods: the Case of Buildings’ Energy Consumptions Prediction". 
</p>
## Abstract
<p align="justify">
It is important in the energy management of a building that predictions made by neural networks (referred to as black boxes) are supported by consistent explanations from the model itself. The building could easily face costly, and unacceptable consequences if there is a critical over-or under-supply of energy due to erroneous forecasts given by a dedicated machine learning model. Moreover, the manager can know why the forecasting model has come up with its predictions in case of abnormal predictions.

Although the existing interpretability methods provide helpful information, more is needed for energy managers. Specifically, managers usually need to be provided with an explanation for a certain period in the forecasted time series of energy consumption. This lack of explanation is covered in this work by proposing a novel interpretability use case: explaining the pattern of a period's forecast by searching backward in the predicted electricity consumption time series to find a period with the most similar pattern. The explanation can be verified by the analogy of the observed target and feature variables in the two periods.

In order to complete the explanation for the electricity consumption forecast, three more interpretability use cases are presented: determining the importance of each exogenous variable in the prediction problem and identifying important regime shifts and persistent patterns in the forecasted electricity consumption.

In order to implement the interpretability use-cases, two state-of-the-art interpretable and accurate forecasting models are employed, Temporal Fusion Transformers (TFT) and NeuralProphet. With these two different models, the interpretability use cases are addressed with two different approaches: analyzing the distribution of attention weights with TFT and decomposing the forecast into interpretable components with NeuralProphet.

The results of applying the mentioned interpretability use cases on two real-world datasets using the models mentioned above are shown in a scientifc paper that soon will be submitted to EIR journal.
</p>