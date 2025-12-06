Files here make use of ASM11, a freeware HC11 assembler for windows.  This assembler is an exe file,
but has been observed to run on WIN11 or earlier.  It can be obtained at: http://www.aspisys.com/asm11.htm.
The "make files" (.bat and .pl files) depend on the ASM11.exe program being in the next-highest directory.
If Placed elsewhere, the bat files or system path must be modified (the system path approach is dated, so
it may not work on higher WIN OS implementations).

The make system also depends on having a perl script interpreter in the system.  See https://www.perl.org/
to obtian the system software needed to run the perl scripts.  The perl scripts are not strictly required,
the file operations can be completed manually in a few minutes, but they greatly improve the accuracy and
reduce the manual intervention needed to produce an object image for the FF-800 software load.

Build instructions are generally found in an appropriately named text file within the source subdirectory.

Joe Haas 11/16/25


