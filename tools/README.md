# PIN2DMD.exe

Tool to configure PIN2DMD interface through USB interface.
You can either upload palette(s) generated by pin2dmd editor in 
binary dat format or defined in a textfile.
For binary upload start pin2dmd.exe with option /b and the filename 
as parameter e.g. "pin2dmd.exe /b c:\palettes_option_b.dat".
For textfile upload start pin2dmd.exe with option /t and the filename 
as parameter e.g. "pin2dmd.exe /t c:\palettes_option_t.txt".
For alternative textfile upload start pin2dmd.exe with option /t and the filename 
as parameter e.g. "pin2dmd.exe /t c:\palettes_option_a.txt".
Additional commands are:

/p followed by the palettenumber you wish to activate
/r to reset device
/c to clear all settings
/i image upload (binary ppm (P6) format with 128x32 pixel resolution)
/s smartdmd paletteID upload
/l set brightness (10-255)
/u - <src> (<dest>) - upload file optional with <dest> as filename
/d <file.dmc> - convert palette from .dmc to .pal file (4 colors)
/k - delete activation key

Without parameter program starts in GUI mode to adjust config.

