Instructions to have the biofeedback show up in the Arduino device list. 
 
1) Download the latest biofeedback-mega.zip file and extract it.	
2) You will need to be using a recent version of the Arduino environment, version 1.0.5 or later.
3) Create a 'hardware' directory inside your sketches folder. 
4) Copy the biofeedback-mega directory into the hardware directory.
5) Restart the Arduino software. New boards will appear in the Tools > Board menu. 


Notes:
the cores for the mega board uses \variants\mega\pins_arduino.h that has additional pins as defined by Seeediunos mega
where the "arduino:arduino" [platform:subfolder] is used for the core.

The bootloader likewise uses SFEs "mega-pro-3.3V:" [platform:subfolder]
