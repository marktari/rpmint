# Welcome to RPMint

RPMint intends to be a successor to Sparemint on Atari 16/32 computer systems.  Features over and above Sparemint include

- Properly specified build and installation dependencies
- Multiple architectures (68000, 68020-60, m5474 (coldfire))
- Auto rebuild of entire architecture
- Custom image generation

The RPM in the RPMint name is a bit of a misnomer that originated in the fact that Sparemint was RPM based.  RPMint intends to be as simple as possible, driven by makefiles and shell scripts and generates packages of 3 types - RPM, IPK, and .tar.gz.  The recommended package format is IPK and ipk packages are compatible with installation on top of a currently updated RPM sparemint system.

Contributions are welcome in the form of package build scripts and packages.  Ideas and suggestions are welcome.  Pull requests are welcome.
