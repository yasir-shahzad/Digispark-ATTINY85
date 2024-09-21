# Digispark-ATTINY85
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Commits since latest](https://img.shields.io/github/commits-since/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/latest)](https://github.com/yasir-shahzad/Digispark-ATTINY85/commits/master)
[![GitHub issues](https://img.shields.io/github/issues/yasir-shahzad/STM32-ST-Link-V2.0-Programmer.svg)](https://github.com/yasir-shahzad/Digispark-ATTINY85/issues)
![Hit Counter](https://visitor-badge.laobi.icu/badge?page_id=yasir-shahzad_Digispark-ATTINY85)

If you like **STM32-ST-Link-V2.0** - give it a star, or fork it and contribute!
[![GitHub stars](https://img.shields.io/github/stars/yasir-shahzad/Digispark-ATTINY85.svg?style=social&label=Star)](https://github.com/yasir-shahzad/Digispark-ATTINY85/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yasir-shahzad/Digispark-ATTINY85.svg?style=social&label=Fork)](https://github.com/yasir-shahzad/Digispark-ATTINY85/network)

This repository contains the open-source schematic and PCB design files for an ST-Link V2.0 clone, created using Altium Designer. This clone allows you to program and debug STM8 and STM32 microcontrollers.


## Need Help with Embedded Systems or Hardware Design?
I offer professional services for embedded systems design and hardware development at competitive rates starting at **$10/hour**. If you're looking for assistance with your next project, feel free to contact me:

<p align="left">
<a href="https://www.facebook.com/yasirshahzad918/" target="blank"><img align="center" src="path/to/facebook-icon.svg" alt="Facebook Profile" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/yasirshahzad18/" target="blank"><img align="center" src="path/to/linkedin-icon.svg" alt="LinkedIn Profile" height="30" width="40" /></a>
<a href="https://www.instagram.com/mastermind.pk/" target="blank"><img align="center" src="path/to/instagram-icon.svg" alt="Instagram Profile" height="30" width="40" /></a>
<a href="https://twitter.com/yourprofile" target="blank"><img align="center" src="path/to/twitter-icon.svg" alt="Twitter Profile" height="30" width="40" /></a>
<a href="https://www.fiverr.com/yourprofile" target="blank"><img align="center" src="path/to/fiverr-icon.svg" alt="Fiverr Profile" height="30" width="40" /></a>
<a href="https://www.upwork.com/yourprofile" target="blank"><img align="center" src="path/to/upwork-icon.svg" alt="Upwork Profile" height="30" width="40" /></a>
</p>


## Schematic Diagram
![Schematic Diagram](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/blob/master/images/Schematic.png)

## PCB Files
![PCB Board](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/blob/master/images/PCB.png)

## Features
- 5 V power supplied by a USB connector
- USB 2.0 full speed compatible interface
- USB standard A to mini B cable
- SWIM specific features
- 1.65 V to 5.5 V application voltage supported on SWIM interface
- SWIM low-speed and high-speed modes supported
- SWIM programming speed rate: 9.7 Kbytes/s in low speed and 12.8 Kbytes/s in high speed
- SWIM cable for connection to the application via an ERNI standard vertical (ref: 284697 or 214017) or horizontal (ref: 214012) connector
- SWIM cable for connection to the application via a pin header or a 2.54 mm pitch connector
- JTAG specific features
- 1.65 V to 3.6 V application voltage supported on the JTAG interface and 5 V tolerant inputs
- JTAG cable for connection to a standard JTAG 20-pin pitch 2.54 mm connector
- Direct firmware update feature supported (DFU)
- Status LED which blinks during communication with the PC
- Operating temperature 0 to 50 °C

## Requirements

- Altium Designer (or a compatible viewer)
  
## Screenshots :eyes:

<table>
  <tr>
    <th>
        <a href="images/Top3D.png" target="_blank">
        <img src='images/Top3D.png' width='200px' alt='image missing' /> </a>
    </th>
    <th>
        <a href="images/Bottom3D.png" target="_blank">
        <img src='images/Bottom3D.png' width='200px' alt='image missing' /> </a>
    </th>  
    <th>
        <a href="images/Top_Layout.png" target="_blank">
        <img src='images/Top_Layout.png' width='200px' alt='image missing' /> </a>
    </th>
    <th>
        <a href="images/Bottom_Layout.png" target="_blank">
        <img src='images/Bottom_Layout.png' width='200px' alt='image missing' /> </a>
    </th>
  </tr>
</table>

## Getting Started

1. **Download the repository**: Click "Clone or download" on the green button above.
2. **Open the project**: Use Altium Designer to open the `.PrjPCB` file located in the main directory.
3. **Review the schematics**: The `schematic.SchDoc` file shows the electrical connections and components used in the design.
4. **Examine the PCB layout**: The `PCB.PCBDoc` file represents the physical layout of the components on the printed circuit board.
5. **Generate BOM (optional)**: Use Altium Designer's BOM generation features to create a list of required components.

## Additional Information

- **Firmware**: This repository does not include the firmware. You'll need to obtain the official ST-Link V2.0 firmware from [link](https://github.com/GMMan/st-link-hack/blob/master/upgrade/upgrade.md)
- **Assembly instructions (optional)**: Consider adding a separate document or webpage with detailed instructions on soldering and assembling the PCB (if applicable).
- **License**: Specify the open-source license used for the design files (e.g., MIT License).

## Contributing

We encourage contributions to this project! Feel free to submit pull requests with improvements, bug fixes, or additional features.

