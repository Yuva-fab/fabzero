# **Project Name - Network Alarm** (__Under Execution__)

Abstract - PING is command used to verify that a particular network device/server is alive or not. Ping works by sending an Internet Control Message Protocol (ICMP) Echo Request to a specified interface on the network and waiting for a reply.<br> 

If reply is any one of the following listed, the PCB will give audio alarm.<br>

    - Request timed out.
    - Net unreachable.
    - Host unreachable.
    - Protocol unreachable.
    - Port unreachable.
    - Source route failed.

This will be useful for Network Administrators for troubleshooting network problems quickly.

## To design the PCB following list of Equipment, Components, Softwares and Tools used.<br>

### Name of the equipment.<br>

    - Monofab SRM20 - To print the PCB.

### Name of the components are used.<br>

    - 8 bit Atmega 328P-AU Microcontroller - 1 No.
    - 6 pin AVR ISP                        - 1 No.
    - 6 pin Serial Communication Interface - 1 No.
    - 10 K ohm Resistors                   - 1 No.
    - 500 K ohm Resistors                  - 1 No.
    - 100 Micro farad Capacitor            - 1 No.
    - Switch/Push button                   - 1 No.

### Name of the Softwares Used.

    - KiCAD 5   - To design the PCB traces and outline.
    - Inkscape  - To convert the SVG file to PNG file.
    - GIMP      - To make the holes in PCB.
    - http://fabmodules.org/ - To convert the PNG file to RML                             file.

### Name of the Tools.

    Soldering Iron.       
    - To used for soldering the components on the PCB.

## **Procedure for PC board design and print**<br>

--Open the KiCAD application. Go to File --> NEW---Click on Project <br>

--New Schema will open and then Select components. Make the connections properly.<br>

--Annotate schematic symbols <br>

--Run Electrical rules check <br>

--Assign PCB footprints to schematic symbols<br>

--Generate Net List <br>

--Press F8 (OR) Go to Tools--> select Update PCB from Schematic layout <br>

--Run PCBnew for layout printed circuit board <br>

--Draw thick copper routing between the components<br>

--Add Graphics line Edge.cuts <br>

--Select Plot and save in SVG format. While saving <br>

    **Select F.Cu and Edge.cuts in include layers** <br>
    **Select Mirrored plot and Negative plot** <br>

--Two file will be generated (Trace and Outline) and saved in the SVG format.<br>

--Open both two files i.e. Trace and Cut in Inkscape software for converting SVG files to PNG file. While exporting choose 2000 dpi. <br>

--Open fabmodules.org to convert from PNG to RML format to print the PCB in SRM20.<br>

--To print the PCB board, fix the 64 mm bit in SRM20 and move the bit using V panel software to origin point of PCB where circuit is going to start printing. And then click ORIGINATE. Set the X and Y Coordinates to 0 (zero).<br>

--Move the 64mm bit (in Z plane (up and down)) with help of yellanki, make the bit to touch the board and tight it.<br>

--In V Plane software set the Z axis coordinate 2mm (This is 2 mm above from PCB board).<br>

--Then in V panel press CUT, a window will POP up. Delete the files which are displaying and add the Trace.rml file (Circuit design). Finally press OUTPUT button, then it will start milling the PCB.<br>

--After printed PCB, clean the bed with soft brush and replace the 64mm bit with 32mm bit.<br>

--Don't change X and Y ORIGINATE coordinates in V panel. Move the bit to starting point of PCB where CUT is going to start. Then help of yellanki make the bit to touch the board and tight it.<br>

--In V panel software set the Z axis coordinate 2mm (This is 2 mm above from PCB board) and then click ORIGINATE. Set X and Y coordinates to 0 (zero).<br>

--Then in V panel press CUT, a window will POP up. Delete the files which are displaying and add the CUT.rml file (Outer line of circuit). Finally press OUTPUT button, then it will start milling the outline.<br>

After finish the CUT, clean the bed with soft brush. With help of screw driver gently remove the PCB. PCB is ready.<br>

## Images of PC board design and Print <br>
![KiCAD Software](proj-img/Kicad-schematiclayout-1.jpg)<br>

![KiCAD PCB Design](proj-img/Add_Componets-2.jpg)<br>

![KiCAD PCB Design](proj-img/Annotate-electricals-rules-check-3.jpg)<br>

![KiCAD PCB Design](proj-img/Assign-PCB-footprints-to-schematic-symbols-4.jpg)<br>

![KiCAD PCB Design](proj-img/PCBlayout-with-normal-connections-6.jpg)<br>

![KiCAD PCB Design](proj-img/PCBlayout-with-copper-routing-7.jpg)<br>

![KiCAD PCB Design](proj-img/PCBlayout-edgeCuts-8.jpg)<br>

![KiCAD PCB Design](proj-img/PCBplot-in-svg-format-9.jpg)<br>

![KiCAD PCB Design](proj-img/inkscape_PCBplot-svg2png_trace-10.jpg)<br>

![KiCAD PCB Design](proj-img/inkscape_PCBplot-svg2png_cut-11.jpg)<br>

![KiCAD PCB Design](proj-img/fabmodules-png2rml_trace-12.jpg)<br>

![KiCAD PCB Design](proj-img/fabmodules-png2rml_cut-13.jpg)<br>

## Following are images of PC board printed at FAB LAB. <br>

![Monofab PCB print](proj-img/Vplane-settings-14.jpg)<br>

![Monofab PCB print](proj-img/Circuit-print-on-board-15.jpg)<br>

![Monofab PCB print](proj-img/PCB-016.jpg)<br>

![Monofab PCB print](proj-img/PCB-17.jpg)<br>

![Monofab PCB print](proj-img/tools-for-pcb-design-18.jpg)<br>

![Monofab PCB print](proj-img/Soldered-PCB-19.jpg)<br>


## Following is the procedure for programming the PCB. <br> 

## Following is the sample PCB programming. <br>

## Following images are testing of programmed PCB. <br>