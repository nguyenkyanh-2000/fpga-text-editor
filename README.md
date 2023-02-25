# fpga-text-editor
Program a FPGA (PYNQ-Z2 board) into a simple text editor (08/12/2021)

# Functionalities
0. RST (BTN0) to clear the whole screen.
1. PUSH (BTN1) to increase internal counter (0 - 15). Return to 0 when > 15. 
2. STOP (BTN2) to print the current value (0 - f) onto the screen.
3. BTN3 + SW0 OFF + SW1 OFF (DELETE MODE, RED TEXT):  Push to start to delete last character.  
4. SW0 OFF + SW1 ON (CAPSLOCK MODE, GREEN TEXT): Turn a - f into A - F when counter's value > 9. 
5. BTN3 + SW0 ON  + SW1 OFF (LINE BREAK MODE, BLUE TEXT): Press BTN3 to move down a line. Automatically reset when reaching end-of-screen.	
6. BTN3 + SW0 ON + SW1 ON (SPACING MODE, RED TEXT): Press BTN3 to add a space between characters. Automatically reset when reaching end-of-screen.
7. LEDs to indicate value o internal counter and current SW inputs (GREEN = ON, RED = OFF, 4 smaller LEDs)	
