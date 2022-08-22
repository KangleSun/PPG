#PPG heart rate monitoring

This is a project to estimate heart rate based on PPG signals.

#Check processed data

You could find basic information of source data in folder "eda". We processed source data to be trainable by two methods(slicing and calculating), the codes to process them are in folder "data processing", and the processed data are stored as tables, which are in folder "data".

#Models and results

This project compares the performances of Linear regression, SVM (including RBF and linear kernel function), Random forest, LSTM and Con1d, parameters of Con1d and LSTM are stored in folder ".ipynb_checkpoints". If you need to call them, just run the code "model = load_model('./.ipynb_checkpoints/Con1d.hdf5')".


