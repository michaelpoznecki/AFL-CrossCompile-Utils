# AFL-CrossCompile-Utils

Small collection of utilities used to compile and fuzz ARMv7 32bit binaries on an x86 host.

## afl-compiler-rt.o

This is an object file needed by AFL for compiling ARM binaries on x86.

Rename your version to a backup name and copy this new version in its place.

`cd AFLPlusPlus`

`mv afl-compiler-rt.o afl-compiler-rt-x86.o`

`mv ~/Downloads/afl-compiler-rt.o AFLPlusPlus/`
