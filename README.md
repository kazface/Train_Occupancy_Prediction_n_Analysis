# Train_Occupancy_Prediction_n_Analysis
Analysis and Prediction of Train Occupancy using LSTM

# Data

DepartureDate departure date
StationName departure station
IndexNumber the order of the station along the route
Count the number of people on the train at the time of departure
TicketsSold sold tickets
Capacity capacity
CarClass wagon type (reserved seat, coupe, luxury)
TrainNumber - train number
Occupancy occupancy 0 to 1
OccupancyPercents, occupancy from 0 to 100
WagonNumber, wagon number
TrainRoute, route
NumberOfStations, number of stations
IsBad, a sign of incorrectly filled data
IsPrediction, whether it is a forecast or a fact (use for estimation)

# Algorithm

A recurrent neural network LSTM is used to predict time series.
LSTM (Long Term Short Term Memory) is a type of recurrent neural network capable of studying long term dependencies.

