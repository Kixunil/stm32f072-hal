stm32f072-hal
=============

_stm32f072rb-hal_ contains a hardware abstraction on top of the peripheral access
API for the STMicro stm32f072 series microcontroller.

This crate is mostly a shameless copy of [stm32f042-hal][] crate with appropriate
changes. **Warning: added serial and spi ports weren't tested yet! Only mechanical
changes in code were made**

If you want a board to try this there is a [nucleo-f072rb][] board on the market.

[stm32f042]: https://github.com/therealprof/stm32f042.git
[nucleo-f072rb]: https://os.mbed.com/platforms/ST-Nucleo-F072RB/

License
-------

[0-clause BSD license](LICENSE-0BSD.txt).
