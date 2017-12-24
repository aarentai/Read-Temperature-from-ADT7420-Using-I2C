# Read-Temperature-from-ADT7420-Using-I2C
This code is designed specifically for ADT7420 temp sensor from ANALOG DEVICES with I2C protocol.The model of the FPGA i've used is Xilinx Artix-7(Xilinx part number XC7A100T-1CSG324C )

The main code file is the i2c_drive.v and scan_led.v under “ReadTemperaturefromADT7420UsingI2C\i2c_drive.srcs\sources_1\new”
The constrain file is the xdc.xdc under "ReadTemperaturefromADT7420UsingI2C\i2c_drive.srcs\constrs_1\new"

You can add the files mentioned above in Vivado, modify them according to your needs and then generate the bit file to see the result displayed on you FPGA.
