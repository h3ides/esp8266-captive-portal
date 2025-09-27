ESP8266 WiFi Captive Portal
Disclaimer
This project is for testing and educational purposes. Use it only against your own networks and devices. I don't take any responsibility for what you do with this program.

About this project
WiFi captive portal for the NodeMCU (ESP8266 Module) with DNS spoofing.

The built-in LED will blink 5 times when a password is posted.

Note! Your saved passwords will not disappear when you restart/power off the ESP8266.

Note: If you want to see the stored passwords go to "172.0.0.1/pass". For changing the SSID, go to "172.0.0.1/ssid"

Installation (Arduino IDE)
Open your Arduino IDE and go to "File -> Preferences -> Boards Manager URLs" and paste the following link: http://arduino.esp8266.com/stable/package_esp8266com_index.json
Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
Go to "Tools -> Board" and select you board"
Download and open the sketch "WiFi_Captive_Portal.ino"
You can optionally change some parameters like the SSID name and texts of the page like title, subtitle, text body...
Upload the code into your board.
You are done!
