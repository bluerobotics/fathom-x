# Fathom-X and Fathom-E

The Fathom-X and -E Tether Boards are part of Blue Robotics' *Fathom Tether* system. These boards provide interfaces and functionality for the communication methods used with the tether. With the Fathom tether, it is quick and easy to get up and running and interface with your ROV or other application.

The schematic and board layout are designed in EagleCAD.

# Fathom-E (Simple Ethernet) Hardware

## Description

The Fathom-E board provides a simple and economical way to connect the Fathom Tether or a Cat5 cable to an Ethernet jack. It uses all four twisted pairs in the cable and works for tether lengths of up to 100m (per the Ethernet specification).

# Fathom-X Hardware

The Fathom-X board has a few advantages over the Fathom-E interface. It uses a HomePlugAV (IEEE1901) module to send 100 Mbps Ethernet with a single twisted pair. This robust connection works over at least 300m tether lengths. 

Please see the [official documentation](http://docs.bluerobotics.com/fathom-x/) for more information.

## License

The Fathom Ethernet Hardware Design is released under the MIT License.

## Revision History

### Fathom-E 

rev1 - Works but RJ45 misaligned

rev2 - Production version

### Fathom-X

rev1 - Works but poor tether connector used

rev2 - Production version with updated connector