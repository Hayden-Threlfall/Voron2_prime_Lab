# Voron2_prime_Lab
VORON 2.4 R1 Instructions:

Plug into the ethernet in the back of the printer then go to any browser and type in: mainsailos.local
(or a hotspot at Temp98, pas: Tmp22922)

Slicers and Printer Profiles 
Here is the Identity of the Printer: Voron 2.4 (R1) 350mm

Super Slicer Profiles (Recommended):
Download the latest Super slicer, select a printer in the menu and download and import the profiles. Make sure to change the temperatures for the filament.
Import Profiles from link.
https://github.com/AndrewEllis93/Ellis-SuperSlicer-Profiles/tree/master/SuperSlicer/CoreXY%20Speeds%20-%20Input%20Shaper/High%20Flow%20Hotend%20(24mm3)

Cura:
Go to add a printer, Offline printer, then add the Voron.

Any other slicer: 
The important part of any slicer for this printer is to add go to the start and end Gcode section, “start_print” and “end_print” in their respective sections. 

Login for rapi: 
pi
ras 

If you have any issues with the interfaces look up the documentation for Klipper, Mainsail.

Tuning information: 
https://ellis3dp.com/Print-Tuning-Guide/, or official Voron documentation

Temporary github: https://github.com/Hayden-Threlfall/Voron2_prime_Lab
If you need any help ask the discord.
