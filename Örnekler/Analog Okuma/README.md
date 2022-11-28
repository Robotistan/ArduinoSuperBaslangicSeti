## Analog Reading and Serial Communication With Arduino Details
When you look at the Arduino board, you will see the "Analog Input" pins. It is possible to read the voltage on this pin by converting from digital to analog signal using these pins. The Arduino is capable of reading 0V(zero) and 5V digitally. If there are intermediate values between these two extremes, it cannot detect it and accept the incoming voltage as 0V or 5V according to the threshold value. Thanks to analog pins, you can detect intermediate voltage values from 0V to 5V and convert them to digital. You will use a adjustable resistor(potentiometer) to obtain signals at intermediate values. In the application, you will read the numerical value of the voltage coming from the analog input pin on the serial port. 

Let's set up circuit and continue with coding.
![6](https://user-images.githubusercontent.com/112697142/190644724-2359220f-709e-430c-b819-509a8e4ba646.PNG)
