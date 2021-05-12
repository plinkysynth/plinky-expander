# plinky-expander
hardware design of a small expander for the plinky synth

if you want to get some of these made, I recommend the gerbers in the folders gerbers_just_front (the front panels, no SMT assembly required) and gerbers_just_back (one sided SMT assembly required, JLCPCB compatible subject to stock)
the BOM files for the SMT assembly are in the main folder, and then the hardware BOM file is the set of thruhole parts you will need to order to assemble.
in summary:
- get black PCB only boards using the gerber zip file in gerbers_just_front
- get any-color PCB boards with SMT assembly using gerber zip and placement file in gerbers_just_back, and using the BOM in jlcbom.csv
- order thruhole components as listed in hardware-bom.csv

once all the parts arrive, you can put it all together. build guide is on plinkysynth.com
