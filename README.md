# PCB Keychain

This keychain have a NFC chip and a LED. It act as a RFID tag, which use [NFC tools](https://apps.apple.com/my/app/nfc-tools/id1252962749) to program the NFC chip.

## Features:
- RFID tag to carry url
- LED for glowing effect

## PCB:
Here's my PCB! It was made in KiCad. 
Schematic

<img width="372" height="514" alt="Screenshot 2026-03-19 at 11 23 23 AM" src="https://github.com/user-attachments/assets/52fd2498-a4b0-4e92-95a5-4251d7a84f99" />

PCB

<img width="364" height="473" alt="image" src="https://github.com/user-attachments/assets/d569af90-965d-486c-99f3-79b6e4f180fb" />

I generate the antenna with this [script](https://github.com/Neurotech-Hub/KiCad-Plugins-8.0/tree/main).
I also follow these design guide: [design guide 1](https://www.nxp.com/docs/en/application-note/AN11276.zip), [design guide 2](https://neurotech-hub.github.io/KiCad-Antenna-Generator/an2972-how-to-design-an-antenna-for-dynamic-nfc-tags-stmicroelectronics.pdf)

## Result:

<img width="432" height="634" alt="image" src="https://github.com/user-attachments/assets/1e6a91fe-6530-4a21-b5ee-6f19aba757e3" />
<img width="615" height="634" alt="image" src="https://github.com/user-attachments/assets/c7a913d9-f5e9-4060-b753-6c4f0e1a69eb" />

## BOM:
Here should be [everything]([https://docs.google.com/spreadsheets/d/1zaCOEk-ZGnszMIk4FFVV_LndeX-SJLxj8WLiJESGuGM/edit?gid=0#gid=0](https://docs.google.com/spreadsheets/d/1KiuXZSORq6o1wyT1NHcNB7JtL9FbZkCRXqoJQaos5Fs/edit?usp=sharing)) you need to make this keychain

- 1x 220nF capacitor
- 1x 51 ohm resistor
- 1x 2V LED
- 1x NT3H2111W0FHKH	NFC chip
