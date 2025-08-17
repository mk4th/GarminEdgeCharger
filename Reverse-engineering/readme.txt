Here I'll upload some reverse engineering from my current Power Pack

Picture description:
•	5-Pads: is a picture of the 5 pads on the PCB. Those have 5 pogo pins that link them to another set of pogo pins, which actually touches the Edge computer. I gave them numbers; 1 as VCC and 5 as GND. 2 and 4 seems not connected. Pad #3 is connected through a resistor and via to <IDK, will find out later>. The resistor had two (reverse polarity?) protection diodes. DigiKey says that this resistor is a 1k ohm.
•	BatConn: Is the battery connector. Because it has 2S configuration, it has a bat+, a common between the two and a GND. It also has a temperature sensor.
•	ID: is a close up on the ID pad related components.
•	OrgBat: is some info about the original battery cell. It has the manual measurements that I took and the printed number that also hold information about the size.
•	Pack: is the decal on the pack 7.6V and 2220mAh results in somewhat above the 16.8Wh. Divide it by 5V, and you will get 3.37Ah, which is slightly higher than the declared 3.3Ah.
•	Main Chip: is well… the main chip in the board. That seems as the ACT2804.
•	PCB_ContactSide and PCB_ConnectorsSide: Wide view of the PCB from both sides.
•	PCB_#: General pictures of the PCB compenents.
•	Active#1: Seems to some power compnent. TBD
•	Active#2: TBD.

Next:
•	Determine active components.
•	To find where the ID via leads
•	Measure the pads under load
