# avsdpll_3v3 SoC Implementation

In this project, a PLL IP would be integrated into an SoC along with necessary I/O pads and control circuitry to implement and test functioning of PLL IP. The PLL IP in consideration is a 8x frequency multiplier. SoC flow will be implemented in OpenLANE. Inputs we have for RTL synthesis are four IPs PLL, Power On circuit, chip_io and vsdPLLSoC, in the SoC IP in which the rest three IPs are integrated. 

Firstly, we prepare design of chip_io in OpenLANE. Then run synthesis on chip_io design. The configuration tcl file of chip_io design looks like:-

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/chipioconfig.tcl%201.PNG)

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/chipioconfig.tcl%202.PNG)

After run synthesis is successful, chip_io.synthesis.v file gets generated as follows:-

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/chipio%20synthesis%20file.PNG)

Then we prepare design of vsdPLLSoC and run synthesis on that design. Configuration TCL file of vsdPLLSoC looks like:-

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/pllsocconfig.tcl%201.PNG)

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/pllsocconfig.tcl%202.PNG)

After run synthesis is successful, vsdPLLSoC.synthesis.v file gets generated as follows:-

![alt text](https://github.com/Dole97/PLL-SoC-Implementation/blob/main/PLL%20SoC%20synthesis%20file.PNG)



# ACKNOWLEDGEMENT

[Kunal Ghosh - Co-founder, VSD Corp. Pvt. Ltd](https://github.com/kunalg123)

[Lakshmi Sathi](https://github.com/lakshmi-sathi)

[Roshan Khatri](https://github.com/rsnkhatri3)
