# Steam Deck OLED Pro
This project is to make the Zotac Zone Handheld Gaming PC (ZGC-G1A1W) act and feel like a Steam Deck OLED (Pro) when installed with Bazzite.

Desired outcome: 
1. Back Buttons work as native back button, like how the buttons on ROG Ally work.
    - Currently they can be made to work with the open source drivers by mapping the back keys to another key, like a mouse button, keyboard key, or front face button.
1. With the OpenZotacZone Drivers installed, the Left "Steam" button and right "..." button should work as they do without the drivers.
    - Currently, those button stop working correctly when the OpenZotacZone Drivers are installed.
    - The left button continues to work but now you need to hold it 3 seconds.
    - The right button doesn't work even when you hold it for 3 seconds.
1. Trackpad should work on the Steam Keyboard just like they do on the steamdeck.
1. RGB Control via HHD
1. Dial Controls actually working
1. Dial Control via HDD
1. ZotacZone Drivers built into Bazzite, signed to allow for safe boot.
1. Zotac Zone (Gen 1 - ZGC-G1A1W) selectable from the dropdown [here](https://bazzite.gg/#image-picker)

Extra Features:
- Firmware/BIOS settings upgrades/changes from Bazzite. Currently only available with the Windows Image.
- The track pads appear to the OS exactly like the steamdeck trackpad do.
- Include the [HDR profile](https://github.com/OpenZotacZone/Zotac-Zone-HDR-144hz)

### Links
- [Zotac Device Page](https://www.zotac.com/us/product/handheld/zone-handheld-gaming-console)
- [Handheld Daemon GitHub](https://github.com/hhd-dev/hhd)
    - [My GitHub Issue](https://github.com/hhd-dev/hhd/issues/288)
- [OpenZotacZone/Drivers](https://github.com/OpenZotacZone/ZotacZone-Drivers)
- [Forum about it](https://www.answeroverflow.com/m/1320392410496499754)
- [hwinfo/devices](https://github.com/hhd-dev/hwinfo/tree/21b7442219922233c41c0568995214ba92873f69/devices)
