# VLSI-Project series ADC 
layout and schematic

Implementation of an entire series ADC from the CMOS inverter.
The purpose of this design is to convert an analog signal to a bit-by-bit digital signal(in series) 
Every design was done by its layout & schematic implementation. 
every part of the design was simulated and tested by the DRC for proper behavior.
The project was done using the Electrical IDE and LTSpice.

Technology of:
MinW=0.6um MinL=0.3um

e.g. part of the design: the priority encoder.
I added up the schematic, layout, and simulation of this design.

exactly the same has been done to all of the parts in the design such as:
-latch(4 Nands)
-DFF(2 Latches)
-amplifier(comparator)
-Frequency Divider(10 DFF)
-ADC(7 comparators)
-Decoder(6 inverters and 4 Nands)
-TG
and etc.

There is also a Word file attached which is written in Hebrew and summarizes the whole project. There are also pictures and simulations of the complex parts in it.   
Finally, you can see the result Vout of an analog in a picture I added. 




