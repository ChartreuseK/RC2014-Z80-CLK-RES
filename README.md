## A z80 + Clock + Reset Board for the RC2014 Bus
![Revision 1 board front](/images/z80-cpu.jpg)

A simple z80 board with integrated clock circuit (can oscillator) and divider. A 555 timer circuit provides power on and on demand reset with a clean pulse. 

The 74HCT393 is optional if you don't wish to divide the clock, just add a jumper or link on the FULL speed pad below it and it'll not be used. There is a shared footprint for either DIP-14 or DIP-8 can oscillators. For DIP-8 align it to the right edge of the socket. The reset pulse length can be shortened by lowering the values of R1 and R2, or adjusting the capacitor values. The 10k value of the pullup resistors is also nominal, and will likely work fine from 1k to 10k
