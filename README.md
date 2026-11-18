# Semiconductor Engineering Learning Journey

**Owner:** [ZAIDRAR](https://github.com/ZAIDRAR)  
**Status:** Learning in progress. The existing ALU and MAC now have executed RTL verification and generic synthesis evidence (18 November 2026). Analog circuits, TCAD and physical implementations remain in progress or planned.

I am an electrical engineering student building a practical foundation in semiconductor physics, CMOS electronics, analog/mixed-signal design, digital VLSI, device simulation, and AI hardware.

## Study areas

| Topic | Study folder | Initial goal |
|---|---|---|
| Semiconductor physics | [01 — Fundamentals](01-semiconductor-physics/README.md) | Explain energy bands, doping, and PN junctions |
| MOSFET and CMOS | [02 — Devices and CMOS](02-mosfet-and-cmos/README.md) | Simulate MOSFET curves and a CMOS inverter |
| Analog, ADC and DAC | [03 — Mixed signal](03-analog-circuits-adc-dac/README.md) | Design and test an R-2R DAC |
| Verilog and digital logic | [04 — RTL design](04-verilog-and-digital-design/README.md) | Write and verify an 8-bit ALU |
| VLSI chip design | [05 — Physical design](05-vlsi-chip-design/README.md) | Understand synthesis, timing and layout |
| TCAD simulations | [06 — Device modeling](06-tcad-simulations/README.md) | Set up a simple numerical semiconductor device model |
| AI hardware | [07 — Accelerators](07-ai-hardware/README.md) | Design a small multiply-accumulate datapath |

## Project repositories — active and planned

All four dedicated projects are initialized. The [Operation X audit](docs/operation-x-review-2026-11-18.md) records exact inspected revisions and distinguishes verified RTL results from remaining experiments.

- [MOSFET characterization](https://github.com/ZAIDRAR/mosfet-characterization) — repository initialized; experiments pending
- [8-bit ALU in Verilog](https://github.com/ZAIDRAR/8bit-alu-verilog) — 524,288 exhaustive binary-input vectors passed; generic synthesis recorded
- [CMOS ADC design](https://github.com/ZAIDRAR/cmos-adc-design) — repository initialized; theoretical reference model and experiment plans added, circuit simulations pending
- [Tiny AI accelerator](https://github.com/ZAIDRAR/tiny-ai-accelerator) — signed MAC verified against Python over 142,123 cycles; 2×2 array planned

## Progress and documentation

- [Prioritized engineering roadmap](roadmap.md)
- [Audit and verified results](docs/operation-x-review-2026-11-18.md)
- [15 practical project levels and specifications](docs/engineering-projects.md)
- [Books, legal free resources and chapter guide](docs/resource-guide.md)
- [Learning log](learning-log.md)
- [Documentation method](docs/documentation-method.md)
- [Experiment report template](templates/experiment-report.md)
- [LinkedIn post template](templates/linkedin-post.md)

## Method

1. Understand the theory and write a prediction.
2. Build or simulate a reproducible experiment.
3. Keep source files, settings, plots, and verification evidence.
4. Explain the difference between expected and observed results.
5. Share verified findings, limitations, and next steps.

> Topic folders remain learning plans until understanding is demonstrated. Dated verification reports establish only the specific tests and conditions they describe.
