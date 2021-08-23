# Time Series - Deep Learning
A Recurrent Neural Network (RNN) is a type of neural network well-suited to time series data.<br>
RNNs process a time series step-by-step, maintaining an internal state from time-step to time-step.

* Specifically designed with Sequence Data
* RNN are also flexible in their inputs and outputs for both sequences and single vector values

#### Input to output
* Sequence to Sequence
* Sequence to Vector
* Vector to Sequence

**LSTM (Long Short Term Memory) and GRU(Gated Reccurent Unit) (Better version of LSTM)<br>**
An issue RNN face is that after a while the network will begin to "forget" the first input, as information is lost at each step going through the RNN. We need some sort of "long term memory" for out networks. LSTM cell was created to help address the RNN issue.
