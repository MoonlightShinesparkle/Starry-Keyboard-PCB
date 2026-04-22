# Starry keyboard PCB files
A KiCad board which allows for the direct insertion or soldering of an appropriate Raspberry Pico model (the project was based in the 2W model, however a W might work) to allow the direct use of the Starry Keyboard code project. The board is based in the concept of a button matrix, allowing for the usage of 25 buttons with only 10 GPIOs from the pico, the rest being used to communicate with an EEPROM and LEDs, the project is directly based in the Moonlit Keyboard project.

# Components
The board is based in the mix of SMD and THT components, most notable SMD components being a capacitor, pull up resistors, power resistors and LEDs, meanwhile the rest of the components are THT and some were meant to be soldered with a base or with pin header sockets to allow for the easy insertion of the components and simple removal process from the board, allowing the use of the microcontroller board for other uses.
