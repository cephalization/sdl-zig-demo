# SDL2 Zig Demo

Here's a (working) basic window with SDL2 in Zig.

Forked from [andrewrk/sdl-zig-demo](https://github.com/andrewrk/sdl-zig-demo)

![screenshot](screenshot1.png)

## How to build and run it

Install `zig 0.13.0` exactly.

```sh
# On macOS
brew install sdl2

zig build run
```

## Cross-Compiling

Pass a `-Dtarget` option. For example:

```sh
zig build -Dtarget=x86_64-windows
```
