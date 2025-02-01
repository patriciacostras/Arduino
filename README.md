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

![image](https://github.com/user-attachments/assets/b3eb12b2-b670-47b5-a313-68e20cc57cf2)

This circuit diagram features an Arduino Uno microcontroller and showcases various components wired together for a project involving LEDs, a 7-segment display, and a temperature sensor. Here's a breakdown:

### Key Components:
1. **Arduino Uno**: The main microcontroller that runs the code and controls the connected components.
2. **7-Segment Display**: Displays numerical data (e.g., temperature or other values) controlled by the Arduino.
3. **LEDs**: Three LEDs (red, green, and blue) are connected to digital pins through current-limiting resistors. These could be used for visual feedback or status indication.
4. **Temperature Sensor (TMP)**: Reads analog data corresponding to the surrounding temperature and sends it to the Arduino for processing.
5. **Push Button**: Likely used as an input for user interaction (e.g., toggling modes or resetting values).
6. **Battery Pack (AA 1.5V)**: Provides additional power to the system, possibly for components requiring external power.

### Functionality:
- **Temperature Monitoring**: The TMP sensor detects temperature and sends the analog signal to the Arduino, which converts it to a digital value. This is likely displayed on the 7-segment display.
- **LED Feedback**: The three LEDs might indicate specific thresholds or states (e.g., temperature too high, normal, or too low).
- **Push Button**: Allows for manual interaction, such as switching modes between Celsius and Fahrenheit or resetting the system.
- **7-Segment Display Control**: Displays numerical values like temperature readings, using appropriate segments powered by the Arduino.

### Power Flow:
- The Arduino is powered via USB or battery, while other components like LEDs and the 7-segment display draw power from the Arduino's digital pins.
