# Lab-1
# By: James Grassi and Fares Dayoub
# Last updated: 10/30/24

Our code is dependent on the 'msp430.h' library

This project uses two LEDs, in our case: BIT0 of P1 as the 'RED_LED and BIT6 of P6 as the 'GREEN_LED'. This project also uses two buttons: BIT1 of P4 as BUTTON1 and BIT3 of P2 as BUTTON2. These names and locations of physical LEDs and Buttons can be changed easily in the define section to fit seemlessly into other projects. Furthurmore, (after setup) the functions can be read as simple if and while statements. Currently, BUTTON1 turns on and off the RED_LED and BUTTON2 turns on and off the GREEN_LED. These statements can also be modified to fit other projects.


The code is clear and understanable becasue it uses a very simple system. As long as someone knows how to read C code, it should be clear what it does.

The code can ultimately be changed easily becase we defined the variables at the begining of the code and run through logic at the bottom. If needed for a different project or board, users can change these numbers and it would still accomplmish the same task. Tthe LED color change and the diffrent pins could also be changed to suit your prefrence if the board is slighly diffrent.
