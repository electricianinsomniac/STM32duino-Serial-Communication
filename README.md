# STM32duino-Serial-Communication
How to Serial communication between STM32 board and Arduino or ESP32 Board
## Introduction
The serial communication makes sure every byte of the data is transferred to the other device. 
RX receives serial data and TX sends the serial data to other board or device. 
In this write-up, serial communication in Arduino is explained in detail with the help of a simple example.
## Background
In STM32, There are some pins that can be used as Serial Communication; you can get information about pin on datasheet. 
for example in Arduino pin 0 and pin 1 are assigned for the serial communication known as UART (Universal Asynchronous Receiver Transmitter) and USART (Universal Synchronous Asynchronous Receiver Transmitter) and they are also known as Tx/Rx pins
