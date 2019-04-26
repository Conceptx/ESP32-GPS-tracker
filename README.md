# ESP32-GPS-tracker

Video tutorial : https://youtu.be/hh-_s-NNab4

This PCB is a relay controller board with LoRa, You can use this PCB mostly to control appliances like garage doors etc.
The Pcb uses:
1) ESP32 as the microcontroller
2) RYLR896 LoRa module.
3) OLED SSD13086 0.96' display
4) Other basic components.

This PCB also has an OLED display and 3 relays which are connected to the ESP32. You can do anything with the code and control the relays using LoRa/WiFi/Bluetooth. So, in short, this project has an ESP32 which can give WiFi/Bluetooth functionality, LoRa module, OLED display and 3 relays. Possibilities with the code are endless. I have also added a prototyping area where you can add sensors or additional relays to the ESP32 which is also accessible.

This is a type of part 2 of a project. So for any control system like this one you need a remote to control the things.
I made a LoRa based remote which you can check out here:
In my case I am using the remote and this controller together and they work like a charm!

There are 3 relays on board connected to pin 25/26/27 which can be customised using the selector jumpers under the ESP32 board.

![alt text](https://github.com/akarsh98/LoRa-Relay-Controller-Board/blob/master/screenshots/fpcb.JPG?raw=true)

You must check out [JLCPCB](https://jlcpcb.com/m) for ordering PCBs online for cheap!

You get 10 good quality PCBs manufactured and shipped to your doorstep for 2$ and some shipping. You will also get a discount on shipping on your first order. To design your own PCB head over to [easyEDA](https://easyeda.com/), once that is done upload your Gerber files onto [JLCPCB](https://jlcpcb.com/m) to get them manufactured with good quality and quick turnaround time.

![alt text](https://github.com/akarsh98/RadioHead-/blob/master/SCREENSHOTS/JLC_AD_APR19.jpg?raw=true)


## The Circuit in action and some other Pictures

![alt text](https://github.com/akarsh98/ESP32-LoRa-Relay-Control-Code-and-Circuit/blob/master/screenshots/IMG_20190420_113747.jpg?raw=true)
![alt text](https://github.com/akarsh98/ESP32-LoRa-Relay-Control-Code-and-Circuit/blob/master/screenshots/5.JPG?raw=true)
![alt text](https://github.com/akarsh98/ESP32-LoRa-Relay-Control-Code-and-Circuit/blob/master/screenshots/4.JPG?raw=true)
