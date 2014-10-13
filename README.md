Coincidence-Counter
===================

Coincidence Counter for 8 inputs. 
Designed for Spartan 3E Starter Kit. 
The code is written in VHDL and compiled in ISE Design Suite 14.6.
Single and Coincidences are defined as: A, B, C, D, H and AH, BH, CH, DH.
The output is given in serial communication. 5 bytes per signal.
String: 1 start bit + 8 data bits + no parity + 1 stop bit.
Baud rate: 19200 and data output every 100ms.

