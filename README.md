# Linear_Reg_ForCar_price_prediction.repo:
- A linear Reg- model for predicting the price of second hand car.
# About :
- A linear reg-model of following structure :
-  InputLayer(input_shape = (8,)),
    normalizer,
    Dense(128, activation = "relu"),
    Dense(128, activation = "relu"),
    Dense(128, activation = "relu"),
    Dense(1),
- DataSet Taken from Kaggle <a href = https://www.kaggle.com/datasets/mayankpatel14/second-hand-used-cars-data-set-linear-regression>Second Hand Car Dataset.</a>.
- Looses = loss: 36433.3633 - root_mean_squared_error: 46644.2148 - val_loss: 37564.8867 - val_root_mean_squared_error: 47129.3828
