# SmartPDB
Centralized power distribution and control board developed for a University Rover Challenge rover architecture.
<br>

- Multiple regulated 12V power rails
- High current power distribution with electronic protection
- Integrated current and voltage sensing for system monitoring
- Designed with CAN integration to handle communication across the rover
- Integrates with the Jetson Orin AGX via an I2C bus
<br>

<div align="left">
  <img src="SmartPDB%203D.png" alt="SmartPDB 3D View" width="500px" style="display: block; margin-left: auto; margin-right: auto;">
</div>
<br>

## Board Layout
PCB layout optimized for high current routing, noise isolation, and serviceability in a mobile robotics environment.
<br>

- Wide copper pours for power integrity
- Logical subsystem grouping for debugging and maintenance
- Designed with competition reliability and field repair in mind
<br>

<div align="left">
  <img src="SmartPDB%20Layout.png" alt="SmartPDB PCB Layout" width="500px" style="display: block; margin-left: auto; margin-right: auto;">
</div>
<br>

## Project Status
This board is currently implimented in our competition rover, with Rev. 2 being designed to reduce size and add the capablity for a second CAN bus.
<br>
