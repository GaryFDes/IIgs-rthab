# IIgs RGBToHDMI Adaptor Board
ROM 01 Apple IIgs RGBToHDMI Adapter board [Top](pictures/Top%20of%20Board.jpeg)/[Bottom](pictures/Bottom%20of%20Board.jpeg)

[Plug](https://warwickts.com/4405/W9327-68-Way-PLCC-Plug) that I used and bought there.

[Socket](https://app.adam-tech.com/products/download/data_sheet/198229/plcc-68-at-data-sheet.pdf) that I used and bought on [DigiKey](https://www.digikey.com/en/products/detail/adam-tech/PLCC-68-AT/9833042)

This is my fourth revision of this board:

* Revision 1 - The board needed the post through it (never sent this to the fab).
* Revision 2 - The traces were wired incorrectly.
* Revision 3 - The board was too big because the board had to be lower and then had to clear not only the post but the big capacitor.
* Revision 4 - This board.

I originally wanted to have the plug and socket on the bottom, and [this connection header](https://www.digikey.com/en/products/detail/te-connectivity-amp-connectors/5103308-3/1114901) on the top.  I found out in the end that I needed to solder the cable right to the header in order to have the height correct.  Also, the plug described above was too tall.  I had to cut down the plug one layer.  There is another [low height connector](https://us.warwickts.com/4391/W9305-68-Way-PLCC-Plug) that is through hole but sold only in bulk.  If I ever get enough gumption and money I will try to redesign the card with that plug in mind.

Steps are:
1) Get all the supplies (plug and PLCC68 socket).
2) Get the board(s).
3) Get (or build) an RGBToHDMI and the associated 12 bit card.
4) Cut down the plug (not an easy task).
5) Surface mount the plug.
6) Through hold solder the socket.
7) Connect the cable that is long enough to go through the opening on the IIgs.
8) Unplug the VGC (I suggest a good puller) and insert the VGC into the socket on the board.
9) Connect your RGBToHDMI 12 bit connector to the cable (!!DO NOT!! Supply power to the RGBToHDMI.  The IIgs cable already has power on it.)
10) Connect to your HDMI monitor.

I included the ROM 03 IIgs Kicad stuff because I only used a socket over the top of the present VGC which is soldered to the motherboard. The pinout I originally did for the ROM 03 IIgs.
12) Start up the monitor and the IIgs.
