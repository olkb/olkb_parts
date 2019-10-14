Mechanical keyboards can be a little overwhelming when seeing all of the different options! This page will serve as a brief guide on what you might be buying from OLKB or other stores. Feel free to suggest additional links/info!

## Guides to check out

* [OLKB PCB assembly guide](http://olkb.com/help/guide)
* [Quantum firmware documentation (up-to-date)](https://docs.qmk.fm)
* [How to hand-wire a keyboard](http://deskthority.net/workshop-f7/brownfox-step-by-step-t6050.html)

## The term "ortholinear"

Ortholinear is a semi-made-up word that was originally coined (to my knowledge) by [TypeMatrix](http://www.typematrix.com/study/) as "ortho-linear" - this term got concatenated, became popular among the keyboard community, and eventually became the banner for a keyboard company!

It refers to keyboard layouts where the keys are aligned vertically and horizontally, compared to standard staggered keyboards. No studies have been done to test the ergonomics of ortholinear keyboards (versus a comparable staggered one), but the change can make it easier to design and visual custom keymaps, and may help relieve RSI symptoms.

## Construction

The keyboards sold on OLKB generally have a top and a bottom (and sometimes a middle) - the switches fit into holes in the top plate, and then are either hand-wired to a Teensy 2.0 (or other microcontroller) or a PCB. In practice, it's much easier to place the switches one-by-one into the plate *and* PCB than it is to place all switches into the plate, *then* the PCB.

10mm between the top and bottom plates is usually enough room to fit all of the necessary components for a PCB or hand-wired build. Additional M2 brass spacer sizes [can be found on Amazon](http://www.amazon.com/s/ref=nb_sb_noss?url=search-alias%3Daps&field-keywords=m2+brass+spacers&rh=i%3Aaps%2Ck%3Am2+brass+spacers).

## Switch Types

There are a lot of different types of modern switches, but they can be separately into two categories that are available for these/custom keyboards:

* MX-compatible switches
  * Cherry MX
  * Gateron
  * Kailh
  * Greetech
* Matias-compatible switches
  * Matias
  * ALPS XM

Each has variations that will affect the feeling/sound of the switch, and are usually denoted by colors. [More information on the various types can be found here](https://www.reddit.com/r/MechanicalKeyboards/wiki/switch_guides).

## OLKB Keyboards

I'm always thinking about new keyboards to make, but these are the OLKB keyboards that have been announced/are for sale currently:

* [Planck](/planck) - a 40% (4u x 12u) keyboard
* [Preonic](/preonic) - a 50% (5u x 12u) keyboard

## Firmware

The PCBs and the Teensy 2.0 use Atmel's Atmega32u4 AVR controller, so all firmware is compatible with both. [The official firmware](https://github.com/qmk/qmk_firmware/) for OLKB boards is called Quantum, and is based on the [TMK Keyboard firmware](https://github.com/tmk/tmk_keyboard/). Quantum contains a lot of helpful shortcuts to make building your custom keyboard/layout easier. 
