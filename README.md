# Prototype_Boards
Workspace for Alorium boards before they get released

Please Note: These board tools are experimental and not intended for general use. If you choose to use them know that you do so at your own risk and you may experience adverse effects.

There is a known issue when running the 64MHz image on an XLR8 board and trying to burn another image. The new image will burn correctly, but at the end of the bootloader burning process the board reports it is still using the 64MHz image. Simply power-cycling the board and restarting it will fix this, and the newly-burned image will be reported.

Use this URL into the 'Additional Boards Manager URLs' input field:

	https://raw.githubusercontent.com/AloriumTechnology/Prototype_Boards/master/package_aloriumtech_proto_index.json

