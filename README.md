
# **DEPRECATED**
This crate has been deprecated in favor of [mipidsi](https://github.com/almindor/mipidsi) a new generic driver that contains ST7789 support and should serve as a drop in replacement for this driver.

# st7789

This is a Rust driver library for ST7789 displays using embedded_graphics, embedded_hal, and no_std, no_alloc support. 
- [Driver documentation](https://docs.rs/st7789). 
- [Examples](https://github.com/almindor/st7789-examples)
- [Display datasheet](https://www.rhydolabz.com/documents/33/ST7789.pdf)

[![ferris-demo](http://objdump.katona.me/ferris_fast.png)](http://objdump.katona.me/ferris_fast.mp4)

## **Deprecation warning**

`v0.7` of this crate is the last release. [mipidsi](https://github.com/almindor/mipidsi) is a new generic driver that contains ST7789 support and should serve as a drop in replacement for this driver.

## Features

These features are enabled by default:

* `graphics` - embedded-graphics support: pulls in [embedded-graphics](https://crates.io/crates/embedded-graphics) dependency
* `batch` - batch-drawing optimization: pulls in [heapless](https://crates.io/crates/heapless) dependency and allocates 300 bytes for frame buffer in the driver

## Status

- [x] Communications via SPI
- [x] Tested with PineTime watch
- [x] Hardware scrolling support
- [ ] Offscreen Buffering

## [Changelog](CHANGELOG.md)

## Minimum supported Rust version

The minimum supported Rust version for the st7789 driver is 1.51.0 or greater.
Ensure you have the correct version of Rust installed, preferably through https://rustup.rs.
