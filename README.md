
# Temperature Measurement System Using PIC18F45K22 Microcontroller

## Project Overview
This project demonstrates the design and implementation of a temperature measurement system using the PIC18F45K22 microcontroller. The system simulates temperature changes by varying voltage levels through a potentiometer. The analog voltage is converted to a digital value using the ADC module of the microcontroller and the corresponding temperature is displayed on a USART interface. Additionally, LED indicators provide visual feedback: a red LED for high temperature and a green LED for low temperature.

## Features
- **Microcontroller:** PIC18F45K22
- **Analog Input:** Potentiometer (simulating temperature variations)
- **ADC Module:** Converts analog voltage to digital value for temperature measurement
- **USART Communication:** Sends temperature data to Tera Term for display
- **LED Indicators:** Red LED for high temperature, Green LED for low temperature
- **Pushbutton:** Initiates the temperature measurement process

## Key Technologies Used
- Microcontroller Programming (PIC18F45K22)
- Analog-to-Digital Conversion (ADC)
- USART Communication
- LED Indicators for Feedback

## Setup

### Input Devices:
- **Potentiometer:** Used to simulate temperature variations as an analog input.
- **Pushbutton:** Used to initiate the temperature measurement process.

### Output Devices:
- **Red and Green LEDs:** Provide visual feedback for high and low temperatures.
- **Tera Term (or similar terminal program):** Displays temperature readings.

### Power Supply:
- **5V Supply:** A standard 5V supply is required to power the system.

## Results
- **Temperature Display:** Accurate temperature readings are displayed on Tera Term based on the potentiometer's voltage variations.
- **LED Indicators:** The red LED lights up for high temperatures, while the green LED lights up for low temperatures.

## How It Works
1. The potentiometer is adjusted to simulate temperature changes.
2. The microcontroller reads the analog voltage from the potentiometer using the ADC module.
3. The digital temperature value is then transmitted via USART to a terminal (such as Tera Term) for display.
4. Based on the temperature value, the system turns on the appropriate LED indicator:
   - Red LED lights up for temperatures above a certain threshold (high temperature).
   - Green LED lights up for temperatures below a certain threshold (low temperature).
5. The user can press the pushbutton to initiate a new temperature measurement.

## Requirements
- PIC18F45K22 Microcontroller
- Potentiometer
- Pushbutton
- Red and Green LEDs
- Terminal Program (Tera Term)
- 5V Power Supply

## License
This project is licensed under the MIT License.
