# Alunar_M508_Firmware

Stock firmware for the Alunar M508 3D printer. The one edit I had to do to the firmware was to the direction of the extruder. I am not sure if it is a hardware issue for me, but it was easier to fix it in software. If your direction is going backwards you can edit the same line in the file "Configuration.h." Search the term "extruderreverse" it will take you to the line you need to change to "false." 

![Schematic](https://github.com/dplumly/Alunar_M508_Firmware/blob/master/img/Screen%20Shot%202017-11-09%20at%202.06.59%20PM.png)

I used Arduino 1.5.4 on a mac to upload the code to the board. You can find the Arduino IDE here: https://www.arduino.cc/en/Main/OldSoftwareReleases
