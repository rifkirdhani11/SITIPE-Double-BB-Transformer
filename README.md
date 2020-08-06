# SITIPE-Double-BB-Transformer
Siemens Totally Integrated Power Engineering Automated Testing (SITIPE AT) is a computer aided test system to integrate and ease the steps of Functional Testing for substation automation, Telecontrol and protection panels manufactured by Siemens. 

<img width=400 src=https://github.com/rifkirdhani11/SITIPE-Double-BB-Transformer/blob/master/1.jpg>


SITIPE AT uses a USB PTM (Panel Test Module) to simulate the electrical output of the equipment at the substation while monitoring the electrical output of the system being tested. Our main contribution is to create a testing device by assembling the relay of USB PTM, making a GUI (Graphical User Interface) of testing, and making a simple test flow in a test case that is entirely used for 3 types of protection panels including Bus Coupler, Transformer, and Overhead Line (OHL).

<img width=400 src=https://github.com/rifkirdhani11/SITIPE-Double-BB-Transformer/blob/master/4.png>
GUI Display


PC users send commands via SITIPE AT to USB PTM to activate or monitor the relay address on the IED (Intelligent Electronics Device) installed on the panel, the two devices are connected by cable. The test is carried out starting from relay for Circuit Breaker, Disconnector, and Earthing Switch. In addition, SITIPE AT also has the IEC 61850 communication feature. The IED on the panel connected to the PC uses Ethernet Cable to send commands and receive indications from the IED. IEDs on the panel will provide signal feedback to the PTM USB which will be read by SITIPE AT and displayed in the GUI.

<img width=400 src=https://github.com/rifkirdhani11/SITIPE-Double-BB-Transformer/blob/master/2.png>
Block Diagram
