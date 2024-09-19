# The Eye of Seeron

A better illuminated loupe for inspecting circuit boards.

I bought [this loupe](https://s.click.aliexpress.com/e/_Dc7G7sf) for
inspecting circuit boards, because of its built in LEDs.   But there
is a risk of depleting the coin cell batteries if it is left on, so I 
wanted to fit a rechargeable power source.   I began by attempting to
modify the existing circuitry, but it is extremely difficult to solder
to the existing circuit board, due to it being surrounded by a welded
plastic shell.

So I removed the existing circuitry and LEDs entirely and created a
ring-light that fits underneath the existing lens retaining ring.

You will need some way of limiting the current draw to no more than
about 200mA.  Either fit a resistor in series with the battery, or
stay tuned for my auto-off control circuit.

You can upload the gerbers.zip file to JLCPCB to have this made, or
use the mill_gerbers.zip to cut your own on a CNC mill.  

The circuit needs up to twelve surface mount Light-Emitting Diodes
(LED) in size 0603.   I used six normal LEDs ([LCSC part C965808](https://www.lcsc.com/product-detail/LED-Indication-Discrete_XINGLIGHT-XL-1608UWC-04_C965808.html))
 and six side-emitting type ([LCSC part
 C273618](https://www.lcsc.com/product-detail/LED-Indication-Discrete_TOGIALED-TJ-S1706SW6TGLCCW-A5_C273618.html).
 
 
.
