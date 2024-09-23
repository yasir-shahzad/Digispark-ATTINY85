# Digispark-ATTINY85
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)  
[![Commits since latest](https://img.shields.io/github/commits-since/yasir-shahzad/Digispark-ATTINY85/latest)](https://github.com/yasir-shahzad/Digispark-ATTINY85/commits/master)  
[![GitHub issues](https://img.shields.io/github/issues/yasir-shahzad/Digispark-ATTINY85.svg)](https://github.com/yasir-shahzad/Digispark-ATTINY85/issues)  
![Hit Counter](https://visitor-badge.laobi.icu/badge?page_id=yasir-shahzad_Digispark-ATTINY85)

If you like **Digispark-ATTINY85** - give it a star, or fork it and contribute!  
[![GitHub stars](https://img.shields.io/github/stars/yasir-shahzad/Digispark-ATTINY85.svg?style=social&label=Star)](https://github.com/yasir-shahzad/Digispark-ATTINY85/stargazers)  
[![GitHub forks](https://img.shields.io/github/forks/yasir-shahzad/Digispark-ATTINY85.svg?style=social&label=Fork)](https://github.com/yasir-shahzad/Digispark-ATTINY85/network)


[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Commits since latest](https://img.shields.io/github/commits-since/yasir-shahzad/Digispark-ATTINY85r/latest)](https://github.com/yasir-shahzad/Digispark-ATTINY85r/commits/master)
[![GitHub issues](https://img.shields.io/github/issues/yasir-shahzad/Digispark-ATTINY85r.svg)](https://github.com/yasir-shahzad/Digispark-ATTINY85r/issues)
![Hit Counter](https://visitor-badge.laobi.icu/badge?page_id=yasir-shahzad_Digispark-ATTINY85)

If you like **Digispark-ATTINY85** - give it a star, or fork it and contribute!  
[![GitHub stars](https://img.shields.io/github/stars/yasir-shahzad/Digispark-ATTINY85r.svg?style=social&label=Star)](https://github.com/yasir-shahzad/Digispark-ATTINY85r/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yasir-shahzad/Digispark-ATTINY85r.svg?style=social&label=Fork)](https://github.com/yasir-shahzad/Digispark-ATTINY85r/network)



This repository contains the open-source schematic and PCB design files for a **Digispark ATTINY85** development board clone, created using Altium Designer. This board allows you to work with the ATTINY85 microcontroller using the Digispark platform.

## Need Help with Embedded Systems or Hardware Design?

I offer professional services for embedded systems design and hardware development at competitive rates starting at **$10/hour**. If you're looking for assistance with your next project, feel free to contact me:

<a href="https://www.facebook.com/yasirshahzad918/" target="blank"><img align="center" src="path/to/facebook-icon.svg" alt="Facebook Profile" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/yasirshahzad18/" target="blank"><img align="center" src="path/to/linkedin-icon.svg" alt="LinkedIn Profile" height="30" width="40" /></a>
<a href="https://www.instagram.com/mastermind.pk/" target="blank"><img align="center" src="path/to/instagram-icon.svg" alt="Instagram Profile" height="30" width="40" /></a>
<a href="https://twitter.com/yourprofile" target="blank"><img align="center" src="path/to/twitter-icon.svg" alt="Twitter Profile" height="30" width="40" /></a>
<a href="https://www.fiverr.com/yourprofile" target="blank"><img align="center" src="path/to/fiverr-icon.svg" alt="Fiverr Profile" height="30" width="40" /></a>
<a href="https://www.upwork.com/yourprofile" target="blank"><img align="center" src="path/to/upwork-icon.svg" alt="Upwork Profile" height="30" width="40" /></a>

## Schematic Diagram
![Schematic Diagram](https://github.com/yasir-shahzad/Digispark-ATTINY85/blob/master/images/Schematic.png)

## PCB Files
![PCB Board](https://github.com/yasir-shahzad/Digispark-ATTINY85/blob/master/images/PCB.png)

## Features
- USB 5 V power supply
- Full-speed USB interface
- Bootloader for uploading sketches via USB
- Onboard 500 mA 5 V regulator
- 6 I/O pins (3 PWM pins, 4 ADC pins)
- SPI and I2C supported
- 8 KB of flash memory (6 KB usable after bootloader)
- 512 bytes of SRAM
- 512 bytes of EEPROM
- Compatible with the Arduino IDE using the Digispark board package
- Operating voltage: 5 V
- Small form factor with low power consumption
- Status LED onboard

## Requirements

- Altium Designer (or a compatible viewer)

## Screenshots :eyes:

<table>
  <tr>
    <th>
        <a href="images/Top3D.png" target="_blank">
        <img src='images/Top3D.png' width='200px' alt='Top 3D View' /> </a>
    </th>
    <th>
        <a href="images/Bottom3D.png" target="_blank">
        <img src='images/Bottom3D.png' width='200px' alt='Bottom 3D View' /> </a>
    </th>  
    <th>
        <a href="images/Top_Layout.png" target="_blank">
        <img src='images/Top_Layout.png' width='200px' alt='Top Layout' /> </a>
    </th>
    <th>
        <a href="images/Bottom_Layout.png" target="_blank">
        <img src='images/Bottom_Layout.png' width='200px' alt='Bottom Layout' /> </a>
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

- Firmware: This repository does not include the firmware. You can program the board using the Arduino IDE by installing the Digispark ATTINY85 board package from the boards manager.
- Assembly instructions (optional): Consider adding a separate document or webpage with detailed instructions on soldering and assembling the PCB (if applicable).
- License: Specify the open-source license used for the design files (e.g., MIT License).

## Contributing

We encourage contributions to this project! Feel free to submit pull requests with improvements, bug fixes, or additional features.
