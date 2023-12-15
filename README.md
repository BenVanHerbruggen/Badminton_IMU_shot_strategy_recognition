# Badminton_IMU_shot_strategy_recognition
Dataset for shot and strategy recognition of badminton players. 

This dataset comprises inertial measurement unit (IMU) data collected from six experienced players. These players perform 13 distinct badminton shots, including forehand serve, backhand serve, forehand clear, backhand clear, forehand smash, forehand drop, backhand drop, forehand lob, backhand lob, forehand net drop, backhand net drop, dab, and drive. When no specific shot is executed, the data is labeled as a fourteenth class. Additionally, the dataset includes four badminton strategies: forcing the opponent to move along the long diagonals, to other corners, to the same corner with deviation, or playing to the middle. Each strategy has various variants, exerting pressure on the opponent.

IMU data is collected at the players' racket and wrist, sampled at 100 Hz using Axivity AX6 devices. Each device provides 3 accelerometer and 3 gyroscope axes, resulting in 12 values per datapoint.

In conjunction with the IMU data, the dataset records the position of both players using an Ultra-Wideband (UWB) indoor real-time location system (RTLS). This system tracks player positions on the court with an update rate of 25 Hz, and the x, y positions are included in the datasets.

Access to this dataset will be provided upon the publication of the corresponding paper.
