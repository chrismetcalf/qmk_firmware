# The chrismetcalf keymap for plaid
Original copyright 2019 Takuya Urakawa (dm9records.com)
LED Support added  by Richard Sutherland (rich@brickbots.com)

This layout is based on the Planck layout, and includes an adjust layer (6)
accessible by holding the lower and raise modifiers (MO3 and MO4) together.
The adjustment layer is used to set the behavior of the two LEDs:

**Modifier Mode:**   
Activates when any modifier (shift, alt, os, MO) key is held
down.  LED turns off when key is release

**Blinkinlights Mode:**  
Random chance of state change on each keystroke.

**Keypress Mode:**  
On for any keypress as long as the key is pressed

**Carriage Mode:**  
Turns on when enter is pressed, turns off when any next key is pressed

To set the behavior of an LED, and save it to eeprom, hold the
raise/lower keys together to access the adjust layer, then use
the keys indicated below to set the behaviors

* z = Toggle Red LED state, deactivates any other modes
* x = Toggle Green LED state, deactivates any other modes
* c = Set RED LED to modifier mode
* v = Set GREEN LED to modifier mode
* b = Set RED LED to Blinkinlights mode
* n = set GREEN LED to Blinkinlights mode
* n = set RED LED to Keypress mode
* m = set GREEN LED to Keypress mode
* , = set RED LED to Carriage mode
* . = set GREEN LED to Carriage mode
