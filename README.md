# kuronbka (currently very early WIP)

kuronbka (куронька) is an NES game made entirely in 6502 Assembly

The .ASM and .CHR files are provided and it can be assembled on Windows and Linux

## Assembly

### Linux

```bash
sudo apt-get install nesasm

make all # to build files

make clean # to clean files
```

The program outuputs a game.nes ROM file which should be able to run in any NES emulator

### Windows

Run the build.bat and keep the assembler.exe, game.asm and game.chr in the same folder

The build.bat contains

```bash
assembler.exe game.asm
pause
```

This also produces a game.nes ROM file and could be run in an emulator
## Contribution

This is a personal project, and no contribution is needed
