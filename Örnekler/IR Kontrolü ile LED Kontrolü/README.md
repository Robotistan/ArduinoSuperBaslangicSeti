## LED Control with IR Controller

The application enables the LED to produce light in the desired color based on the infrared signals received from the IR controller. Red LEDs turn on when we press 1, green LEDs turn on when we press 2, and blue LEDs turn on when we press 3. When we press 4, all LEDs produce white light flashing at the same time. When we press 0, all "LEDs" turn off. No feature was assigned to other buttons.

There is an infrared LED on the IR control. The infrared LED blinks at a certain frequency according to the address of the buttan pressed and sends the signal to the IR receiver. Usually this infrared LED hasa flashing frequency of 38kHz. The frequency of the remote control used in this example was 38kHz.

After setting up the circuit, let's continue with coding.


![12](https://user-images.githubusercontent.com/111511331/191005729-24b35ddc-510e-4a7a-b799-1b0f7b500533.png)
