# ESP32-First-Steps
Doing the simple stuff first - transitioning from the ESP8266 to the ESP32

These programs have been tested on the "DoIt" ESP32 development board, but should work equally well with other ESP32-based boards (although you will probably need to change GPIO numbers to suit).

## Blinky
Yup, just a simple, on-off blink of the blue LED on the DoIt board (GPIO-02) to prove that the hardware, toolchain, compiler and flash functions all work as expected.

## Blinky + WiFi
As above, but with the addition of WiFi connectivity.  This demonstrates how to set up a static IP, Netmask, Gateway and DNS for your ESP32 board and than loops on the Espressif demo WiFi access-point scanner program (you should be able to ping your ESP32 once this demo is running).

