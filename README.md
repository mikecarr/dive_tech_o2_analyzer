# DiveTech O2 Analyzer

See https://www.divetech.com/post/the-20-nitrox-analyzer for parts list and design

DISCLAIMER: This is a DIY project. Know that making your own nitrox analyzer could be very dangerous if you do something wrong. The risk of not knowing exactly what you are breathing when you go diving could be fatal, so use at your own risk. You've been warned.


I am making some changes to the code that is found here: https://ejlabs.net/tmp/o2_analyzer.ino

Text Size Issues
2 is too big and 1 is too small

"this is an old post but i had the same problem with scaling the font size. I have changed all variables called TextSize in Adafruit_GFX.cpp and Adafruit_GFX.h from int (uint8_t, int16_t) to float. Now i can granularly change font size to values like 1.2, 1.5 etc.."

https://github.com/adafruit/Adafruit_SSD1306/issues/88
https://drive.google.com/drive/folders/1s5irKeFCHLMgdhiwgaWbUYswknHlWh12?usp=sharing