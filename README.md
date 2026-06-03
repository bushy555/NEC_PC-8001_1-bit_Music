NEC PC-8001 - 1-bit music.

Listed here only for proof of concept. Works but is pretty ordinary.  "LETS GO" is perhaps the nicest tempo sounding tune here.  I gave it away because the 4Mhz CPU just couldnt handle any of the music players without massive changes to the engine/music data to play at an appropriate listenable tempo speed.  Most/all players will need a 1.35x factor speed up.  I kinda just gave up converting over the majority of the engines.


Uses port $40 for data to the speaker.

Assemble to a binary to $8100 , no header. 

Convert BIN to cassette tape .T88  file.

      Use :     
         z88dk-appmake.exe +pc88 -b file.bin -o file.t88 --org 33024

Use any of these emulators:

      J80 PC-8001      (Uses Java)
      pc8801MA
      quasi88-0.6.4-win32

   
            example, using J80:         .\8001\j80_r6b38\_J80.BAT
         [PC-8001] --> [Power on]
         MON
         L
         [TAPE] --> [PLAYER]
         <Select .T88 file>
         G8100




      
