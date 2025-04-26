# Illuminate
Through Wellesley College's CS 320 Tangible User Interfaces, a team and I worked to create a functional lamp that reinvents classroom dynamics. We are proposing a design that is visually aesthetic and impactful. We will solder individual blue and yellow glass pieces to form a top of the lamp. These bright colors are proven to foster innovation and creativity during group discussions. The inner components include the Arduino Plug and Make Kit (with Modulino Pixels, Modulino Distance, and Modulino Buttons). Based on the user's intention, the LEDs will shine through the glass pieces (either blue, meaning normal question, or yellow, meaning urgent question).

We believe a tangible approach is effective in addressing this problem as these products can function as an extension of the user. Today’s world is becoming increasingly virtual. And, some may have it tiresome or stressful to try and interject in meetings with their own body, such as speaking over others or raising their hands for an extended duration of time. By having a real and concrete object (rather than abstract or virtual) in front of every individual at a meeting, we give each individual equal power to interject themselves into a conversation, boosting their confidence and giving them a sense of value and impact within the group. 

# List of Libraries Used
The Modulino.h library makes Arduino coding with Modulino parts easy and modular. Through this library, we are able to create an object for each Modulino part and call built-in functions. It handles pin set-up, reading sensors, and controlling outputs internally. 

# Set-Up Instructions
There are no dependencies for this product. 
1. Begin by plugging your Arduino Uno R4 Wifi Board into your computer using a USB-C cable.
2. Use Qwiic cables to connect the Modulino Distance, Modulino Buttons, and 2 Modulino Pixels (in the order listed) to the Wifi Board.
3. Verify, upload the code, and press the reset button (small white button) on the board to begin running the program.

# Usage Instructions
To use the TUI, press the right eye (right button) when you want to speak in line with the conversation topic; this will light up the blue LEDs. Use the mouth (distance sensor) to show your level of urgency to speak. Once your turn arrives, press the right eye again to turn off the blue LEDs. If you want to contribute an important thought or raise a question, press the left eye (left button) to light up the yellow LEDs, again using the mouth to indicate urgency. Remember to press the left eye to turn off the yellow LEDs once your turn arrives. If you switch between blue and yellow LEDs, always turn off the active LED before turning on a new one.

# Credits & External Resources
Created with Liora Jones and VV (Xue Qing) Chua. Special thanks to Orit Shaer, Zoe Mitchell, and Mary Calabro for their guidance and help in finding resources.

[Arduino Plug and Make Kit Datasheet](https://docs.arduino.cc/resources/datasheets/AKX00069-datasheet.pdf)

[I2C Address Changer](https://github.com/arduino-libraries/Modulino/blob/main/examples/Utilities/AddressChanger/AddressChanger.ino)

[Arduino Plug and Make Kit Modulino Code Examples](https://forum.digikey.com/) 
