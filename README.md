# PZEM004Tv30MULTI
An Arduino library to connect multiple PZEM004T version 3 sensors to one serial port.
See https://www.innovatorsguru.com/pzem-004t-v3/

I've created this library to allow easy intergration in Espruna https://github.com/xoseperez/espurna and/or ESPeasy https://github.com/letscontrolit/ESPEasy

It's based on the code from https://github.com/mandulaj/PZEM-004T-v30 but modified to be able to use multiple devices on one serial port and to be fully compatible with the orginal version from https://github.com/olehs/PZEM004T so it's easier to use this sensor in existing
projects. Just keep in mind that the V3 uses addresses in the range 0x01~0xF7 instead of the IP like addresses of the first version.

Example code will follow soon...


