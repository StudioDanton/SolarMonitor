# SolarMonitor
Solar Scintillation Seeing Monitor



The Solar Scintillation Seeing Monitor connects to an Arduino running "The inexpensive Solar Seeing Scintillation Monitor". (see design by E.J. Seykora https://www.ecu.edu/cs-cas/physics/upload/An-Inexpensive-Solar-Scintillation-Seeing-Monitor-Circuit-with-Arduino-Interface-final2.pdf) This device monitors Solar Scintillation and reports seeing values every second. The output is read, and represented in graphical form. (Green seeing values, blue input intensity, red moving average of seeing values). 
It is also a TCP server which will send the seeing and input values. Capturing programs like FireCapture can use these values to decide if seeing is good enough to capture solar images.
A special plugin for FireCapture is part of the project.


**Dependencies:**

Qt5
VS-2017 C++ Runtime (vc-redist64.exe)

Linux

To get access to the serial port, when the Arduino is connected, the user should be added to the dialout group.

*Windows*



*Max-OSX*

not tested or ported yet 


**Disclaimer**

The current version is still a pre-release and not guaranteed to work correctly in all situations and conditions. 

