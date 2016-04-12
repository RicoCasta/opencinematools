# General #

This is the second release. This version includes 3 command line tools:
  * mkcpl
  * mkpkl
  * mkmap

And a GUI for Windows.
  * DcpMaker

Subtitles are not supported.
Only JP2K and PCM 48k are supported.
3D is supported.
The generated DCP are 100% SMPTE compliant.


# Download #
There are currently 2 different downloads.

To use directly on Windows, download opencinematools-1.1.2-bin-win32.zip

To compile on Windows, Unix and Mac OS X, download opencinematools-1.1.2-src.zip

Read the [FAQs](ReleaseFaq.md) for more details.

# Known Issues #
  * different errors can return the same return code for the command line tools

# Changes From Release 1.0.1 #
  * Fixed memory alloc bug
  * Added 3D support
  * Replace some Interop tag by their SMPTE equivalents.
  * Added GUI
  * Added libexpat.dd in opencinematools-1.0.1-bin-win32.zip

# Changes From Release 1.0.0 #
  * Fixed bug when using mkcpl -h
  * Added libexpat.dd in opencinematools-1.0.1-bin-win32.zip