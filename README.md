# Terminatel257-archive
Information on the Terminatel 257 Prestel terminal

## User manual

[manual](./documents/Terminatel257MinitelImages.pdf)


## Photo gallery

[more photos](https://photos.app.goo.gl/XQcuR6rgJqsdsudp8)

## Prestel

Showing the Terminatel connected to Telstar using ESP32 wifi modem - note external 75 to 1200 baud rate converser in trasmit line.

See links for details:

[SimpleSoftwareSerial](https://github.com/DavidJRichards/SimpleSoftwareSerial)

[Zimodem](https://github.com/DavidJRichards/)

![telstar](./images/telstar.jpg)

## mode change

To swap to ansi terminal at 4800 bps issue these commands at the keyboard:

There is no way to store settings, the changes do not survive a power cycle.

I have the neccessary key strokes printed on a label as a reminder.

![mode change](./images/mode-change.jpg)

![terminal](./images/terminal.jpg)



## Internal view

![cpu-board](./images/cpu-board.jpg)

## Firmware

The eprom is type M27256 32KB printed label identifier '4853'

[firmware](./firmware/M27256@DIP28-4853.bin)

Processor type: 8032 - 8032 80 Series Microprocessor with 256x8 RAM and I/O
```
Features
40-pin MCS51 Series Microcontroller
Power Control Modes
256 x 8-bit RAM
32 programmable I/O Lines
Three 16-bit Timers
Six Interrupt Sources
2-Level Program Memory Lock EPROM
Programmable Serial Port
64k External Program Memory Space
64k External Data Memory Spac
```

## code disassembly

the d52 disassembler created these control and source listing files, more work is needed to make the control file properly represent the software structure.

[D52 8051/8052 Disassembler](https://www.bipom.com/dis51.php)

[control](./firmware/4853.ctl)

Best viewed with tab setting of >= 8 spaces.
[dissasembly](./firmware/4853.d52)

## other information

This thread has descriptions of some of the chips: [twitter](https://twitter.com/Foone/status/1226394705040007169)

https://heyrick.eu/blog/index.php?diary=20180815&keitai=0

https://www.jelora.fr/post/2017/08/07/Teardown-Demontage-Minitel-1-Telic-Alcatel.html

https://www.jelora.fr/post/2017/08/01/Teardown-Demontage-d-un-Minitel-2.html


