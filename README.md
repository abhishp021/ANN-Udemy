# ANN-Udemy

### Dataset
Combined Cycle Power Plant Dataset taken from **UCI Machine Learning Repository** and has 4 attributes<br/>
![Initial Dataset](https://github.com/abhishp021/ANN-Udemy/blob/cbba1b8c461e4da63ae923ea71a1162dd384874f/ScreenShot_20220716082557.jpeg)<br/>

Features consist of hourly average ambient variables
- Temperature (AT) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW
The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization.


### Working
![Initial Dataset](https://github.com/abhishp021/ANN-Udemy/blob/cba8f9e28e378c9e522361b53ab0a8768d1071de/ANN_Architecture.png)<br/>
- Used ANN (Artificial Neural Network)
- 2 Dense Hidden layers 
- 'adam' optimiser for hidden layers

### Error
Mean Square Error converges to around 26 after 50 epochs
