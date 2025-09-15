# Display-Counter-Using-Arduino

This project creates a simple digital counter using an Arduino and a 16x2 Liquid Crystal Display (LCD). Every time a push button is pressed, a number on the LCD screen increases by one.

Functionality ⚙️
The Arduino continuously checks the state of a push button. When it detects that the button has been pressed (a HIGH signal), it performs two actions:

It increments a counter variable by one (count++).

It displays the new value of the counter on the first line of the 16x2 LCD.

The code includes a debouncing mechanism (while(digitalRead(pbutton)==HIGH);) to ensure that a single, prolonged press is only registered as one count, preventing the number from rapidly increasing while the button is held down.

Hardware Requirements 🔩
Arduino Uno (or any compatible board)

16x2 LCD Display

Push Button (momentary switch)

100Ω Resistor (for the push button pull-down)

Potentiometer (for adjusting LCD contrast)

Breadboard

Jumper Wires

Software Requirements 💻
Arduino IDE

Circuit and Connections 🔌
