TinBoost
========

A simple holder for an OKR-T/6 bucking variable voltage converter, designed to fit in an Altoids-sized tin alongside two 18650 Lithium Ion batteries

Output adjustable from ~3.5V - 6V as shown.   You can go as low as 1V output if you change the values of the 220 resistors.

The barrel jack is connected directly to battery + and -.  It is intended to allow easy in-circuit charging using an external Lithium-Ion charger appropriate for the battery (7.2V in the case of dual Li-Ion).  It could also be used as an unregulated output direct from the battery.  

**DO NOT CONNECT A STANDARD DC POWER SUPPLY TO THE DC JACK, YOU WILL DAMAGE YOUR BATTERY AND PROBABLY START A FIRE**


## BOM:
* OKR-T/6 (mantually spread the pins to fit the board holes)
* C&K 1101 6A Switch (digikey # CKN5001)
* E-Switch illuminated right-angle tactile switch (digikey # EG4685-5)
* Bourns 3310Y 1k Pot (digikey # 3310Y-001-102L)
* 2x small through-hole tantalum 10uf caps
* 2x small 220ohm throughhole resistors ( for trim adjust )
* 1x small 6.8k throughhole resistor ( for EN pulldown )
* 1x small 1kohm throughhole resostor ( for tac switch LED )
* 1x standard through-hole DC barrel jack
