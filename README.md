# STM32duino-Serial-Communication

How to Serial communication between STM32 board and Arduino or ESP32 Board

## Introduction

The serial communication makes sure every byte of the data is transferred to the other device. 
RX receives serial data and TX sends the serial data to other board or device. 
In this write-up, serial communication in Arduino is explained in detail with the help of a simple example.

## Background

In STM32, There are some pins that can be used as Serial Communication; you can get information about pin on  
[datasheet](https://www.st.com/resource/en/datasheet/dm00037051.pdf)
for example in Arduino pin 0 and pin 1 are assigned for the serial communication known as 
[UART](https://www.techopedia.com/definition/3669/universal-asynchronous-receivertransmitter-uart) (Universal Asynchronous Receiver Transmitter) and 
[USART](https://www.techopedia.com/definition/9850/universal-synchronousasynchronous-receivertransmitter-usart) (Universal Synchronous Asynchronous Receiver Transmitter) 
and they are also known as Tx/Rx pins

## Getting started

These steps are discussed in details below

 - Hardware: make sure you have two microcontroller and wire them together
 - Software: make sure you have the Arduino IDE and install this library 
   https://raw.githubusercontent.com/stm32duino/BoardManagerFiles/master/STM32/package_stm_index.json
 - Example: open, compile, flash and run one of the library examples
