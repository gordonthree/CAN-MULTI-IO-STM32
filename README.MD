# Analog / Digital Multi-IO Controller STM32
Compact module intended to interface with various analog and digital sensor modules, as well as provide generic digital outputs. An isolated CAN interface provides expansion capability with other modules, displays and sensors.

<img src="https://github.com/gordonthree/CAN-MULTI-IO-STM32/blob/main/CAN-MULTI-IO-STM32.png?raw=true" width=480 alt="3d rendering of circuit board">

# Multi-IO Node
* STM32L433 Microcontroller
* Automotive grade switch-mode power supply for 5v rail
* Automotive grade low-dropout linear supply for 3.3v rail
* 3-pin terminal block for CANBUS connection with drain
* Jumper selected CAN terminator resistor
* Analog header with four 16-bit ADC inputs
* GPIO header with four digital input/outputs
* Dedicated external I2C bus with interface buffer (hot swap capable)
* One-Wire bus header (USART3)
* LED indicator for 3.3v power
* LED indicator for status, controlled by the micro
* Power input transient voltage protection diode for harsh environments
* Voltage divider to monitor input voltage
* Headers for USART1 serial port and the SWLINK programming connector