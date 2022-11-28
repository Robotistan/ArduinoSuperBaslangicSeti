## LED Lighting With Button Details
In this application, you will learn to use pins on Arduino as input. In this way, you can ensure to be notified in Arduino when a button is pressed remotely. The LED circuit may be the same as the previous application. Only the leg to which the LED is connected will be #10 in this application. Let's set up the circuit and then continue with coding.

In order to read the data from the button, it is required to use it together with 10k Ohm resistor. You need to use "pull-up" or "pull-down" resistance to prevent interference when the button is not pressed. In this application, we will use "pull-down" resistance. In this project, the pin reads the value of 0V, i.e. LOW logic level, when the button is not pressed. The pull-down resistance ensures that the voltage on this pin remains constant at 0V unless the button is pressed and the value is HIGH. Now that you have learned the logic of the circuit, let's continue with coding.

![4](https://user-images.githubusercontent.com/112697142/190633739-54ec4c91-b376-4a4c-ad7e-d59bac5075ee.PNG)
