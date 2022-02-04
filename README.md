## Solar Power Load Sharing

### Simulations of load sharing circuits used in solar-powered LIPO charger
### and physical testing of a new opamp version.


### Update 3:

The opamp version has been revised to take into account the opamp's input offset
voltage.  See the folder "OpampVersion-Revisited", and the PDF included therein.


### Update 2:

Results of actual testing of the solar-powered opamp circuit have been included,
and the PDF has been updated accordingly. The issue of resistance to oscillation
in the opamp circuit is addressed, and there is discussion of the programming
resistor value on the TP4056 module - typically set at 1.2K for 1A charging current.


### Update:

The repo has been reorganized to divide its contents between the standard
load sharing circuit and a new version that uses an opamp to drive the mosfet gate.
The PDF explains both.


This repo examines the idea of using a standard load sharing (power path) circuit
in a LIPO charger powered by a solar panel instead of by a fixed 5V supply such as USB.
It presents the results of LTspice simulations of such a circuit, and proposes a new
circuit featuring a single opamp.  Everything is explained in the PDF.


