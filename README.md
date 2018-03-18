# Customized Makeblock Library

This is a customized Arduino Library for Makeblock's modules. I only use it with the MeOrion so it's untested on others. 

# Changes

 - Move everything up one dir, so it can be zipped and installed normally
 - Eliminate the `utility` directory so we use Arduino's standard libraries for Servo, EEPROM, etc, rather than the outdated copies in the original lib