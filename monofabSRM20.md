# Roland Monofab SRM20 Milling Machine <br>
![Roland Monofab SRM20 Image](img/monofab_SRM20.jpg)<br>
The SRM-20 portable milling machine can mill a broad range of materials, including modeling wax, chemical wood, foam, acrylic, poly acetate, ABS and PC board. <br>
Milling Made Easy with a User-Friendly VPanel.<br>
Following Softwares SRP Player, MODELA Player 4, ClickMill and SF Edit2 are require to editing, scaling and milling.<br>
# Procedure for PC board print <br>
--Open the KiCAD application<br>
--File --> NEW<br>
--Click on Schematic Layout Editor<br>
--New Schema will open and then Select the components and Voltages with Proper connections.<br>
--Annotate schematic sysmbols <br>
--Run Electricals rules check <br>
--Assign PCB footprints to schematic symbols<br>
--Run PCBnew to layout printed circuit board <br>
--Draw thick copper routing between the components<br>
--Add Graphics line Edge.cuts <br>
--Select Plot and save in SVG format. While saving <br>
    -Select F.Cu and Edge.cuts in include layers <br>
    -Select Mirored plot and Negative plot <br>
--Open both two files i.e. Trace and Cut in Inkscape software for convert SVG files to PNG file <br>
--Open fabmodules.org to convert from PNG to RML format to print in SRM20

# Following is the PC board printed at FAB LAB. <br>





