# ESP32steps
First, what is ESP32? The ESP32 integrates the wireless transceiver so it can not only connect to WiFi and interact with the Internet, but can also set up its own network, allowing other devices to connect directly to it.
//// warning : ESP32 requires 3.3V power supply and 3.3V logic levels for communication

To install the ESP32 board in your Arduino IDE, follow these next instructions:
After installing the Arduino, go to File> Preferences
Enter the following into the “Additional Board Manager URLs” : "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json" click "ok"
Open the Boards Manager Go to Tools > Board > Boards Manager
Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:
That’s it, we will done.
for Testing the Installation  follow these next instructions:
after Plug the ESP32 board to computer With  Arduino IDE open
Select your Board in Tools > Board menu
Select the Port "COME3"
Open the following example under File > Examples > WiFi (ESP32) > WiFiScan
 A new sketch opens in your Arduino IDE: file:///C:/Users/66jam/Downloads/windows-wifi-scan-example-open.webp
 Press the Upload button in the Arduino IDE. Wait a few seconds while the code compiles and uploads to your board.
 After that you should see a “Done uploading.” message.
 done.



