# BABBIT36 BUILD STEPS
Designed by [ChrisChrisLoLo](https://github.com/ChrisChrisLoLo)

---
## PICTURES
![BABBIT36](/images/top.jpg)\
![BABBIT36](/images/side.jpg)\
![BABBIT36](/images/angle.jpg)\
![BABBIT36](/images/bottom.jpg)

---
## REQUIRED
- Seeed Studio XIAO nRF52840 (Sense)
![XIAO](/images/xiao.jpg)
- 3.7 V 301230 110mAh Battery
![BATTERY](/images/battery.jpg)
- 4mm M2 screws 6 pieces
![SCREWS](/images/screws.jpg)
- Adhesive rubber feet 4 pieces
![FEET](/images/feet.jpg)
- SMD solder paste syringe
![PASTE](/images/paste.jpg)
- JST PH2.0mm male 2 pin connector
![JST](/images/jst.jpg)
- JST PH terminal pin
![PIN](/images/pin.jpg)
- 0.08-1.0mm^2 crimping tool
![CRIMPER](/images/crimper.jpg)
- Good soldering iron with a narrow tip e.g. FNIRSI HS-02
![IRON](/images/iron.jpg)
- Kailh choc v1 switches 36 pieces
![SWITCH](/images/switch.jpg)
- Chosfox cfx keycaps 36 pieces
![KEYCAPS](/images/keycaps.jpg)

---
## STEPS
### Case
I used JLCPCB's CNC service for the case. Get the files [here](https://github.com/Siriuslyblack/how.i.built.the.babbit36/tree/main/cnc)
These were my settings
![CASESETTINGS](/images/casesettings.png)
### Board, Backplate and Assemply
Gerbers can found [here](https://github.com/Siriuslyblack/how.i.built.the.babbit36/tree/main/pcb)
Bill of materials and placement file [here](https://github.com/Siriuslyblack/how.i.built.the.babbit36/tree/main/assembly)
Board fabrication and assembly settings
![BOARDSETTINGS](/images/boardsettings.png)
Uploaded the bom.xlsx and cpl.xlsx files here
![BOMCPL](/images/bomcpl.png)
Made some adjustments to the final placement here
![FINAL](/images/finalplacement.png)
Backplate settings
![BACKPLATESETTINGS](/images/backplatesettings.png)
### Flashing Firmware
Before soldering I flashed the firmware to the mcu to make sure everything works. Clicking the small button on the xiao twice after connecting it to the pc makes it come up as usb storage. I just copied [this](https://github.com/Siriuslyblack/zmk-config/blob/master/babbit36-seeeduino_xiao_ble-zmk.uf2) file to the xiao and it rebooted and was detected as a keyboard indicating that everything works.
### Soldering the MCU
I used a clothespeg to temporarily fasten the mcu to the board after aligning it properly. I then applied some solder paste using the syringe to the battery pads on the xiao through the holes on the board and added heat with the soldering iron. I inserted the tip of the iron in the hole to get a good connection. After cooling I removed the clothespeg and soldered all the pads on the opposite side using the same method. Its straightforward because the mcu stays fastened after soldering the battery pads. Thats all the soldering I needed to do for this board.
![BATPADS](/images/batpads.jpg)\
![MCUPADS](/images/mcupads.jpg)
### Connecting the battery
I tested all the switches and everything worked so I used the crimping tool to crimp the terminal connector pins to the battery wires like shown in [this](https://www.youtube.com/watch?v=jHfYzrSF4pY) video. I then inserted the wires into the JST male plug and the plug into the board battery connector.
![BATCON](/images/batcon.jpg)
### Installing the case, switches and backplate
I put the board inside the case and installed the switches and fastened the backplate with 6 m2 screws. My build was complete.
