# SimpleMenu
A simple terminal menu relying on unicode characters. 
On Windows, those aren't always supported (mostly older versions), 
so there I opted to use a different method, which is a bit slower, but still works.


This started as a copy from https://github.com/cornradio/dumb_menu, and evolved into its own thing.
Many of the ideas used in Cornradio's implementation stay the same, but I added extra functionality, 
mainly titles and a body, and made the code a bit clearer (for myself).
I also switched out the 3rd party `getch` library for standard-library functions, 
so this library has no dependencies outside the standard library.

# Why this and not another existing library?
This library is purely functional, no classes. It's also very light-weight, and strives to be fast.
However, it might not provide enough functionality for you, and maybe you're mainly targeting Windows. 
Then you might want to look for another option.
