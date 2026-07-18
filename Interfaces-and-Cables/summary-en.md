This video focuses on the physical components that connect computers together: Interfaces (Ports) and Cables.

1. Interfaces and Ports
An Interface (also called a Port) is the physical socket on a device where you plug in a network cable.

A standard Ethernet socket is called an RJ-45 Port.

The port translates physical signals (like electricity or light) into binary code (Bits: 0s and 1s) that the computer can process.

2. Network Speed: Bit vs. Byte
Bit: The smallest unit of data (0 or 1). Network speeds are measured in bits per second (e.g., Mbps or Gbps). Data travels through a cable one bit at a time.

Byte: A group of 8 bits. Bytes are used to measure file sizes and disk storage (e.g., a 500GB SSD), not network speed.

3. Ethernet Standards (IEEE 802.3)
IEEE is an organization that makes global rules so equipment from different brands (like Cisco, Dell, HP) can talk to each other.

The standard for wired networks is 802.3.

The 100-Meter Rule: Copper Ethernet cables can only carry signals reliably up to 100 meters. After 100 meters, the signal becomes weak (Attenuation), causing drops.

When you read 10/100/1000Base-T on a switch:

10 / 100 / 1000: The speeds the port supports in Megabits per second (Mbps).

Base: Baseband transmission.

T: Twisted Pair cabling.

4. Twisted Pair Cables (Copper)
Inside the cable, there are 8 small copper wires twisted into 4 pairs. They are twisted to cancel out electromagnetic fields that cause interference.

UTP (Unshielded Twisted Pair): Basic cable with no extra metal shielding. Very common but prone to interference.

STP / FTP (Shielded): Cables wrapped in metal foil to protect the data signals from outside electrical noise.

5. Straight-Through vs. Cross-Over
The 8 wires connect to numbered pins (1 to 8) inside the plastic RJ-45 connector.

End Devices (PCs, Routers): Transmit (TX) data on pins 1 & 2, and Receive (RX) data on pins 3 & 6.

Switches: Receive on 1 & 2, and Transmit on 3 & 6.

Straight-Through Cable: Pin 1 connects to Pin 1, Pin 2 to Pin 2, etc. It connects different devices (e.g., PC connected to a Switch).

Cross-Over Cable: Wire 1 connects to Pin 3, Wire 2 connects to Pin 6. It connects similar devices (e.g., Switch to Switch, or PC to PC).

Auto-MDIX: A smart feature in modern devices that automatically senses the connected device and adjusts the pins electronically. Thanks to this, we rarely need cross-over cables today.

6. Fiber Optic Cables
Instead of electricity, Fiber Optics transmit pulses of light through glass. They do not use RJ-45 ports; they use SFP transceivers to plug into switches.

Multi-Mode (MM): Has a wider glass core. Light bounces inside at multiple angles. Used for short distances (inside a building) and uses cheaper LED light.

Single-Mode (SM): Has a very thin glass core. Light travels in a single straight line using a precise laser. Used for very long distances (between cities) and is more expensive.
