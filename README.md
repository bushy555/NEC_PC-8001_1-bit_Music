NEC PC-8001 - 1-bit music.

Uses port $40 for data to the speaker.

Assemble to a binary to $8100 , no header.  (TO DO: confirm on .N80 header file format)

Convert BIN to cassette tape .T88  file.

   Use :     z88dk-appmake.exe +pc88 -b file.bin -o file.t88 --org 33024

Use J80 PC-8001 emulator  (google search it; uses java)

      .\8001\j80_r6b38\_J80.BAT
      [PC-8001] --> [Power on]
      MON
      L
      [TAPE] --> [PLAYER]
      <Select .T88 file>
      G8100

Appears that the engine/data need to about a 1.35x factor in speed/tempo increase.



      
