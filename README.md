# signfind-rs

Minecraft sign finder made in Rust.\
Reads all chunks in a world and returns all signs containing text.

## How to use

Put executable in the same directory as the world and rename the world to `world`.\
Then just run this command:
```
./signfind-rs
```

If you're using Windows, just append `.exe` and it should work

## Building

Get Rust and Cargo through [rustup](https://www.rust-lang.org/learn/get-started).\
Clone the repository, then run this command:
```
cargo build --release
```
