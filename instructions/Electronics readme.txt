Send the gerber zip-file to a PCB manufacturer, like JLCPCB.
Solder the components to the PCB. It should be kind of self explanatory which component goes where.
Pay attention to polarity on the Capacitors and Power Jack.
I recommend using female + male header pins for the Arduino so you can replace it easily if necessary.

Before connecting anything to the PCB you must adjust the DC-DC converter to output 5.0 V.

Solder the two photo transistors in parallel. Use shrinking tube to avoid short circuits.
The shorter leg on the PT333-3C is the Collector and must connect to the PIN marked "C" on the PCB.
(The longer one is of course emitter wich connects to "E")
Total length of the cables should be around 20 cm. Make sure the two photo transistors can be inserted into opposite holes in the scanner.

RGB LED: the longer leg is the Anode and connects to the "A" pin on the PCB. The "R", "G", and "B" pins connects to corresponding legs.
Make this cable also around 20 cm and mount the LED in the middle hole in the scanner.

Twisting the PT333-cables might be good to supress noise.

