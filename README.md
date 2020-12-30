<h1><center>Simple Arduino Project</center></h1>
<hr/>

## Greeting
Hello Everyone,
Welcome to documentation of a Simple Arduino Project.

All project in this documentation has I created and tested, but if you trying to run the project but it doesn't work, may be you can check the pin and also the libraries (if it need) before adding an issue

If you had issue about credit, you can contact me via Discord DM (glenaldinlim#7397).
Thank you for coming, sorry if my grammar so bad.

Sincerely,
Glenaldin Halim

## Table of Content
- [Greeting](#greeting)
- [Table of Content](#table-of-content)
- [Libraries](#libraries)
  - [How to import / install libraries to ArduinoIDE](#how-to-import--install-libraries-to-arduinoide)
    - [Using Library Manager](#using-library-manager)
    - [Import from .zip file](#import-from-zip-file)
  - [Manual Installation](#manual-installation)
- [Project](#project)
- [Reference / Credit](#reference--credit)

## Libraries
- [LCD 16x2 I2C](Libraries/Arduino-LiquidCrystal-I2C-library-master.zip)
- [RFID RC522](Libraries/rfid.zip)

### How to import / install libraries to ArduinoIDE
There are two different step to install libraries to ArduinoIDE, you can download library from `Library Manager` (available from IDE version 1.6.2) or you can import a `.zip` library. 

#### Using Library Manager
Before you use `Library Manager`, your PC must connected to Internet
1. Open ArduinoIDE 
2. Click "Sketch" menu
3. Select *Include Library > Manage Libraries* and `Library Manager` will open
4. On search field, you can search library that you want to install
5. After you find the library,you can select the version that you want install (higher version is better), but don't worry if the version of the library doesn't appear, it's normal 'cause some library has a version
6. Finally click on *Install* button then wait the installation
7. Once it has finished, and *Installed* tag should appear next to the library name. After that, you can close the library manager and you will find the new library in the *Sketch > Include Library* menu.

#### Import from .zip file
1. Open ArduinoIDE 
2. Click "Sketch" menu
3. Select *Include Library > Add .ZIP Library...* and your file manager will open
4. Navigate to the .zip file's location and click the file, then click *Open* button. After that, wait the importing progress (maybe your ArduinoIDE will be freeze for a little bit)
5. Once it has finished, you can find the new library in the *Sketch > Include Library* menu. The library will appear in the bottom of the drop-down menu

NB: the Library will be available to use in sketches, but with older IDE versions examples for the library will not be exposed in the File > Examples until after the IDE has restarted.

### Manual Installation
Coming soon, ASAP. 

## Project
- [Writing Text in LCD16x2 with I2C Module](LiquidCrystal_I2C/readme.md)
- [Read RFID Tag with RFID RC522 Module](RFID_RC522/readme.md)
- [Control SG90 Tower Pro Servo Module with Arduino](SG90_Servo/readme.md)

## Reference / Credit
- [Installing Additional Arduino Libraries](https://www.arduino.cc/en/guide/libraries)
- 