This is an image of a bootable diskette for
the IBM (Japan) 5295-002 5250 Workstation Emulation System.
It is based on IBM Multistation hardware, and runs a Japanese
DOS and 5250 emulator program.

Ths physical format of this diskette is plain IBM 3.5" DSDD 720k
DOS format diskette...

HOWEVER!

The diskette is NOT a standard MS-DOS format diskette.

DO NOT BE FOOLED AS OTHERS HAVE BEEN!

The boot sector on this diskette is NOT a standard DOS diskette
boot sector. It is, in fact, an IBM VTOC (in EBCDIC even!) which
is the standard format for IBM 8" diskettes (and some midrange
5.25" diskettes). 

With the exception of the boot sector, the rest of the diskette is
plain ol' MSDOS format.

You should be able to write this image with your favorite imaging
software (including just plain "dd" for Linux/macOS. 

Included in this dir is an .img (raw sector image) and an .imd
(ImageDisk). Finding some tool to write either one of those formats
shouldn't be too difficult.

The included ZIP file is just the DOS contents of the diskette
for informational purposes. You'll need the diskette image to boot
a 5295.


Diskette rescued and imaged by The Crusty Computer Club
info@crusty.computer
