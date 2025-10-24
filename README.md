# Single-LED-Interface-using-PIC16F877A

🔧 Project Overview

This project demonstrates a simple LED blinking example using the PIC16F877A microcontroller.
The LED connected to PORTB Pin 7 (RB7) toggles ON and OFF every 1 second, illustrating basic digital output control.

⚙️ Hardware & Software Requirements

Hardware:

PIC16F877A Microcontroller

LED (any color)

330Ω resistor

Breadboard / Proteus simulation board

Software:

MPLAB X IDE

XC8 Compiler

Proteus 8 Professional (for simulation)

🧩 Proteus Circuit Setup

Controller: PIC16F877A

Oscillator: 20 MHz Crystal (connect to pins 13 & 14)

LED: Connect anode to RB7 through 330Ω resistor, cathode to GND

Power: +5V to VDD, GND to VSS

▶️ Simulation Steps

Open Proteus_Design.pdsprj in Proteus 8.

Load the compiled .hex file generated from MPLAB X.

Run the simulation — watch the LED blink every second.
