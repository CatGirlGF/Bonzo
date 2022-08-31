# Bonzo
## Pro Micro based custom pseudo 40% keyboard inspired by [V4N4G0N](https://trashman.wiki/keyboards/v4n4g0n)

![Bonzo](https://i.imgur.com/aKBtpmu.jpg)

## Kicad libraries used:

https://github.com/AcheronProject/AlexandriaLibrary
https://github.com/keebio/Keebio-Parts.pretty
https://github.com/ai03-2725/MX_Alps_Hybrid/tree/master/MX_Only.pretty

## Gerbers

The provided gerbers have been created according to the specifications of JLCpcb. For plate the size is 275.3mm * 113.4mm

## Cases 

### Acryllic case

The case is designed to be cut out of 3mm acryllic and uses a 1.5mm switchplate.

I used 4mm female to female M2 standoffs from this listing: https://www.aliexpress.com/item/1005003106030065.html

https://i.imgur.com/W8KVRhH.png Picture for reference if the listing gets deleted

### 3D printable case WIP

This case has been printed fully and works, but the screwholes are too tight and have to be drilled.

Updated case design with heat insrets and correct size holes at some point.

## Firmware 

I have provided a compiled .hex and a layout json that will let you use the keyboard with VIA.

The full QMK library is also provided incase it is needed.

## BOM

### General parts for wired

| Name                    | Pieces | Description                          |
| ----------------------- | ------ | ------------------------------------ |
| PCB                     | 1      | Gerbers available at this repository |
| 1,5mm switch plate      | 1      | Gerbers available at this repository |
| 2U PCB mount stabilizer | 3      | Also known as screw-in stabilizers   |
| MX hotswap sockets      | 54     | Kailh or equivalent                  |
| MX style switch         | 54     |                                      |
| 1N4148 diodes           | 54     | SOD-123 packaging                    |
| ProMicro or similar     | 1      |                                      |

### For Wireless

| Name                    | Pieces | Description                                                                                            |
| ----------------------- | ------ | ------------------------------------------------------------------------------------------------------ |
| PCB                     | 1      | Gerbers available at this repository                                                                   |
| 1,5mm switch plate      | 1      | Gerbers available at this repository                                                                   |
| 2U PCB mount stabilizer | 3      |                                                                                                        |
| MX hotswap sockets      | 54     | Kailh or equivalent                                                                                    |
| MX style switch         | 54     |                                                                                                        |
| 1N4148 diodes           | 54     | SOD-123 packaging                                                                                      |
| nice!nano v2            | 1      |                                                                                                        |
| LiPo battery            | 1      | Refer to [nice!nano's documentation](https://nicekeyboards.com/docs/nice-nano/) on battery suggestions |
| Slide switch            | 1      | JS202011AQN or similar                                                                                 |

#### For acryllic case

| Name                               | Pieces    | Description                        |
| ---------------------------------- | --------- | ---------------------------------- |
| Acrylic layers                     | 1 of each | Files available in this repository |
| 4-6mm M2 female - female standoffs | 8         | Hexagon shaped ones won't fit      |
| M2 screws                          | 16        |                                    |

#### For 3DP case

| Name         | Pieces | Description                         |
| ------------ | ------ | ----------------------------------- |
| Top case     | 1      |                                     |
| Bottom case  | 1      |                                     |
| M2x15 screws | 4      | Self-tapping screws are recommended |
| M2x10 screws | 4      | Self-tapping screws are recommended |



## Keycaps
You will also need keycaps to fit the layout pictured below 
![layout](https://i.imgur.com/XcQJnYB.png)

# Disclaimer
**Everything in this repo has been published with intent to allow others to build this keyboard if they want to and is published under MIT License. The versions I have uploaded have been tested to work. I take no responsibility of designs being incorrect or flawed. Check all the files yourself before you purchase anything. If something is broken or missing please let me know and ill try and see if I can fix the issue.**


Also here is the cat who inspired the name and the silkscreen
![The boy](https://i.imgur.com/2VJDWau.jpg)
