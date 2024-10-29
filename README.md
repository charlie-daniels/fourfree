# fourfree
designed because nobody sells 40 percent keyboards anymore.

## pcb

created using kicad with [marbastlib](https://github.com/ebastler/marbastlib) and a few handmade footprints.

![kle layout](/img/fourfree_kle.png)

![pcb top side](/img/fourfree_top.png)

![pcb bottom side](/img/fourfree_bottom.png)

created oct 2024.

## assembly

**promicro goes in upsidedown on the topside!!!**
this is why the pads are on the bottom and the pin labels seem flipped from the top.

### parts list 

**pcb** 

- 43x 1N4148W diodes
- 43x Kailh hotswap MX
- 1x Sparkfun Promicro
- 1x 2-pin reset switch
- 1x 128x32 OLED (optional)
- 1x 2.75u pcb mount stabiliser
- 1x 2.25u pcb mount stabiliser
- 1x 2u pcb mount stabiliser

**case**

- 14x M2 screws...?
case still being designed but should be screw in to the pcb mounting brackets, maybe 14 was overkill...

## firmware

this is just initial firmware made with [Keyboard Firmware Builder](https://kbfirmware.com/) by [Ruiqi Mao](https://ruiqimao.com/). The keymaps should work as expected as they are configured properly with the pinouts and key matrix.

![firmware key matrix](/img/fourfree_key_matrix.png)

## to be added

- plate
- case
- to see if the pcb actually works

## sources

[Ben Vallack](https://www.youtube.com/channel/UC4NNPgQ9sOkBjw6GlkgCylg)'s YouTube tutorials are great.

