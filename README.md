<h1><center>Simple Arduino Project</center></h1>
<hr/>

## Greeting
Hello World!
Welcome to the documentation of a Simple Arduino Project.

All projects in this documentation have I tested, but if you're trying to run the project, but it doesn't work, maybe you can check the pin and also the libraries (if it needs) before adding an issue

If you had an issue with a credit or a problem with the project, you can add an Issues on GitHub or contact me via Email

Sincerely,
Glenaldin Halim

## Table of Content
- [Greeting](#greeting)
- [Table of Content](#table-of-content)
- [Libraries](#libraries)
- [Project](#project)
- [How to / Tutorial](#how-to--tutorial)
  - [How to import / install libraries to ArduinoIDE](#how-to-import--install-libraries-to-arduinoide)
    - [Using Library Manager](#using-library-manager)
    - [Import from .zip file](#import-from-zip-file)
  - [Manual Installation](#manual-installation)
- [Reference / Credit](#reference--credit)

## Libraries
- [LCD 16x2 I2C](Libraries/Arduino-LiquidCrystal-I2C-library-master.zip)
- [RFID RC522](Libraries/rfid.zip)
- [HCSR04 Ultrasonic](Libraries/HCSR04-by-Martin-Sosic.zip)

## Project
- [Writing Text in LCD16x2 with I2C Module](LiquidCrystal_I2C/readme.md)
- [Read RFID Tag with RFID RC522 Module](RFID_RC522/readme.md)
- [Control SG90 Tower Pro Servo Module with Arduino](SG90_Servo/readme.md)
- [Measuring Distance Using HCSR04 Ultrasonic Sensor](HCSR04_Ultrasonic/readme.md)
- [Turn On the LED Using a Push Button](Push_Button/readme.md)

## How to / Tutorial
### How to import / install libraries to ArduinoIDE
There are three different steps to install libraries to ArduinoIDE, you can download the library from `Library Manager` (available from IDE version 1.6.2) or you can import a `.zip` library or you can add it manually.

#### Using Library Manager
Before you use `Library Manager`, your PC must be connected to the Internet
1. Open ArduinoIDE 
2. Click the "Sketch" menu
3. Select *Include Library > Manage Libraries* and `Library Manager` will open
4. In the search field, you can search library that you want to install
5. After you find the library, you can select the version that you want to install (the higher version is better), but don't worry if the version of the library doesn't appear, it's normal 'cause some library has a version
6. Finally, click on the *Install* button then wait for the installation
7. Once it has finished, and *Installed* tag should appear next to the library name. After that, you can close the library manager and you will find the new library in the *Sketch > Include Library* menu.

#### Import from .zip file
1. Open ArduinoIDE 
2. Click the "Sketch" menu
3. Select *Include Library > Add .ZIP Library...* and your file manager will open
4. Navigate to the .zip file's location and click the file, then click the *Open* button. After that, wait for the importing progress (maybe your ArduinoIDE will be freeze for a little bit)
5. Once it has finished, you can find the new library in the *Sketch > Include Library* menu. The library will appear at the bottom of the drop-down menu

NB: The library will be available to use in the "Sketch" menu. In the older IDE versions, the *Examples* of the library won't be exposed in the *File > Examples* until after the IDE has restarted.

### Manual Installation
Coming soon, ASAP. 

## Reference / Credit
- [Installing Additional Arduino Libraries](https://www.arduino.cc/en/guide/libraries)
- 