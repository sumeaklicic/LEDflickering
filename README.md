# LEDflickering
Flashing leds using an Arduino and a few basic lines of code to light up the led

First, we'll go over some basic information you need to know about diodes.
Materials needed for the project:
-Arduino UNO board
- LEDs
- The resistors

  ![image](https://github.com/user-attachments/assets/59a2fe98-b0e4-4699-88f2-a8b8f5465415)
In the picture we see the material and the method of joining it.

A diode has its two parts, the anode and the cathode.
![image](https://github.com/user-attachments/assets/0e29216a-d3ce-44ba-9ff1-dd4194f30e7d)

The anode is the positive part and we connect the resistor to it. The resistor is used to limit the current through the LED and protect it from damage. We connect the other side of the connected resistor to the desired pin on our board.

We connect the negative side or cathode to GND. GND (Ground) – Grounding. The term earth is often used in electronics for a conductor at zero potential, and it is the reference for all voltage measurements at a potential of 0 volts. If it is said that the voltage of a point in the circuit is 5 V, it means that the voltage between that point and the ground (the point of zero potential determined by convention) is equal to 5 V. The conductor under zero potential is often the minus line of the device's power supply. Grounding is a line (conductor) at zero potential that serves for protection! It should be understood that portable devices do not have a classic This is about the electrical connection of all the metal parts of the components in one device to that line that acts as grounding.

By connecting the diode to the board in this way, we have established contact, the resistor protects the diode and the diode lights up.

![image](https://github.com/user-attachments/assets/5074c62c-a0c6-413c-8d33-1ee46c30998e)

This is the basic thing we need to know for the project itself, which is attached. In my project, 10 LEDs were connected and different transitions were made to make the project look much more interesting. A lot of different transitions can be added, but first learn the basics such as the functioning of the Arduino UNO board and the diode itself



