# JoelOS

### A minimal Rust operating system kernel

Only builds on Mac but it's basically a one-liner to change to Linux or Windows

Mac:

`cargo rustc -- -Z pre-link-arg=-lSystem`

Next:

*Create kernel & configure for target system *Start using bootloader 
*Print to screen

[Reference](https://os.phil-opp.com/freestanding-rust-binary/)

