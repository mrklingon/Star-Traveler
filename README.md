# Star-Traveler
Micro:bit game in Micropython to navigate a generated 20x20 universe.

* Tilting left/right/up/down guides the star flow.
* Pressing A+B (or "shake") stops star flow - then tilting left/right/up/down guides the "ship" on the 5x5 screen.
* Pressing A when stopped displays the star's name (if ship is "at" a star)
* Pressing B when stopped will pronounce the star's name (if ship is "at" a star)
* Pressing A+B (or "shake") again will start the stars flowing by again.

* StarTravel.py - main code
* universe.py - helper module 
* StarTravel.hex - micro:bit binary that can beloaded
