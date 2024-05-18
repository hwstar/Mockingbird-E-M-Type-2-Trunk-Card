# Mockingbird-E-M-Type-2-Trunk-Card
An E&amp;M Type 2 trunk card for the Mockingbird Telephone Exchange

![alt text](https://github.com/hwstar/Mockingbird-E-M-Type-2-Trunk-Card/blob/main/assets/board_photo.jpg)

An interface card design for the Mockingbird Telephone Exchange. 

Features: 
* Provides one E&M type 2 interface
* STM32F103C8T6 microcontroller.
* Isolated local -48VDC supply for the M lead current
* Dry contacts for the E-lead
* Separate  RJ45 jacks for signalling and trunk pinouts.
* Uses standard 4 pair EIA568B Network cable pinout.
* Adjustable audio levels
* Accessed from the Main Microcontroller over I2C
* ATTEN signal to main microcontroller to tell it when there is an event to service.
* 4 Wire transformer isolated audio interface converts the balanced interface audio to unbalanced.
* Design in KiCAD 8.0.

The main project website is on hackaday.io here: https://hackaday.io/project/196044-mockingbird-telephone-exchange
