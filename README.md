MultiWii_2.3_HK_23U4
====================

Code from https://code.google.com/p/multiwii/ https://multiwii.googlecode.com/files/MultiWii_2_3.zip
All code is under some form of GPL licence. Which one I am not sure.


MultiWii code changed for Hobby King MultiWii MicroWii ATmega32U4 Flight Controller


Please note this code contains Input scaling for RC controllers. This was developed cause I was impaciant for the my Hobby King configuring device to come. This code can be adapted for other controlors. You need to make sure the start point is scaled to 1000 and the middle is 1500 and the end point is 2000.

So MULTI is the multiplier for the channel scaling and the cont is the hard value.

 data = (rcValue[rcChannel[chan]] * MULTI) - CONST ; // 

This should be converted to pre-processor vaules but that is for a later date.

Adric
