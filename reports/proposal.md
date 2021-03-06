# I2C2 (I2C in C)
## David Tarazi and Jack Greenberg

The goal of our project is to write an implementation of the I2C (inter-integrated chip) protocol in C. Our MVP will be having two Arduinos communicate over I2C (sending random data or sensor data from another I2C). We will manipulate the pins and ports of the Arduino to enable device communication, and have some sort of sensor (like a soil moisture sensor) that produces data and sends it via I2C to our Arduino, and we will then be able to read out from the Arduino using a serial output.

### Goals
Our goals are learning about writing embedded firmware and about inter-device communications at the phyiscal level. We also hope to learn about reading data sheets and understanding the technical jargon they contain.

### Getting Started
To get started, we need a solid understanding of how I2C works and we need hardware. We have multiple Arduinos that we can use, and we will purchase a sensor that already uses I2C so that we can focus on reading data from the sensor using our implementation.

### First Steps
1. Researching I2C and learning the fundamentals of how it works. (David & Jack)
    * Create a list of functions that we need to write (read and write functions, start and stop functions, etc)
    * Research device addressing in I2C and learn how they are set
    * Find details of setting and getting baudrates in hardware and software
2. Familiarize ourselves with the low-level functionality of Arduino so that we understand how to manipulate pins and ports.
    * Learn how to read and write individual pins on an Arduino
    * Use Arduino's built-in I2C to establish a successful communication standard that we can use to verify our implementation
3. Set up the hardware to read data from a sensor (Arduino, sensor).
    * Wire Arduino to sensor
    * Connect Arduino to computer to get a read-out (via serial)
