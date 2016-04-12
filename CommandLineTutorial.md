# Introduction #
There are several steps to create digital cinema package:
  1. Color transform the picture if needed
  1. JPEK 2000 encodin
  1. Create the MXF files
  1. Create one or more composition playlist
  1. Create one or more packing list
  1. Create an asset map
  1. Copy the files on a compliant media

# 1. Color Transform #
Color transform is not yet supported at this state of the project.
The [Color Transform Language (CTL)](http://www.oscars.org/council/ctl.html) API can help you to support color tranform if you project needs it.

# 2.JPEG 2000 Encoding #
Encoding could be donne with [OpenJPEG](http://www.openjpeg.org/) or any JP2K compliant software/hardware.

# 3. MXF Files Creation #
The current version of OpenCinemaTools doesn't currently support MXF file creation.
[asdcplib](http://www.cinecert.com/asdcplib) can help you to create MXF files.

# 4. Composition Playlist Creation #
A composition playlist can be created with [mkcpl](MkCplMan.md).

# 5. Packing List Creation #
A packing list can be created with [mkpkl](MkPklMan.md).

# 5. Asset Map Creation #
An asset map can be created with [mkmap](MkMapMan.md).

# 7. Copy To Media #
A simple file copy on an ext2 media would be fine.
**This information may vary from a manufacturer to another, so please check with them.**
