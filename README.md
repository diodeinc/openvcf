# OpenVCF

Open source PCB printed business cards based on NFC, coded in atopile.

![card](./media/card.png)

Open-source, customizable PCB printed business cards with writable NFC tag.
The name is a reference to the [VCF](https://en.wikipedia.org/wiki/VCard)
format.

## Schematics

Schematics are really straighforward, with just 4 components

- Capacitor to smooth the NFC power generation.
- Resistor to current limit the LED.
- A Yellow LED
- [NFC NTAG: NT3H1101W0FHKH](card/elec/src/nfc/NT3H1101W0FHKH.ato)

The NT3H1101W0FHKH is really cool, a writable NFC tag that just needs an antenna.
It will generate enough power from the NFC field to light up a LED.


![video](./media/video.mov)


## Ordering 

DM on [twitter](https://x.com/davideasnaghi) if you want us to send you one of 
these. You can even customize it with your logo!