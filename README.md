

This proyect include a two tasks, both files can be run as they come.

The first ask produces a neural network from scratch by defining the necessary classes. By running the file, a neural network defined at the bottom is trained obtaining already around 92% of performance with 10 epochs. The hyperparameters of this NN can be changed as desired following the same structure as the one defined. At the bottom the code to finetune the hyperparameters is commented out as it take around a day to run (in my local CPU), although I include the main results of each round of finetuning.

The second task trains an LSTM using pytorch, on the energy consumption dataset included also in this repo called "office_hourly_dataset.csv". It's mainly divided in three sections: training the first LSTM (which include processing the data, defining the LSTM class and a training loop), training the feature engineered LSTM, and finetuning the hyperparameters.
