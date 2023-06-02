# Traffic-Forecasting-using-Bi-LSTM
This is a submission for the Traffic Forecasting challenge posted in the link
https://trbaiac.web.app/challenge

It is a timeseries/forecasting model to predict the traffic states of the various segments 
in the Greater Seattle Area based on the data collected through loop detectors deployed.

### Datasets
The datasets are in the form of pickles that can be downloaded from the page of the challenges
in the above link.
The train dataset is preprocessed into a dataframe with the timestamps as indices and all the 
87 segments enlisted under the Loop Detector data as the Columns.

The train data contains the traffic states of the 87 segments of the Greater Seatlle Area ranging from
Jan. 1st, 2020 to May 31th, 2020 with 15-minute time interval

The testing data contains 15 test cases with each of 36 previous time steps ranging from the dates
Jun 1st 2020 to Jun 16th 2020

### Models
The general Deep Learning Models used for Forecasting kind of problems are variants of RNN like LSTM and 
GRU.

The code inluded here is a Bi-LSTM model which is an extension of LSTM.
