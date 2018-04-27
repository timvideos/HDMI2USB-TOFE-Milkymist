## Milkymist Compatibility - TOFE Expansion board

The [Numato Opsis board](https://numato.com/product/numato-opsis-fpga-based-open-video-platform) is
already very similar to the [Milkymist M1](http://m-labs.hk/m1.html) and
[Mixxeo](http://m-labs.hk/mixxeo.html) devices created by
[M-Labs](http://m-labs.hk/), but lacks the DJ hardware interfaces. This
expansion board adds these missing components.

This board can be ordered from the
[Numato Opsis page on CrowdSupply.com](https://www.crowdsupply.com/numato-lab/opsis).

![Board Image](img/above.jpg)

## Features

This extension board has the following features;

 * [AC‘97 compatible](https://en.wikipedia.org/wiki/AC%2797)
   audio interface with Microphone, Headphones, Line In + Out (on standard
   3.5mm connectors).

 * [RS-422](https://en.wikipedia.org/wiki/RS-422) / [RS-485](https://en.wikipedia.org/wiki/RS-485)
   compatible high speed (10Mbps), full duplex serial port;

    * Compatible with wide range of interfaces including the industry standard
      [DMX512 control protocol](https://en.wikipedia.org/wiki/DMX512).

    * Connected to screw terminal headers, allowing wiring to DB-9, RJ-12,
      XLR-5, XLR-3 or RJ-45 connectors (wiring diagrams provided).

 * [RS-232](https://en.wikipedia.org/wiki/RS-232) full duplex serial port on a
   standard DB-9 connector. Supporting connection to wide range of devices with
   serial ports. (A secondary RS-232 full duplex serial port on a standard
   screw terminal.)

 * [MIDI](https://en.wikipedia.org/wiki/MIDI) In and Out interfaces on screw
   terminals, supporting connection to wide range of musical instruments and
   control devices.

 * [Infrared](https://learn.adafruit.com/ir-sensor/ir-remote-signals)
   transmitter and receiver compatible with manys
   [consumer remote protocols](https://en.wikipedia.org/wiki/Consumer_IR).

 * 4 x Push button Switches,
 * 4 x Indicator LEDs,

 * 2 x [Digilent Pmod™ Compatible](http://www.digilentinc.com/Pmods/licensing.cfm)
   headers to allow usage of existing expansion boards, including boards froms
   [Numato Lab](http://numato.com/fpga-boards/filter/cat/expansion-modules.html?limit=30),
   [Digilent](http://digilentinc.com/pmods),
   [Maxim](https://www.maximintegrated.com/en/design/design-technology/fpga-design-resources/pmod-compatible-plug-in-peripheral-modules.html) ands
   [Analog](https://wiki.analog.com/resources/alliances/xilinx#pmods).

A PDF version of the schematic can be found in the [docs](docs) directory.

## Editing

The design in this repository was made using [KiCad](http://www.kicad-pcb.org/)
version **2013-07-07 BZR 4022**
([the version is Ubuntu Trusty](http://packages.ubuntu.com/trusty/kicad)).

## License

TOFE MilkyMist Compatibility Expansion board by Numato Systems Pvt. Ltd

TOFE MilkyMist Compatibility Expansion board is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

![Creative Commons License Logo](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
