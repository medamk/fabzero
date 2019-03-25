
 Installed KICAD 5 Application for PCB Making.  

 - open the KICAD application  
 - File --> NEW
 - Click on Schematic Layout Editor
 - New Eeschema will open. then Select the components and Voltages with Proper 
 connections. 

![kicad](images/kicadsch.jpg)
 - Perform Electronic Rules Check. If there is No Errors
 - Then click on assign PCB footprints
 - Assign the Components from footprint libraries  

![kicad](images/kicadfp.jpg)

 - Save and Press F8
 - Give the all connections and  border
 ![kicad](images/pcblayout.jpg)
 - Click on Plot. Select F.cu and Edge.cuts only
 - Select negative plot and mirrored plot. Then Click on Plot.
 ![kicad](images/plot3d.jpg)

- then two files will be saved in.svg files.
- open each .svg file in inkscape application. Then Export in .PNG file.
- open the website http://fabmodules.org/ to convert into .camm file  
- input the .png file. Select the Roland mill and PCB Trace(1/64). then save the file
![kicad](images/millstrace.jpg)

- input the .png file. Select the Roland mill and PCB outline(1/32). then save the file
![kicad](images/millscut.jpg)