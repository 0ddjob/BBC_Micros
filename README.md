# BBC Micros
 Projects for the BBC Model A/B and Master.

## [Master Compact Floppy Interface](/Master_Compact_FDC_Interface)
Simple adaptor board to convert the DB25 floppy interface to a standard IDC 34-way header.
### Status: TESTED
- 17-Nov-2024: test PCBs ordered from PCBWAY
- 20-Nov-2024: PCBs shipped
- 27-Nov-2024: PCBs arrived
- 3-Dec-2024: tested successfully
<br>

```
DB25             34-IDC
                  2  1
        /INUSE    4--3 
                  6  5
    1---INDEX-----8  7
14  2---/DS0-----10  9
15  3---/DS1-----12 11
16  4---/DS2-----14 13
17  5---/MOTOR---16 15
18  6---/DIR-----18 17
19  7---/SEEK----20 19
20  8---/DATA----22 21
21  9---/ENABLE--24 23
22 10---/TRK0----26 25
23 11---/WRPROT--28 27
24 12---/READ----30 29
25 13---/SIDE----32 31
                 34 33

Pins 14-25 on DB25 connected to GND.
Odd pins on IDC connected to GND.
The Master Compact's original floppy cable has IDC pins 3 & 4 connected,
i.e. /INUSE grounded.  This doesn't seem to matter when using the Gotek.
```

![3D render of board](/Master_Compact_FDC_Interface/BBC_Master_Compact_Gotek_3D.png)

![Built board](/Master_Compact_FDC_Interface/BBC_Master_Compact_Gotek_Built1.jpg)
![Built board with Gotek](/Master_Compact_FDC_Interface/BBC_Master_Compact_Gotek_Built2.jpg)

