# Electrolyte-Solution-Builder
This program is being designed for the building of custom electrolyte solutions (think Pedialyte or for sports medicine usage).

Since electrolye solutions for human consumption are required to be of a certain osmotic concentration (osmolarity) to prevent negative digestive effects or more severely, under/overdosing of certain components, it can be difficult to balance all requirements without fine tuning. 


This program will function under several modes:

Mode 1/Building Mode: Enter the required the maximum osmolarity and the required ions or additives (glucose, etc) and the program will calculate the masses needed for a desired volume. This mode will use a stored list of known precursor compounds commonly used to mix electrolyte solutions.

Mode 2/Reverse Engineering Mode: Enter masses and identity of component ions and additives and the program will calculate the osmolarity and masses of potential parent compounds for reproduction of the parent solution.

Mode 3/Custom Mode: The program will allow entry of custom chemical compounds which will be stored and available for use in other modes.



*Current Build*

1.0-1.3 : Building basic functionality so that the program will recognize chemical components and return their molar mass, as well as store them for later use ('Custom' Mode). For example the program will recognize entering "Na3Citrate" or "Na3C6H5O7" and should return a molar mass value for "Trisodium citrate" and should also query the host if the meant to enter the much more commonly utilized "Trisodium Citrate Dihydrate".
