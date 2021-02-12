# avsdpll_3v3 SoC Implementation

In this project, a PLL IP would be integrated into an SoC along with necessary I/O pads and control circuitry to implement and test functioning of PLL IP. The PLL IP in consideration is a 8x frequency multiplier. SoC flow will be implemented in OpenLANE. Inputs we have for RTL synthesis are four IPs PLL, Power On circuit, chip_io and vsdPLLSoC, in the SoC IP in which the rest three IPs are integrated. 

Firstly, we prepare design of chip_io in OpenLANE. Then run synthesis on chip_io design. The configuration tcl file of chip_io design looks like:-


Then we prepare design of vsdPLLSoC and run synthesis on that design. Configuration TCL file of vsdPLLSoC looks like:-

