# Rectangle-Controller
Uses the RP2040 to emulate a Rectangle style controller in a smaller package. This device only uses the 3.3V line to power.

REQUIRES EXTERNIAL POWER SUPPLY (3.3V) TO PROGRAM

  JLCPCB ordering instructions:

NOTE: JLCPCB minium order is 5 boards

First you will need to preorder some components because JLCPCB does not keep them in stock and sources them from other companies.

1) Make a JLCPCB account and sign in
2) Go to "your profile" / Parts Manager / Order Parts / Parts Library / Global Parts sourcing 
3) Enter in "12401610E4#2A" as your part, This is the USB-C connector
4) Find the ARROW distributer and add 5 to your cart
5) Go to "your profile" / Parts Manager / Order Parts / Parts Library / Cart / Global Sourcing Parts
6) Select the part and checkout

You will be able to view the status of your order in "your profile" / Parts Manager / Order Parts / Parts Order History

It will take about a week to arrive, you can continue on ordering the parts when the status of the order is "Complete"

 Finally you can order the board!

1) Log in and click on "order now"
2) Upload the included gerber.zip file
3) make sure "2 layers" are selected
4) select "PCB assembly" then click next
6) upload the included BOM and CPL files
7) Make sure 11 parts are detected and 11 parts are confirmed
8) Confirm the placement (the USB-C will not render but that is ok)
9) Order the product

  Programming the Board:

1) Plug in USB-C into computer
2) Power the device with 3.3V through the 3.3V pin out at the bottom of the board (don't forget to connect ground to one of the 4 ground pins)
3) Windows should recognize it as a storage device and automatically open the unit
4) drag and drop uf2 file onto storage device and it will automatically eject (Haystack firmware recommended: https://github.com/JonnyHaystack/HayBox)

![7711FD64-64CC-4310-9353-E3A3F6A96C94_1_102_a](https://github.com/AlC0da/Rectangle-Controller/assets/97121247/3ebb52dc-9d99-4f9a-8d05-8988f2d96248)

![DD0D312B-9328-4153-BD69-E2851F2CD043_1_102_a](https://github.com/AlC0da/Rectangle-Controller/assets/97121247/4b42d204-b904-4451-ba9c-3ef0589e62b7)

![Rectangle Schematic](https://github.com/AlC0da/Rectangle-Controller/assets/97121247/e8f9ea95-e831-4cd0-a92c-aaa7ef259994)

![Rectangle PCB](https://github.com/AlC0da/Rectangle-Controller/assets/97121247/13c4cdab-edb6-4dd9-ad49-86d03f13b97f)
