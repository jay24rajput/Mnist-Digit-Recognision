# Mnist-Digit-Recognision<br>
This is a sample implementation of RNN(Recurrent Neural Networks) using LSTM layer.<br>
The dataset used is mnist dataset.<br>
## How to run
1. Clone and download the project<br>
```git clone https://github.com/jay24rajput/Mnist-Digit-Recognision.git``` <br>
2. Install the dependencies <br>
```pip install -r requirements.txt --user```
3. Run the python file <br>
```python3 Digit_Recognision.py``` 
## Notes
If you are running the program on CPU then make the following changes:<br>
**line 3**<br>
```from tensorflow.keras.layers import Dense, Dropout,CuDNNLSTM``` <br>
**line 14**<br>
```model.add(LSTM(128,input_shape=(x_train.shape[1:]),activation='relu',return_sequences=True))``` <br>
**line 17** <br>
```model.add(LSTM(128),activation='relu')``` <br><br>
```Digit_Recognision.ipnb``` gives the detailed explanation of each steps along with a sample output. 
