# SPI_Master_With_Single_Chip_Select_and_Test_Bech
# this is a tested and standard VHDL code + test bench for SPI (Serial Peripheral Interface) Master With Single Chip Select
# the VHDL SPI Master project added to this project as module
#  VHDL code will..
Creates master based on input configuration.
Sends a byte one bit at a time on MOSI
Will also receive byte data one bit at a time on MISO.
Any data on input byte will be shipped out on MOSI.
also has a Chip Select (AKA Slave Select) to define the chip(slave) by master for communication
# Test bench code will..
teste the protocol with a few senario

