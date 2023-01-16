# STM32-BluePill-JLink
1. Flash the STLinkV2.J16.S4.bin file
2. Update the ST-Link with the ST-Link Upgrade utility.
3. Download STLinkReflash (Version 190812 tested). The version in this repository has been pre modified, but instructions are below if you want to do it yourself.
    Modify the following offsets in STLinkReflash.exe
    2566 3C > 38
    2567 40 > C0
    26B2 3C > 38
    26B3 4A > C0
4. Run STLinkReflash.exe and accept, selecting option 1.
5. Fun and profit!
