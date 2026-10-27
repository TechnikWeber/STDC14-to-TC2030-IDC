# STDC14 to TC2030-IDC adapter

<p>
  <img alt="For STLINK-V3" src="https://img.shields.io/badge/for-STLINK--V3MINIE-blue">
  <img alt="PCB: KiCad" src="https://img.shields.io/badge/PCB-KiCad-informational">
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

A tiny adapter PCB from the 14-pin **STDC14** debug connector (1.27 mm, used by the
STLINK-V3MINIE and other STLINK-V3 probes) to a 2×3 2.54 mm IDC header for a
**Tag-Connect TC2030-IDC** (or TC2030-SKEDD) cable — so you can program and debug STM32
boards over SWD with a Tag-Connect footprint instead of a connector.

![STDC14 to TC2030 adapter, rendered in KiCad](docs/board-3d.png)

## Files

- `STDC14_Adapter_to_JTAG_TC2030_SKEDD.kicad_sch` / `.kicad_pcb` — schematic and PCB (KiCad)
- [`production/`](production) — Gerber/drill zip, BOM, positions and netlist, ready to order
  (made with the KiCad Fabrication Toolkit)

<img width="418" alt="Adapter" src="https://github.com/user-attachments/assets/742616d8-45b4-4e1b-beae-bdfdfabbd2b9" /> <img width="383" alt="Adapter" src="https://github.com/user-attachments/assets/57772b06-4d7b-4722-a19e-9a666ba1624a" />

## License

[MIT](LICENSE).
