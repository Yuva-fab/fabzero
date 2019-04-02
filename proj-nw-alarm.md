# **Project Name - Network Alarm** (__Under Execution__)

Abstract - PING is command used to verify that a particular network device/server is alive or not. Ping works by sending an Internet Control Message Protocol (ICMP) Echo Request to a specified interface on the network and waiting for a reply.<br> 

If reply is any one of the following listed, the PCB will give audio alarm.<br>

    - Request timed out.<br>
    - Net unreachable.<br>
    - Host unreachable.<br>
    - Protocol unreachable.<br>
    - Port unreachable.<br>
    - Source route failed.<br>

This will be useful for Network Administrators for troubleshooting network problems quickly.

## To design the PCB list of Equipment, Components and Softwares used.<br>

### Name of the equipment.<br>

    - Monofab SRM20 - To print the PCB.

### Name of the components used.<br>

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