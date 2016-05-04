Introduction
------------

This adapter board is designed to interface a Blackrock CerePlex M9 headstage
(containing 3 Omnetics connectors with 32 channels each) with a 64-pin Molex
connector. The Molex connector is compatible with the 64 channel probes
produced by Sotiris Masmanidis at UCLA. 

Note that the Omnetics connectors are actually 36 pin connectors (two pins are
used for reference and two for ground). The reference and ground pins are tied
to reference and ground planes on the PCB. All pins on the third Omnetics
connector of the Blackrock headstage are tied to ground.

There's a screw terminal block that accepts two wires (one for reference and
one for ground). The wire must be between 230 and 26 AWG. The two-pin vertical
header is designed for use to connect reference to ground using a jumper (e.g.,
Sullins SPC02SYAN).

Ordering
--------

I have ordered this through Macrofab (macrofab.net). Be sure to select the
*extended manufacturing* option. You will need to have three Omnetics
connectors (part number A79026-001) shipped to them as consignment parts (if
you're not sure how this works, talk to their customer service first). The
parts can be ordered directly from Omnetics ($68 per connector), however there
is generally a very long lead time of at least two months. You can also order
from Neuralynx ($95 per connector) if you need them faster. Macrofab will take
care of ordering the Molex connector and two-pin header. If you want the
jumper, you'll need to order that yourself (DigiKey is a good source). Total
cost for ordering from Macrofab will be about $150 for a single, fully
assembled board. This does not include the cost of the Omnetics connectors
which are extra. So the final cost will be approximately $350 to $500 depending
on where you purchase the Omnetics connectors from and how much shipping is.

CircuitHub is another vendor that can handle prototype boards. They may be able
to source the Omnetics connectors directly for you as well (I know they do this
for the acquisition bboards designed by the Open Ephys group). If you decide to go with CircuitHub or another vendor, you need to ensure that the following tolerances are met:

* 3 mil minimum trace width
* 3 mil minimum trace spacing
* 3 mil minimum annular ring
* 3 mil edge clearance
* 12 mil minimum drill size
