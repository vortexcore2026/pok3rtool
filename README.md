# vortexcore2026

Changes made to this fork:

- Defaults to older v1.x branch of the tool which uses C++. (Modern pok3rtool uses python, which seems to be running into issues)

- libchaos now points to github fork with a patch that fixes the build for newer C++ versions (> c++14).

## Building

```sh
git clone --recursive https://github.com/vortexcore2026/pok3rtool
mkdir pok3rtool-build
cd pok3rtool-build
cmake ../pok3rtool
make
```

# pok3rtool Vortex Keyboard Dev Tool/Library

*Disclaimer: This project comes with no warranty, and may be used for free at your own risk.*

The `pok3rtool` CLI application runs on Linux, Windows, and Mac OS X. Along with some development
tools, `pok3rtool` implements the firmware update protocol over USB for the POK3R, POK3R RGB,
Vortex Core, RACE3, ViBE, and some others.

The `pok3rtool` executable is built with CMake. You will need all submodules checked out to build it.

**WARNING: THIS TOOL CAN VERY EASILY BRICK YOUR KEYBOARD IF USED INCORRECTLY, MAKING IT
UNUSABLE WITHOUT EXPENSIVE DEVELOPMENT TOOLS. READ THE DOCUMENTATION, POSSIBLY READ THE
CODE, AND PROCEED AT YOUR OWN RISK.**

[See the wiki for pok3rtool usage, warnings, etc.](https://github.com/pok3r-custom/pok3rtool/wiki)
