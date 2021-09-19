# `nrf-hal`

Fork of the nrf-rs/nrf-hal with the nrf52840 memory.x memory layout modified for the nrf52840 dongle. The original memory.x starts the flash at address 0, however this needs to be 0x1000 to accomodate the dongle bootloader.
