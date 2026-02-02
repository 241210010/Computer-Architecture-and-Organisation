# Computer Architecture and Organisation — Laboratory Work

This repository contains laboratory exercises and circuit designs created for the course "Computer Architecture and Organisation". Its purpose is to collect Logisim-evolution circuit projects, notes and example configurations that demonstrate fundamental digital logic building blocks used in computer design.

## Overview

- Author: 241210010
- Course: Computer Architecture and Organisation
- Primary tools: Logisim-evolution (recommended version: v4.0.0)

The repository focuses on practical, hands-on designs for combinational and sequential circuits (adders, multiplexers, encoders, and supporting wiring). Each .circ file is a Logisim-evolution project that can be opened directly with the Logisim-evolution application.

## Files in this repository

- adders.circ
  - Description: A Logisim-evolution project that contains implementations of basic adder circuits. The design includes logic gates, LED indicators and digital oscilloscopes configured to demonstrate the behaviour of sum and carry signals. Expect to find single-bit full-adders, arrangements forming multi-bit adders (ripple-carry style), and wiring that connects clocks, inputs (pins/dip switches) and outputs (LEDs/LedBars).
  - How to use: Open the file in Logisim-evolution. Use the provided input pins or DipSwitch components to apply test vectors. Observe outputs on LED components and the Digital Oscilloscope components to verify timing and logic behaviour.

- mux_n_encoder.circ
  - Description: A Logisim-evolution project that demonstrates multiplexers, n-to-1 selection logic and encoders. The project uses arrays of AND/OR/NOT gates and DipSwitch / LedBar components to let you toggle inputs and view encoded outputs. It can be used to study selection logic, priority encoding, and how multiplexers route selected inputs to outputs.
  - How to use: Open the file in Logisim-evolution (v4.0.0 recommended). Toggle the DIP switches to set input values or select lines, and watch the LedBar/LED outputs to validate the encoding or multiplexer selection.

## Requirements

- Logisim-evolution v4.0.0 or later (https://github.com/logisim-evolution/). The .circ files include project metadata which Logisim-evolution reads to place components and set gate parameters correctly.

## Usage tips

- When testing adders, apply input vectors to the input pins or DipSwitch components and step the clock (if used) to observe sequential behaviour. Use the Digital Oscilloscope components to visualise timing relationships for sum and carry.
- For the multiplexer/encoder circuits, test corner cases (all inputs 0, single 1 active, multiple 1s) to understand how the encoder implementation resolves priorities or collisions.
- If a component appears misconfigured after loading, make sure you’re running the recommended Logisim-evolution release — older forks or other circuit editors may not support all components or attributes.

## Contributing

If you want to contribute additional circuits, improved documentation or lab notes, please:
1. Fork the repository
2. Add new .circ files or update README.md with explanations and usage instructions
3. Open a pull request describing your changes

## License

This repository does not include an explicit license. If you plan to reuse or redistribute the circuits, contact the repository owner (241210010) or add a LICENSE file to clarify reuse terms.

---

If you would like, I can commit this README.md to the repository now.