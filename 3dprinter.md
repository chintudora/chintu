# 3D Printer
Then they taught us about 3d printer operation and how it works. Explained operation of 3d printing and its components.
![fabzero](img/3d1.jpg)
# What is 3D-printing?
3D printing is a process where a three-dimensional object is made by joining material in a computer controlled way. There are several techniques to join the material; melting plastic and laying it on top of each other (FDM or fused deposition modeling), fusing powder together or fusing liquid molecules together. 
The 3DWOX printer makes objects by stacking different layers of molten plastic on top of each other.
3D-printing can be used for didactical material, design objects, technical pieces, toys, medical purposes.
# Different steps
There are different steps needed to create a physical object with printing.
•	First there is a computer model needed.
•	The model needs to be translated to a model that the 3D printer can read.
•	Print the object on the printer.
•	Post-processing.
# Exercise
1.	Import files in 3DWOX
In this tutorial we will start from an already existing 3D-file. You will learn how to import this 3D-file in the software of our 3D-printer (3DWOX).
2.	Change settings in 3DWOX
You will learn how to adapt a file in 3DWOX to achieve the best printing result. You will learn how to scale the model, change the orientation of the model, define the layer thikness and create support.
3.	Send file to printer
You will learn how to send the printable code from 3DWOX to the printer by wifi or by USB-drive.
4.	Print
You will be able to start the printer and print the model.
5.	Post-process 
Learn how to clean up the 3D printed model.
# Download online models
Some people put their drawn 3D-models online. Some interesting sites to download 3D-models are grabcad , My mini factory , youmagine and thingiverse 
# transform to printable file
# 3D-Printing with Sindoh 3DWOX - Getting Started 
# software 3DWOX
# 3DWOX
3DWOX is the software for the 3DWOX printer. A 3D printer can only print a model layer by layer. These layers needs to specified. 3DWOX is a kind of program, called a slicer, that converts the 3D models that we have into this bunch of stacked layers.
# Software download
Click here to download the software 3DWOX. Everything printed on the 3DWOX printer needs to be sliced in this software.
# Setup software for first use with the printer
choose printer
•	Start by opening up the Sindoh 3D WOX software.
•	Set up the type of 3D-printer. 
Go to settings > printer settings. Choose the printer model, in this case it’s the “DP201”. This will make sure that the software will generate the correct code for our 3D-printer.
# Set Up 3D-model for 3D-printing
# Load/import 3D-model
Import a 3D-model. This needs to be a .STL, .OBJ or .PLY file. Click the Load folder icon on the top left corner of the screen, select your 3D-file in the browser, and click “open.” The model will now show up on the build platform.
# Navigation
There are 3 different ways to move around in the slicer in order to inspect the model.
# Move point of view
right clicking the mouse and drag, this will orbit the view. 
# Pan around
Hold shift button on the keyboard while right clicking the mouse and dragging.
# Zoom in and out
Use the scroll wheel of the mouse 
# 3D-Printing with Sindoh 3DWOX - Print setup 
# slices
A 3D printer prints an object in different layers of plastic. The 3DWOX software will convert a 3D model in a code readable for the printer. The view sliced layers simulates these printable layers.
•	View sliced layers of model: click “layer viewer” icon. ( third icon from the top right)
•	There might be a warning that the software detected a “overhang region” and that there is support needed in order to print this object successfully. If this is the case click "ok" and read the chapter 'overhang region'
•	scroll through layers of sliced object: slider on right bottom of the screen.
You will notice that the model is converted in a bunch of colored layers. Notice that, at the bottom of the model, a couple of blue layers are added. These layers are called a 'raft', they ensure that the part will be well connected to the bed while printing. This raft can be easily teared off after printing. 
# Overhang region
The warning message tells us that a large part of the print is not supported. 
The printer is melting the plastic layers on top of each other. So whenever the printer is laying down molten plastic, it needs a solid layer beneath it to make sure that it is supported. 

