# DMRRec - DMR Recorder
This software connects to a DMR "master" (using MMDVM protocol) and records all received voice streams. Streams are decode using an AMBEServer and will be saved in .WAV files.

# Build
Main program is a single C file, no makefile is required. To build, simply run gcc:
```
gcc -o dmrrec dmrrec.c
```

# Usage
```
./dmrrec [CALLSIGN] [DMRID] [DMRHostIP:PORT:TG:PW] [AMBEServerIP:PORT] [SavePath]
```
