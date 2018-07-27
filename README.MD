# JoelOS

### A minimal Rust operating system kernel

~Only builds on Mac but it's basically a one-liner to change to Linux or Windows~

Build anywhere:

`cargo install cargo-xbuild`

`cargo install bootimage --version "^0.5.0"`

`bootimage build`

Disk image: _target/x86_64-joel_os/debug/bootimage-joel_os.bin_

You can boot on a VM or copy to USB drive (bare metal!) but a CD (different format) won't work. I am using [QEMU on Mac](https://www.qemu.org/download/#macos) & it works like a charm. 

## Next:

1. ~Create kernel~  
2. ~configure for target system~ 
3. ~Start using bootloader~ 
4. ~Print to screen~
5. More OS features...

[Reference](https://os.phil-opp.com/freestanding-rust-binary/)

