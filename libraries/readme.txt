For information on installing libraries, see: http://www.energia.nu/reference/libraries

Note from repository owner: Vksalian

The libraries included in the repository are the ones which have been ported from arduino to energia to 
support EK-TM4C123GXL TIVA C TM4C123G Launchpad kit. The porting was done by vksalian for some of the 
libraries and some libraries are in their original form. Please note that all the credit goes to authors
of the oroginal libraries. I just made the libraries work for the TM4C123G launchpad

The repository is still in development stage and hence there might be bugs in it. So, be aware of such
bugs before use. I am not responsible for any issues that may arise with use of these libraries. Its upto
the user to decide whether to use these libraries or not.

The intension of this project is to help the TM4C123G users to develop applications using energia.

Initial Commit: The initial commit has below libraries added,
                Adafruit_GFX-master  - Adafruit GFX for use with 1.8 TFT LCD 128x160
                SD_TM4C-master       - Sdfat library (But it seems there are unimplemented features. So not working when used with LCD)
                TFT_ILI9163C-master  - LCD library (1.8 TFT LCD 128x160) (works)
  
                TODO -  All the libraries are ported alongwith the examples corresponding to pins of TM4C123G
  
  
