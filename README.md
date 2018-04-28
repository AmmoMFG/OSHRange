# OSHRange
OSH Range - Open Source Hardware Range is a hardware and software implementation for scoring Action Shooting

This is built mostly on a previous project called "OpenRange" however someone has now trade-marked that as another product. This project uses the OSH name as all of the hardware and software that makes it operate is 100% open source and will be made freely available from the GitHub or other sources.
Hardware

There are three hardware components:

    Target sensor - Monitors the target for hits
    Shot Timer - Controls the start buzzer, counts shots fired.
    Central Control - A box that receives data from sensors and timers writes them to a database and formats it for web presentation

Software

The software consists of three components as well, one for each hardware component. However the Central Control software rather than being written in C/C++ for the arduino will be written in a number of languages and depend very heavily on the operating system of the RasPi SoC.

Please see the Wiki for full documentation: https://github.com/AmmoMFG/OSHRange/wiki
