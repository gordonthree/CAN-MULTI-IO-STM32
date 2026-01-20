# Analog / Digital Multi-IO Controller
Compact controller board intended to interface with various analog and digital sensor modules, as well as provide isolated digital outputs. An isolated CAN-FD interface provides expansion capability with other controllers, displays and sensors.

<img src="https://github.com/gordonthree/CAN-MULTI-IO-STM32/blob/main/CAN-MULTI-IO-STM32.png?raw=true" width=480 alt="3d rendering of circuit board">

# Multi-IO Node
* STM32L433 Microcontroller
* Automotive grade switch-mode power supply for 5v rail
* Automotive grade low-dropout linear supply for 3.3v rail
* 3-pin terminal block for CANBUS connection with drain
* Jumper selected CAN terminator resistor
* Two ADIO headers with six total input/output pins
* I2C bus header with selectable pull-up resistor (I2C2)
* One-Wire bus header (USART3)
* LED indicator for 3.3v power
* LED indicator for status, controlled by the micro
* Bidirectional transient voltage protection diode for harsh environments
* Headers for USART1 serial port and the SWLINK programming connector
  
