## Motor Control with Sound

In this example, you will provide motor movement according to the value read by the sound sensor. The sound sensor provides a digital output by measuring the ambient sound level with a microphone. The sensor circuit amplifies the audio signal received from the microphone and converts the analog audio signal into a digital signal according to the threshold level.
Since the motor draws excessive current, a motor driver board is used in such circuits. The motor drive powers the motor according to the signal it receives from the Arduino. This way you can safely control the motor without damaging Arduino.
The threshold value of the sound level can be adjusted with the potentiometer on the sound sensor. This adjustment can be made with the help of a screwdriver


Let's set up the circuit and then start writing our project code.

![sound](https://user-images.githubusercontent.com/111511331/191266510-b4533044-dbac-4793-a0cc-18a97d8194fe.png)
