# Trajectory-prediction-RNN
Trajectory prediction is essential in applications such as autonomous driving
and traffic monitoring. In this task, we use Recurrent Neural Networks (RNNs), specifically
Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRU), to forecast the future
locations of moving taxis based on GPS data.

Data points: GPS coordinates (latitude, longitude) with timestamps for taxis
● Number of trajectories: Approximately 1200 trajectories across 50 taxis
● Average trajectory length: Between 20-100 points per trajectory
● Coordinate system: Geographic coordinates (latitude/longitude)
● Time intervals: 60 seconds between consecutive points
● Data source: Either T-Drive dataset (Beijing taxi trajectories) or synthetic data
mimicking its structure
● Context: Taxi movement patterns in urban environments
