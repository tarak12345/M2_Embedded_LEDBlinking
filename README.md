# M2_Embedded_LEDBlinkingAtmega32
## LED BLINKING using ATMEGA32 AVR micrcontroller.
This article will tell you how to proceed towards the basic programming of AVR Atmega32. You will learn how to develop codes  for blinking LEDs through Atmega32. You will also learn how to determine direction of I/O pins and how to make the status of output pins high or low.

## DEVELOP THE CODE
First develop the code for “led blinking” by using Visual Studio Code. Here we will write code by using C language. For the programming of AVR Atmel32 two registers are used namely, DDR and PORT. DDR is a data direction register which tells the direction whether the pin of Atmega32 is input or output while the PORT register is an output register which tells whether the pin of corresponding port is active low (0V) or active high (5V)

## CIRCUIT SIMULATION ON SIMUL IDE

To observe the working of this code, simulate the circuit on Simul IDE by using Atmega32, 8 LEDs, registers, capacitors and crystal from the built-in library of Simul IDE. Notice that the ground and Vcc (voltage supply) pins of Atmega32 are connected by default in Proteus while working in real time you have to connect the Vcc with 5V and ground pins. Set the frequency of crystal oscillator and Atmega32 “16MHz” and set fuse bits.
