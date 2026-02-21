# Retro-VFO
# A Si5351A/MS5351 100kHz lower limit Quadrature Clock Generator with Retro Rotory Dial Using a 1.54" 240x240, 1.9" 170x320 or 2.0", 2.4", or 2.8" 240x320 dpi ST7789 LCD Displays.

Added a Arduino Nano code example, quad.zip, to demonstrate just the quadrature output without the display.

Based on code/design by T.J. Uebo (JF3HZB) A.K.A Tj Lab(JF3HZB)  https://github.com/tjlab-jf3hzb/Digital_VFO_with_analog_dial_V2.git

Added VFO_RETRO_TFT_1.54_ETHERKIT.zip which uses a modified version of Jason Milldrum's Si5351_Etherkit library.
     
 *    Note: Arduino IDE version 2.3.7 was used with esp32 core version 3.3.7
 
 *    Uses a ESP32 DOIT DEVKitC (a 30-pin WROOM board. Other WROOM/WROVER boards may work (untested).
     
 *    Under Arduino IDE Tools menu select Esptool as programmer.
   
 *    9600 BAUD Kenwood ST-2000 CAT Control Emulation by Barb (Barbaros ASUROGLU) - WB2CBA.
 *    KY-040 Encoder powered by 3.3V from ESP32. Uses ESP32 Rotary library ESP32Encoder library.
 *    ST7789 displays are Powered by 3.3V from ESP32.
 *    Si5351A module powered from +5V supply.
 *    Display driver is TFT_eSPI or LovyanGFX. Install from IDE library manager.
 *    Uses local modified copy of Si5351 library by Tj Lab(JF3HZB) https://github.com/tjlab-jf3hzb/Digital_VFO_with_analog_dial_V2.git
 *    Quadrature output down to 100kHz.
 *    Added set_drive_level() function to allow setting output level for each clock.
 *    Kicad V9.x PCB design files are included.
***
![IMG_20241207_HDR](https://github.com/user-attachments/assets/58c91bbc-8729-42d1-ac4e-7053147a2246)
***
![pic_65_2](https://github.com/user-attachments/assets/c770457f-f190-4c7f-9e9f-50a07137bf31)
***
