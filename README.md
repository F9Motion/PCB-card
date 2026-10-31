# PCB Business Card
**A real printed circuit board that works as a business card and a thank-you gift for loyal customers.**
<img width="1675" height="893" alt="Снимок экрана 2026-10-31 155251" src="https://github.com/user-attachments/assets/95635f8c-c08c-4b56-be1f-4bfab2a9db42" />

## About

A 2-layer PCB business card for **F9Motion**, the brand of motion designer **Begmetov Rasul**. The card carries the logo, the software I work with (Ae, Pr, Me, Ps, Ai), contact details and a hole for a keychain. A 3D printed case with a sliding lid protects it.

The card has no battery and no firmware. The whole design is made of copper, solder mask and silkscreen.

## Why I made this

I work as a motion designer: logo animations, intros and other video work. I wanted a special thank-you for people who come back.
<img width="1152" height="648" alt="Без имени" src="https://github.com/user-attachments/assets/b207d0a6-9bf9-43fb-a817-57efd3fcaad5" />
> **The rule is simple:** if a customer buys my service **3 or more times**, I ship them this PCB card as a gift.

It is a loyalty reward and a business card at the same time. It is far more memorable than a paper card, because it is a real board that I designed myself.
## Features
- Gift for loyal customers, sent after 3+ orders
- Real 2-layer PCB, 1.6 mm
- Logo, text and graphics made with silkscreen, copper and solder mask
- Decorative component footprints: a 10-position DIP switch and a 24-pin SMD IC
- Mounting hole for a keychain
- Contacts on the card: YouTube, Telegram, phone
- 3D printed case with a YSWS lid
- Designed in KiCad, case modeled in Blender

## Pictures
PCB:
<img width="1675" height="893" alt="Снимок экрана 2026-10-31 155251" src="https://github.com/user-attachments/assets/41416147-4c39-47aa-8d0d-477125c71b6a" />
PCB editor:
<img width="1917" height="1078" alt="Снимок экрана 2026-10-31 155300" src="https://github.com/user-attachments/assets/06616dce-b52f-4297-ad04-2ed2d32e3889" />
Case:
<img width="1588" height="837" alt="Снимок экрана 2026-10-31 155950" src="https://github.com/user-attachments/assets/67aff0c3-cbb8-474a-928e-f38fc9f1b845" />
Opened case:
<img width="1582" height="853" alt="Снимок экрана 2026-10-31 160002" src="https://github.com/user-attachments/assets/b9ddfa72-f958-4402-b9b3-6469dcc923ee" />
## How it works
This is a passive card. The design is drawn entirely in KiCad:

| Layer | What is on it |
|:--|:--|
| Silkscreen | `F9Motion` logo, tagline *The best motion designer ever!*, software icons, name, phone |
| Copper (F.Cu, B.Cu) | Decorative traces, text and shapes |
| Solder mask | Dark green color that makes the white silkscreen stand out |
| Footprints | `SW_DIP_SPSTx10_Slide_KingTek_DSHP10TS` and a 24-pin SMD IC, used as design elements |
| Edge.Cuts | Rectangular outline with a round hole in the corner |

### Board stats

| Parameter | Value |
|:--|:--|
| Layers | 2 (F.Cu, B.Cu) |
| Pads | 68 |
| Vias | 2 |
| Track segments | 395 |
| Card size | 70x50mm |

## Information on the card

| Field | Value |
|:--|:--|
| Name | Begmetov Rasul |
| Role | Motion designer |
| Software | After Effects, Premiere Pro, Media Encoder, Photoshop, Illustrator |
| YouTube | [@F9MotionAe](https://www.youtube.com/@F9MotionAe) |
| Telegram | [@F9Motionmp4](https://t.me/F9Motionmp4) |
| Phone | `+998 91 014 86 22` |

## How to assemble

1. **Order the PCB.** Use the Gerber files from the reposity
   Suggested options: 2 layers, 1.6 mm, green solder mask, white silkscreen and order in JLCPCB
2. **Decide on the parts.** To get a working DIP switch and IC, solder them on the marked footprints. For a flat card, leave the footprints empty.
3. **Print the case.** Print **bottom.step** and **top.step** from the step folder.
   Suggested settings: PLA, 0.2 mm layer height, `[15%]` infill. A light color for the top makes the `YSWS` text easier to see.
4. **Clean the PCB** with isopropyl alcohol to remove fingerprints.
5. **Put the card into the bottom part.** It sits in the rectangular recess.
6. **Close the case** with the top part.
7. **Add a keychain** through the corner hole (optional).

## Bill of Materials (BOM)

| Item | Cost | comment |
|:--|--:|:--|
| Print PCB | $4 | without shipping(I need $10) |
| bottom.step | $0.41 | Felament price only |
| top.step | $0.26 | Price taken form Bambu Studio |

## Credits

| Role | Tool |
|:--|:--|
| PCB design | KiCad |
| 3D case | Blender |
| Design | Begmetov Rasul |
