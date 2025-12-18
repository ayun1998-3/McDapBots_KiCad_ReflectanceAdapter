# McDap Bots Pedagogical Robot

This project was created as a capstone project for the University of Virginia Department of Electrical and Computer Engineering. Our goal was to create a small robot which could be programmed by students, for use as a teaching aide in an embedded systems course. This repository contains the software component of this, both drivers and application code.

**Authors**
- Colby Wise
- Pratik Pandit
- Austen Yun 
- David Merino
- Marc Rosenthal

**Advisors**: Todd DeLong and Adam Barnes 

**Features at a glance**
- 2 motors (PWM controlled), OLED screen (I2C), reflectance sensor (I2C), bump switches (GPIO), Bluetooth (UART), and infrared sensors (ADC)
- battery charging port and battery voltage display (press button to enable)
- support for TI and STM microcontrollers

## What is contained here
This repository contains a KiCad project file for the reflectance sensor adapter board, which connects the [15-Channel Reflectance Sensor Array](https://www.pololu.com/product/4315) to
the robot's main PCB. The reflectance sensor board can be soldered onto this adapter board via male header pins, and this adapter board has pins that plug into the bottom of the main PCB.

**Schematic File**
KiCad schematic file that shows the electrical connections of the reflectance sensor adapter board. 

**Layout File**
KiCad layout file that shows how the components are placed and routed on the reflectance sensor adapter board.

**Bill of Materials Files**
BOM.xlsx contains a list of all the parts needed for to add the reflectance sensor as a feature to the robot.
Digikey_Parts_List.xlsx is a file that can be uploaded to Digikey to select the parts needed for one copy of this board.

## How to use this repository
1. Copy the repository locally to your computer
2. Using KiCad 8.0 (or higher version) open the file `Reflectance_Adapter.kicad_pro"`
3. Generate necessary gerber files and order components
