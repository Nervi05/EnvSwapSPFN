![EnvSwap - Github Banner](https://github.com/bigmaxine/EnvSwap/assets/73800394/b63358b4-6e4d-4f35-a170-60b95dd52f21)
# This is <ins>NOT</ins> a port of HBL to Aroma and <ins>NOT</ins> an application to use .ELF homebrew on Aroma.

## Wii U Environment Swapper

This is just a test, to see if its Possible to switch between 2 Aroma Enviroments (Base Aroma and SPFN).<br>

Opening this app in the normal Version of Aroma reboots the WiiU and (hopefully) switches to SPFN<br>
Opening this when using SPFN reboots the WiiU and it should switch back to the Base Aroma version<br>

## Building

To build this, ensure you have `devkitPro`, `devkitPPC`, `libmocha` and `wut` installed via the (dkp-)pacman package manager. Run `make` in the same directory as the Makefile, and use the resulting files located in the `dist` directory.

Alternatively, you can use the included dockerfile, here are some command that should work as long as you have Docker installed.
### Docker for Linux
`docker run --rm -v ${PWD}:/project builder make`

### Docker for Windows
`docker run --rm -v %cd%:/project builder make`.

## Credits
Huge thanks to:

[TraceEntertains](https://github.com/TraceEntertains) - Lead developer<br>
[Maxine](https://github.com/bigmaxine) - Original project<br>
[Ingunar](https://github.com/Ingunar) - All of the awesome icons & graphics (and the idea for this too)<br>
[Moonlumen](https://github.com/Moonlumen) - Moral support and *insane* amounts of alpha testing<br>
[WiiUReboot](https://github.com/Fangal-Airbag/) - Originally used as a foundation for this project<br>

<sup><sub>The Wii U is a registered trademark of Nintendo, who we are not affilated with.</sub></sup>
