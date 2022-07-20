Smart methods IOT department's first task
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
Part one: The task is to create a web page that takes speech as an input and then convert it to text using JavaScript.

Link: https://saudalsheikh.github.io/

Part two: Writing an algorithem that explains how to install and run esp32.

How to install and run ESP32:
-------------------------------
first step: Download the Arduino IDE through the following link "https://www.arduino.cc/en/software".

second step: Open the Arduino IDE and download the board manager through file ==> preferences. then, insert the following link "https://dl.espressif.com/dl/package_ESP32_index.json"
in additional boards manager url.

third step: Go to Tools ==> board ==> board manager. After that, a new window will popup and then search for "ESP32" and install the package.

fourth step: Connect the ESP32 board. Then, go to Tools ==> board ==> ESP32 Arduino and choose your board.

Note: Make sure you connect your board in the right port selected in Tools ==> Port.

fifth step: To make sure that your board is connected go to File ==> Examples ==> 01.Basics ==> Blink. Run the code and the LED should blink.
