# Arty A7 Hardware Repository

This repository contains Vivado projects for all demos for the Arty A7.

For more information about the Arty A7, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [Arty A7 GPIO Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/demos/gpio) | This project demonstrates the basic use of Arty A7's Switches, LEDs, RGB LED's, Pushbuttons, and USB UART bridge |
| [Arty A7 XADC Analog to Digital Converter Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/demos/xadc) | Simple hardware-only project that uses the XADC analog-to-digital functionality of the board |
| [Arty A7 Pmod VGA Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/demos/pmod-vga) | Play video through a simple VGA interface|

## Repository Description

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Arty A7. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Arty A7](https://github.com/Digilent/Arty-A7) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* https://github.com/Digilent/Arty-A7-35-GPIO/
* https://github.com/Digilent/Arty-A7-100-GPIO/
* https://github.com/Digilent/Arty-A7-35-XADC/
* https://github.com/Digilent/Arty-A7-100-XADC/
* https://github.com/Digilent/Arty-A7-35-Pmod-VGA/
* https://github.com/Digilent/Arty-A7-100-Pmod-VGA/