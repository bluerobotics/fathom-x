#Fathom-E

The Fathom Tether Boards are part of Blue Robotics' *Fathom Tether*. These boards provide interfaces and functionality for the communication methods used with the tether. With the Fathom tether, it is quick and easy to get up and running and interface with your ROV or other application.

The schematic and board layout are designed in EagleCAD.

#Fathom-E (Ethernet) Hardware

##Description

The Fathom-E Hardware is designed for applications using a simple microcontroller for ROV control. It is meant to be an all-inclusive tether interface. The power switching capability allows small ROVs to be completely powered through the switched battery power connection with 20A continuous and 40A burst current ratings. Larger systems with higher current or voltage requirements must use an external power switching circuit or rely on plug/unplug power systems.

The Fathom-E Hardware is designed to be used with tether cables that have four twisted pairs, preferrably similar to Cat5 cable. The design is based on the tether cables available from Blue Robotics, but will also work with standard Cat5 network cable.

##Features 

* Low Latency Analog Video through NTSC or PAL (Up to 2000 ft, 600m)
* 10/100 Ethernet Connection 
* Power switch that uses a 3-50V input signal to connect batteries and provide up to 40A continuous
* Onboard 3.3V, 5V, and 12V (camera) regulated supplies
* Jumpers to enable/disable configuration options
	* Power-on through tether / power always on when batteries connected
	* Power board from battery / power board from alternate input
* 0.1" I/O header for ribbon cable to ROV controller
* Current and voltage sense outputs

##Configuration

###Fathom Ethernet Onboard

[Image with arrows]

###Fathom Ethernet Topside

[Image with arrows]

##Electrical Ratings

| Value                              | Minimum | Nominal | Maximum | Unit    |
|-----------------------------------:|:-------:|:-------:|:-------:|:--------|
| Battery Input Voltage              | 7       | 12      | 27      | V       |
| Power-on Signal Voltage            | 3       | 5       | 50      | V       |
| Switched Battery Output Current    |         | 20      | 40      | A       |

##Example Setups

Examples TBD

##Physical Specifications

Dimensions, screw holes, wire gauges, etc.

##License

The Fathom Ethernet Hardware Design is released under the MIT License.

##Revision History

0.0 - Under development