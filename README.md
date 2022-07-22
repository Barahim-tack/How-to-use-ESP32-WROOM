# How-to-use-ESP32-WROOM
How to start with ESP32-WROOM board

ESP32 is one of the good chips that can be programmed by Arduino IDE, and has capability to connect to the network. 

The algorithm to use ESP32-WROOM:
1. First you should download Arduino IDE on your computer using the link: https://www.arduino.cc/en/software 
2. You need to prepare Arduino IDE to accept ESP32 boards, so you first open Arduino IDE. 
3. Go to File >> Preferences >> and then paste this link (https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json) into "Additional Board Manager URLs” field >> Finally press OK. 
4. Then, you go to Tools >> Board >> Boards Manager.
5. A new window will be opened, Write "ESP32" into the search field, and click on Install button for “ESP32 by Espressif Systems". 
6. Close the Arduino IDE and re-open it. 
7. Connect ESP32-WROOM board to the computer. 
8. Go to Tools >> Board >> ESP32 Arduino >> and select "WEMOS D1 MINI ESP32". 
9. Go to Tools >> Port >> and select the available port. 
10. You can test the board by using one of the examples available in IDE such as "Blink". 
11. Go to File >> Examples >> Basics >> Select "Blink" , and upload the code to the board. 
