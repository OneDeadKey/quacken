# Quacken

Libre, ergonomic, *polymorphic*: a single PCB for many possible layouts.

[3×6, 3×5, hummingbird, and everything in between](https://onedeadkey.github.io/quacken/).

![Quacken Flex, unibody Raven, 42 keys](quacken_raven.jpg)
![Quacken Flex, split Finch, 32 keys](quacken_finch.jpg)

## Project

This is just the public web page of the project, which is mostly
[Nuclear-Squid]’s work:

- [hardware] (KiCad and FreeCAD sources)
- [ZMK firmware] implementing the [Selenium] keymap

[Selenium]:      https://onedeadkey.github.io/selenium
[hardware]:      https://github.com/Nuclear-Squid/quacken
[ZMK firmware]:  https://github.com/Nuclear-Squid/zmk-keyboard-quacken
[Nuclear-Squid]: https://github.com/Nuclear-Squid

## Roadmap

- [x] onboard RP2040 (left) and I/O expander (right)
- [x] splittable in two (I²C communication over a TRRS cable)
- [x] splittable outer columns
- [ ] hotswap sockets
- [ ] optional Circle Trackpad
- [x] optional rotary encoders
