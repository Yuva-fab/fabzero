# Roland Monofab SRM20 Milling Machine <br>
![Roland Monofab SRM20](img/monofab_SRM20.jpg)<br>
The SRM-20 portable milling machine can mill a broad range of materials, including modeling wax, chemical wood, foam, acrylic, poly acetate, ABS and PC board. <br>
Milling Made Easy with a User-Friendly VPanel.<br>
Following Softwares SRP Player, MODELA Player 4, ClickMill and SF Edit2 are require to editing, scaling and milling.<br>
# Procedure for PC board design and print <br>
--Open the KiCAD application. Go to File --> NEW---Click on Schematic Layout Editor<br>
--New Schema will open and then Select the components and Voltages with Proper connections.<br>
--Annotate schematic symbols <br>
--Run Electrical rules check <br>
--Assign PCB footprints to schematic symbols<br>
--Run PCBnew to layout printed circuit board <br>
--Draw thick copper routing between the components<br>
--Add Graphics line Edge.cuts <br>
--Select Plot and save in SVG format. While saving <br>
    *Select F.Cu and Edge.cuts in include layers <br>
    *Select Mirrored plot and Negative plot <br>
--Open both two files i.e. Trace and Cut in Inkscape software for convert SVG files to PNG file <br>
--Open fabmodules.org to convert from PNG to RML format to print the PCB in SRM20.<br>
--To print the PCB board, fix the 64 mm bit in SRM20 and move the bit using V plane software to origin point of PCB where circuit is going to start printing. And then click ORIGINATE. Set the X and Y Coordinates to 0 (zero).<br>
--Move the 64mm bit (in Z plane (up and down)) with help of yellanki, make the bit to touch the board and tight it.<br>
--In V Plane software set the Z axis coorinate 2mm (This is 2 mm above from PCB board).
--Then in V plane press CUT, a window will POP up. Delete the files which are displaying and add the Trace.rml file (Circuit design). Finally press OUTPUT button, then it will start milling the PCB.<br>
--After printed PCB, clean the bed with soft brush and replace the 64mm bit with 32mm bit.<br>
--Don't change X and Y ORIGINATE coordinates in V plane. Move the bit to starting point of PCB where CUT is going to start. Then help of yellanki make the bit to touch the board and tight it.<br>
--In V Plane software set the Z axis coordinate 2mm (This is 2 mm above from PCB board) and then click ORIGINATE. Set X and Y coordinates to 0 (zero).
--Then in V plane press CUT, a window will POP up. Delete the files which are displaying and add the CUT.rml file (Outer line of circuit). Finally press OUTPUT button, then it will start milling the outline.<br>
After finish the CUT, clean the bed with soft brush. With help of screw driver gently remove the PCB. PCB is ready.<br>
## Images of PC board design and Print <br>
![KiCAD Software](img/Kicad-schematiclayout-1.jpg)<br>

![KiCAD PCB Design](img/Add_Componets-2.jpg)<br>

![KiCAD PCB Design](img/Annotate-electricals-rules-check-3.jpg)<br>

![KiCAD PCB Design](img/Assign-PCB-footprints-to-schematic-symbols-4.jpg)<br>

![KiCAD PCB Design](img/PCBlayout-with-normal-connections-6.jpg)<br>

![KiCAD PCB Design](img/PCBlayout-with-copper-routing-7.jpg)<br>

![KiCAD PCB Design](img/PCBlayout-edgeCuts-8.jpg)<br>

![KiCAD PCB Design](img/PCBplot-in-svg-format-9.jpg)<br>

![KiCAD PCB Design](img/inkscape_PCBplot-svg2png_trace-10.jpg)<br>

![KiCAD PCB Design](img/inkscape_PCBplot-svg2png_cut-11.jpg)<br>

![KiCAD PCB Design](img/fabmodules-png2rml_trace-12.jpg)<br>

![KiCAD PCB Design](img/fabmodules-png2rml_cut-13.jpg)<br>

## Following are images of PC board printed at FAB LAB. <br>

![Monofab PCB print](img/Vplane-settings-14.jpg)<br>

![Monofab PCB print](img/Circuit-print-on-board-15.jpg)<br>

![Monofab PCB print](img/PCB-016.jpg)<br>

![Monofab PCB print](img/PCB-17.jpg)<br>





