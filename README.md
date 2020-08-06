# ECG-Anomaly-Detection-LSTM-AE-Hybrid-Network
A Research conducted by me and my professors for Detection of Anomaly in ECG Signals and track down Patients suffering from Cardiac Problems.
In this paper, Time Series data Reconstruction for the ECG Signals using Self-Supervised
Pattern Recognition Algorithm is proposed. Encoder and Decoder Mechanism with Long Short Term Memory
Networks is designed for the development of the Pattern Recognition System. The LSTM network can be
organized into an architecture called the Encoder-Decoder LSTM that allows the model to be used to both support
variable-length input sequences and to predict or output variable-length output sequences. In this architecture, an
encoder LSTM model reads the time series based input sequence in a step-by-step manner. After accepting in the
entire input sequence, the hidden state or output of this model represents an internal learned representation of the
entire input sequence as a fixed-length vector. This vector is then provided as an input to the decoder model that
interprets it as each step in the output sequence is generated. In this way, the time series based ECG Signal data is
accepted, processed and thus, a pattern is learnt from the sequential time-series data and thus, anomaly detection
of the ECG Signal is done. The Hybrid model used in the process is Long Short Term Memory Network with
Autoencoders for the reconstruction of the data and thus, anomaly detection is done with robustness and with
utmost accuracy.
