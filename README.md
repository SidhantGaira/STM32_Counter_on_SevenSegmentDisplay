Overview: 

This project demonstrates basic GPIO control and application of functions & arrays by making a counter a D1 digit of a 4 digit 7 segment display using STM32CubeIDE.

Hardware Used :

STM32 Nucleo F103RB
Breadboard
4 x 220 ohm Resistor
4 digit Seven Segment Display
DuPont / Jumper Wires

Software Used: 

STM32CubeIDE
HAL Drivers

Features: 

GPIO output configuration
LED blinking at different times independent to each other
Basic embedded system setup

Project Structure: 

Core/Src → main application code
Core/Inc → header files
Drivers → STM32 HAL libraries
.ioc → peripheral configuration

How to Run:

Open the .ioc file in STM32CubeIDE
Build the project
Connect STM32 via USB
Flash using ST-Link

Output:

You observe that a counter starts from 0 and goes till 9 and then repeats the cycle again.

Learnings:

GPIO configuration in STM32
Understanding HAL functions
Embedded project structure
Multiplexing inside the display
Loops 
arrays
Funcitons

License:

MIT License Copyright (c) 2026 Sidhant Gaira Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files...
