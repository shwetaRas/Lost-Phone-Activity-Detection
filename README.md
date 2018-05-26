<b> LOST PHONE ACTIVITY SELECTION </b><br>

<b>OBJECTIVE</b><br>
In this project we develop various scenarios where a person can be separated from his phone. <br><br>
Specifically, we take 3 different situations into consideration. <br>
•	Case 1: user places a phone on a surface and forgets about it.<br>
•	Case 2: user drops his phone while walking or standing. <br>
•	Case 3: user’s phone is stolen from his pocket by a thief or perpetrator.<br>

The implementation of this paper is focused on creating different signatures for each of these activities and then training an LSTM classifier to demonstrate how mobile sensor data could be used to warn the user about the missing phone problem in real time.<br>

<b>DATA COLLECTION</b><br>
We used the AndorSensor Application available on Google Playstore to collect inertial sensor data when the user performs several motions. All collected data is available in the '6m_data' folder. <br>


<b>TRAINING</b><br>
Training of the application has been perfomed using the LSTM model in TensorFlow. <br>

<b>ACCURACY</b><br>
Our model provides an accuracy of 92%.



