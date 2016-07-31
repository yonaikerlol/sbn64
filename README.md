# sbn64
Simple Byteswapper for N64 Saves

This program is designed to convert N64 saves generated by PC emulators, like Project64, from Little Endian to Big Endian, by performing a 32-bit byteswapping operation on the whole file (and adding padding if required). The output file should be compatible with Wii64/Not64 and Mupen64Plus emulators. Usage is pretty much straightforward and it's also explained in the program itself.

Furthermore, sbn64 lets you convert an input file to the Virtual Console format, by using the "/vc_save" modifier. Also, it's compatible with Sixtyforce saves and it's able to extract Controller Pak saves from them.

This code is public domain, so just have at it.
