## Servo Motor Control With Joystick

The joystick outputs position as an analog signal depending on whether the lever is moved forward-backward or right-left.
The servo is a motor that positions itself at an angle according to the signal received from the data pin

When the lever on the joystick is moved back and forth, the voltage values on the VRX pin change and the voltage values on the VRY pin changes when it is moved to the right or left. When you click on the joystick, the SW pin gives SV output. in this example, the VRX pin will be used as we will only use one servo. Since the data from the VRX pin is analogue data between O and SV, connect it to the AO pin on Arduino. Connect the data pin of servo motor to pin 3 which can give analog output. The sample code allows the servo motor to rotate between O and 180 degrees with the data from the joystick.

After setting up the circuit, let's continue with coding.


![11](https://user-images.githubusercontent.com/111511331/191002111-f385b562-31b7-4b01-98b1-1884961be0ae.png)
