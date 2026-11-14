# Power rail for a 9 V and 5 V modular synth

This PCB supplies power to the modules of my modular synth from a rechargeable battery. It gives 9 V and 5 V outputs on JST connectors.

<img width="623" height="101" alt="Power rail" src="https://github.com/user-attachments/assets/24fb0420-4ad7-429f-a834-7d24cf97eeb2" />

## Build guide and video

- Step-by-step build guide on Instructables: not available yet.
- Video on YouTube: not available yet.

## How it works

1. A USB-C charging module charges the battery.
2. A step-up voltage regulator increases the battery voltage to 9 V.
3. JST connectors along the rail supply 9 V to the modules. Most of my modules use an Arduino Nano, which operates from 9 V.
4. A second voltage regulator on the rail decreases the voltage to 5 V, for modules that need 5 V.

## What you need

- All parts are in the [parts list](Parts%20List.pdf).
- The Gerber files for the PCB are in `Power Rail_Gerber File.zip`. You can send them to a PCB maker.

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `Eagle Files/` | Eagle files for the PCB |
| `Power Rail_Gerber File.zip` | Gerber files for the PCB, ready to order |
| `Parts List.pdf` | Parts list |

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

This project uses the [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0). Copyright (c) 2025 Marcus (lonesoulsurfer).

You can make, change and sell boards from these files. If you share or sell a changed design, you must also share the changed design files under the same licence.
