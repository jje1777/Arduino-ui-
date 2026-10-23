# Arduino-ui-
This project has an Arduino (R) 4 wifi with an Elegoo TFT 2.8" touch screen display. The project is still in bata but will work fine. I'll put the list of libraries and other important stuff below .

The program will work with a regular Arduino uno but some of the features  will not work. 

The list of libraries are below, 

1. Arduino_GFX_Library – Drives the TFT display controller (ILI9341 over 8-bit parallel bus).

2. TouchScreen – Handles resistive touch screen inputs and calibration on analog/digital pins.

3. EEPROM – Built-in library used for non-volatile storage (saving themes, Wi-Fi credentials, PINs, notes, and custom widget layouts).

4. WiFiS3 – Provides Wi-Fi connectivity support specifically for the Arduino UNO R4 WiFi board.

5. WiFiUdp – Used alongside Wi-Fi for sending and receiving UDP packets (handling NTP time sync and mDNS).

6. ArduinoMDNS – Manages local network domain resolution (the-tft-display.local).

7. Modulino – Controls external Modulino hardware modules connected via I2C (specifically driving the ModulinoBuzzer).

Internal System Libraries Used Automatically (i don't know if the next 2 are preinstaled or not.)

8. NVIC (Cortex-M core functions used for system resets).

9. Wire1 / I2C (Hardware I2C bus used internally by the Modulino library).
