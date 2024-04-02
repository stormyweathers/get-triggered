# Get Triggered

This is a eurorack module which takes an input signal (CV, audio, etc..) and generates pulses of fixed width when the signal crosses zero.
The output pulses are positive polarity for both rising and falling edges.
These pulses can be used as trigger input for a variety of other modules, but I am designing this with my strobe control system in mind.

Features:
    * Buffered inputs, outputs
    * Adjustable pulse width (100us -> 100ms target)
    * Adjustable by CV/manual POT
    * Attenuator on CV input
    * LED indicators for positive/negative edge pulses
    * 3 Outputs: rising edge, falling edge, and both edges
    * Output pulse amplitude: Something like 12V-V_LED
    * Low component count: R,C, TL074, mono jacks, IDC power, pots, JEFT, and LEDs only
    * SMD footprints: 0603 for all passives

Rack info:
    * +12V: 
    * -12V:
    *  +5V: Not used
    * Width: <6HP (target)



TODO:
    * Breadboard test
        * The JFET VCF is new to me, might take a little tuning to get it right
        * The LED rectifiers are also a new idea
    * PCB layout
    * Front panel design
    * Fabrication
