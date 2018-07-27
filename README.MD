# JoelOS

### A minimal Rust operating system kernel

Only builds on Mac but it's basically a one-liner to change to Linux or Windows

Mac:

`cargo rustc -- -Z pre-link-arg=-lSystem`

Next:

1. Create kernel & 
2. configure for target system 
3. Start using bootloader 
4. Print to screen
5. ...More OS feature

[Reference](https://os.phil-opp.com/freestanding-rust-binary/)

