# EE242Final

 :- Install Arduino IDE 2.0.3
 :- Extract the EE242_Salam_inferencing.zip to Arduinos libraries folder. Usualy the libraries folder is located at C:\Users\Alican\Documents\Arduino\libraries
 :- Add https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json to the Additional board manager urls. (File->Preferences)
 :- Tools->Board->Board Manger select esp32 by Espressif system install version 2.0.3
 :- Select ESP32 Dev Module for target board.

 :- Now you may compile and upload the code.

 :- Wiring	      INMP441
 :- D25     ->       WS
 :- D19     ->       SD
 :- D21     ->       SCK
 :- GND     ->       LR
 :- GND     ->       GND
 :- 3V3     ->       VCC