When the printer has to print something “in the air” the molten plastic will just drop down to the bed and the print will look like a bunch of plastic spaghetti soup instead of a chair. 
As long as the printer is printing the legs of the chair, everything will be okay, but the seat is “flying” in the air and thus unsupported.
# Support
The overhang region problem can be solved by using support structures. This function will generate additional geometry to our object that can be removed after the printing process.
•	Turn on support: Click the "settings" icon (left of the screen, underneath load icon)
Under support > placement there are three options:
•	“none” will print the object without any additional support structures
•	“touching buildplate” will only generate structures where the overhang region is directly above the build plate
•	“everywhere” will also generate support structures if the overhang is directly above another piece of our object.
# orientation
Since all of the support material is technically just waste, we are better off limiting the amount of support material as much as possible. 
The most important factor here is printing orientation. 
# Change orientation
•	Change the view back to “3D model viewer”
•	change the orientation: click the 2 circular arrows on the right hand side of the screen. Select the object you want to rotate, it will glow in a blue hue, and then you can dial in a rotation angle to orient the object as you like.
•	automatically search a flat side on your object: click “lay flat” button
•	Once your done changing the orientation, you can go back to the sliced view by clicking 'slices' in the top right corner.
# Quality and speed
The print profile has the biggest influence on the printing process. Choosing a fast speed will not increase the actual speed of the printer, but it will slice your 3D-object in thicker slices thus resulting in fewer layers, reducing the overall print time but also reducing the quality of your print. The slow speed setting will create thinner layers that will take longer to print but result in a higher quality finish. The normal settings are a trade-off between the two extremes.
# Change quality and speed
•	click "settings"
•	under quick print profile the speed can be chosen. There are 4 options. The faster the speed, the thicker the layer thickness and the less detail in the print.
# Send to printer
# 3D-Printing with Sindoh 3DWOX - Export print 
# Send to printer
When the print is set up correctly and you have added the support (if needed) we can send our file over to the 3D-printer. There are two options, send the file to the printer over the local network or save it to a USB flash drive.
# Upload via network
# connect to wireless network
•	Power on the printer and go to the “Settings” > “Network” menu > “Choose a network…”
•	Select your network and enter the password.
•	Once everything is connected, go back to the main menu and select the “info” tab where you should now be able to see a Wireless IP. Every object (computer, printer,..) connected to the internet has an IP-adres to be able to communicate with other objects on the internet. By using this IP number we can link our computer with the printer. Write down this number, you will need this in the next step.
# pair the printer in the software
•	To pair the printer to your computer, go to “Printer” > “Add Network Printer”.
•	If the 3D-printer doesn’t automatically show up in here you can click the “Find printer by IP address” and manually enter the IP you have written down in the step aboves.
•	The printer will now show up on the left side of the screen, and it will show which color is loaded (blue) and how much material it still has left.
•	Click the print icon on the right side, click print and OK. The print will now start and you can monitor it by going to the “Printer” > “Web monitoring” tab. You will get a webcam view
# print by USB
•	Go to file and then “Save G-code” and select a USB-drive.
•	Insert this USB-drive in the 3D-printer, go to “Print” and select the file you want to print.
•	A preview will pop-up on the display, now you just have to press the play icon in order to start the print. The printer will remind you to check whether the building platform is clear before you start the print.
# Post-process
# 3D-Printing with Sindoh 3DWOX - Post process 
# Remove print
When the print is finished, you can simply remove the silicone top sheet of the bed by lifting it up, it is magnetically attached to the bed itself. Now flex the sheet a little bit and the print will detach. Be careful when you reinstall the silicone sheet and make sure that it touches the back side of the metal bed. 
# Clean-up
The only thing that is left to do is cleaning up the print. We have to remove the support- and bed adhesion structures. This is easily done with a small pair of pliers.
# Maintenance
# 3D-Printing with Sindoh 3DWOX - Maintenance 
# Bed leveling
For an optimal printing result, the build plate should be perfectly aligned to the printing head. 
If this is not the case, prints might not attach to the bed properly, or come loose while printing.
•	If the bed is not leveled, you can use a specific function in the settings menu to fix this issue. Go to “setting” > “bed leveling” and this will start the leveling routine.
•	The printing head will measure the height of bed on different locations and will ask you to compensate for the difference in height if necessary. It will ask you to rotate the wheels a couple of clicks in a certain direction to make sure that the bed is level again.
# Cleaning case
The printer might show a sign: clean case. Click ok and pull out the cleaning case, empty the cleaning case and put it back in. 
# Unloading filament
•	To unload te filament click Cartridge > unload > OK.
•	The printer will now heat up the nozzle so the filament can be retracted. This will roll back the filament and collect it on the spool.
•	The cartridge is now ejected and can be removed.
# Fill cartridge
•	Use the slider button on the left of the cartridge to open it up and reveal the spool, which can now be changed out with a new one or a different color.
•	Place the new spool in the correct place and feed the end of the filament into the guiding tube. Be sure to check whether you can see the filament move forward when you manually turn the extruder wheel, the wheel that is located inside the cartridge. This will make sure that the printer will be able to automatically load the filament once it is installed back in the 3D-printer.
•	Also remember to swap the chip out for the one that corresponds with the correct filament roll. You can now close the cartridge.
# Loading filament
Slide the cartridge back into the machine.The printer will automatically ask if you want to load the filament and just pressing OK is all we have to do. 
![fabzero](img/3d.jpg)
![fabzero](img/3d2.jpg)
