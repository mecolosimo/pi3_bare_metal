# Raspberry Pi 3 Bare Metal

This is based on several other projects:

- [bare_metal](https://github.com/adamransom/bare_metal/tree/master)
  -  [adamransom.github.io](https://adamransom.github.io)

- [raspi3-tutorial](https://github.com/bztsrc/raspi3-tutorial)


## Setup

First in order to run these examples, you will most notably need a Raspberry Pi 3 Model B.

Secondly, you will need the a tool chain.

## Usage

If you have `make` installed, all you need to do is `cd` into an example directory and run:

```Bash
make
```

Then you will need to copy the generated `kernel.img` to your SD card, along with the [Raspberry Pi boot files](https://github.com/raspberrypi/firmware)
(`bootcode.bin` and `start.elf`, these are under *sd_card*), put the card carefully in your Pi and you are good to go!
