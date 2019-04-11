# ArducamESP32
After having trouble finding a working version of an Arducam OV2640 project in the Arduino ESP32 environment I had to make changes to the Cpp and H file for it to even compile.. apparently there was a conflict with some variable names between the sketch and the libraries... I also had to figure out by trial and error that the TTGO ESP32 board seems to show better performance using the VSPI not the HSPI bus and the pins are even labeled slightly differently from other ESP boards...Basically this sketch works with the standard Arducam library and ESP32 TTGO board using VSPI pin 5 as the CSO(CSN).
