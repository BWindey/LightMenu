# Work In Progress
# LightMenu
A simple lightweight terminal menu.

This started as a copy from https://github.com/cornradio/dumb_menu, and evolved into its own thing.
Many of the ideas used in Cornradio's implementation stay the same, but I added extra functionality, 
mainly titles and a body, and made the code a bit clearer (for myself).
I also switched out the 3rd party `getch` library for standard-library functions, 
so this library has no dependencies outside the standard library.

## Why this and not another existing library?
This library is purely functional, no classes. It's also very light-weight, and strives to be fast.
However, it might not provide enough functionality for you. 
On Windows, this will still work, but it might be slower, as it doesn't use the unicode characters 
for clearing the terminal, but the `cls` command.
