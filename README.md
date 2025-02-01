# PWM and Temperature Control Project

The purpose of the project is to make use of PWM signals, timers and LM35 sensor and implement them. After the hardware is done after the sketch, using the code provided the project will make us of: PWM signal and timers ( to fade-in and fade-out a tranzistor; in a given time using prescalers ), LM35 sensor ( used with an ADC to convert from tension measured to temperature ), serial communication ( to display values and for input to toggle tranzistor).

## Description
This project is designed for microcontroller-based systems using C and AVR libraries. It implements various functionalities including:
- LED control via PWM for fade-in and fade-out effects
- ADC (Analog-to-Digital Conversion) for temperature measurement
- Serial communication using USART
- Timer-based interrupts for periodic operations

## Features
- **LED Display Control:** Implements character display using LED segments.
- **PWM Control:** Adjusts LED brightness with gradual fade-in and fade-out.
- **Temperature Monitoring:** Uses an analog sensor to read temperature and toggles an LED based on threshold values.
- **Keyboard Input Processing:** Enables control via serial input to turn LEDs on/off.
- **Timer-based Interrupts:** Provides periodic execution of critical tasks.

## Hardware Requirements
- ATmega328P microcontroller (Arduino compatible)
- Temperature sensor (e.g., LM35)
- LED(s) for visual feedback
- Resistors and necessary wiring

## Software Requirements
- AVR GCC Compiler
- Arduino IDE (optional for testing)
- USB-to-Serial Interface (for debugging)
