# Retro-VFO
A Si5351A/MS5351 100kHz lower limit Quadrature Clock Generator with Retro Rotory Dial Using a 240x240 dpi 1.54 inch ST7789 TFT Display.
Based on code/design by T.J. Uebo (JF3HZB) A.K.A Tj Lab(JF3HZB)  https://github.com/tjlab-jf3hzb/Digital_VFO_with_analog_dial_V2.git
and...
It’s Not Just Another Digital VFO - Version 1.0 Developed By: John Price – WA2FZW, Glenn Percy – VK3PE and Jim Smith – G3ZQC
     
 *    Note: Arduino IDE version 2.3.4 was used with esp32 core version 3.0.7
 
 *    Uses a ESP32 WROVER DEV Kit (a 40-pin WROVER-E PSRAM board. Other WROVER boards may work (untested).
     
 *    Under Arduino IDE Tools menu select DIO flash mode, Esptool as programmer, and PSRAM Enabled. Otherwise, the ESP32 may not upload or run.
      I've noticed sometimes the ESP32 will refuse to be programmed while plugged into a PCB; Try removing the ESP32 module
      from the PCB and then upload the program.
   
 *    9600 BAUD Kenwood ST-2000 CAT Control Emulation by Barb (Barbaros ASUROGLU) - WB2CBA.
 *    KY-040 Encoder powered by 3.3V from ESP32. Uses ESP32 Rotary library ESP32Encoder library.
 *    240x240 dpi 1.54" ST7789 TFT Powered by 3.3V from ESP32.
 *    Si5351A module powered from +5V supply.
 *    Display driver is TFT_eSPI  https://github.com/Bodmer/TFT_eSPI
 *    Uses local modified copy of Si5351 library by Tj Lab(JF3HZB) https://github.com/tjlab-jf3hzb/Digital_VFO_with_analog_dial_V2.git
 *    Quadrature output down to 100kHz.
 *    Added set_drive_level() function to allow setting output level for each clock.
 *    Kicad V8 PCB design files are included.
***
![IMG_20241207_HDR](https://github.com/user-attachments/assets/58c91bbc-8729-42d1-ac4e-7053147a2246)
***
![pic_65_2](https://github.com/user-attachments/assets/c770457f-f190-4c7f-9e9f-50a07137bf31)
***
