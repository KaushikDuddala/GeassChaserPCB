
# Geass Chaser

Geass-based chaser based on [HackClub's Blinky Guide](https://blueprint.hackclub.com/starter-projects/blinky) with an added bar on the bottom for the parts

## BOM:
|ID |Name               |Designator|Footprint                |Quantity|Manufacturer Part|Manufacturer |Supplier|Supplier Part|Price|
|---|-------------------|----------|-------------------------|--------|-----------------|-------------|--------|-------------|-----|
|1  |1uF                |C1        |CAP-TH_BD5.0-P2.00-D0.8-FD|1       |KF010M050C110A   |CapXon(丰宾)   |LCSC    |C62934       |0.026|
|2  |10nF               |C2        |CAP-TH_L8.0-W4.0-P5.00-D1.2|1       |N09F1B103MN0B0S0N0|STE(松田)      |LCSC    |C249157      |0.037|
|3  |PZ254V-11-02P      |H1        |HDR-TH_2P-P2.54-V-M      |1       |PZ254V-11-02P    |XFCN(兴飞)     |LCSC    |C492401      |0.013|
|4  |XL-502UWC          |LED1,LED2,LED3,LED4,LED5,LED6,LED7,LED8,LED9,LED10|LED-TH_BD5.9-P2.54-RD_WHITE|10      |XL-502UWC        |XINGLIGHT(成兴光)|LCSC    |C2895480     |0.024|
|5  |Header-Male-2.54_1x1|P1        |HDR-TH_1P-P2.54-V-M      |1       |2.54-1*1P针       |BOOMELE(博穆精密)|LCSC    |C81276       |0.008|
|6  |1kΩ                |R1        |RES-TH_BD2.3-L6.5-P10.50-D0.5|1       |MF1/4W-1KΩ±1%T52 |华星机电         |LCSC    |C713997      |0.007|
|7  |470Ω               |R2        |RES-TH_BD2.2-L6.5-P10.50-D0.6|1       |MFR0W4F4700A50   |UNI-ROYAL(厚声)|LCSC    |C58592       |0.01 |
|8  |50kΩ               |R3        |RES-ADJ-TH_3P-L9.5-W4.85-P2.50-BL-L|1       |3296X-1-503      |BOCHEN(博晨)   |LCSC    |C118912      |0.177|
|9  |100kHz             |U1        |DIP-8_L9.8-W6.6-P2.54-LS7.6-BL|1       |NE555P           |TI(德州仪器)     |LCSC    |C46749       |0.457|
|10 |CD4017BE(LX)       |U2        |PDIP-16_L19.3-W6.4-P2.54-LS7.94-BL|1       |CD4017BE(LX)     |LX(灵星芯微)     |LCSC    |C32710674    |0.126|


## Final Product:

![FinalImg](https://raw.githubusercontent.com/KaushikDuddala/GeassChaserPCB/refs/heads/main/PCB/Nov%2011%20Screenshot%20from%20Geass%20Chaser.png)

## Process:

#### Started with making the schematic based on the guide:

![Schematic](https://raw.githubusercontent.com/KaushikDuddala/GeassChaserPCB/refs/heads/main/PCB/Geass%20Chaser%20Schematic%20Nov%2012%202025.png)


#### Made a DXF of the board outline from an image using an online converter but later had to change the image to have a block on the bottom for the main internals:

![Editor Picture](https://raw.githubusercontent.com/KaushikDuddala/GeassChaserPCB/refs/heads/main/Pictures/Screenshot%202025-11-11%20at%2012.00.12%E2%80%AFPM.png)

#### Put down all the parts and used the autorouter

![Routed Parts](https://raw.githubusercontent.com/KaushikDuddala/GeassChaserPCB/refs/heads/main/PCB/Screenshot%202025-11-12%20at%2012.11.41%E2%80%AFAM.png)

#### Final Product!!:

![FinalImg](https://raw.githubusercontent.com/KaushikDuddala/GeassChaserPCB/refs/heads/main/PCB/Nov%2011%20Screenshot%20from%20Geass%20Chaser.png)