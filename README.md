# TRANSAIR
Command line script to send a DSK file directly (by WIFI) to a TOSHIBA FlashAIR inside a Floppy EMU, an UNISDISK Air or another device (to test)

© FRENCH TOUCH - 2019-2020
Code by Grouik/French Touch

DISCLAIMER: 
This Python script has been written to help Apple II cross-development on PC and is made to be executed from a command line. 
It is not optimized, probably buggy under certain circumstances and for someone who knows Python, the code is probably an abomination!
But it does the job. Use it at your own risk!



# Resquirements:
 - your FLASHAIR card must be correctly configured and recognized on your WIFI network!
 - if the "name of your card" is not 'flashair', you must modify APPNAME variable accordingly at the beginning of the script.
   => "name" of your card" refers to the APPNAME defined in your FlashAir CONFIG file if you use Station Mode or SSID if you use Access Point Mode.
 - if you get a bunch of errors at the launch of the script (and everything is correctly configured), it is probably because your FlashAir is not yet initialized and recognized on your wifi network. It takes a little while after the Apple II is turned on. So wait and try again!

# Notes:
 - 1: script unmounts old file and mounts the new file after sending it to the FlashAir. This was required with UNISDISK Air (from Nishida Radio).
          Not sure that this is necessary with a Floppy Emu (from BMOW) or another device...
 - 2: with a Floppy Emu, you must of course use a microSD to SD card adapter to use a FlashAir!
 - 3: script was not tested with another WIFI card, only TOSHIBA FlashAir.
 - 4: at the time (when I had one), script was written for UNISDISK Air. I think it still works with it. However tested recently with a Floppy Emu!
