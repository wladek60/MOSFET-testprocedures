# MOSFET-testprocedures

## Test Procedures for MOSFET SPICE Model Validation
Verilog-A compact models validation for Open PDK's

The emergence of open PDK initiatives reduce barriers to entry for integrated circuit (IC) design and manufacturing, serves thelong term goal of promoting academic/industrial collaboration, and stimulate innovation in the field of semiconductor IC design. Open PDKs have the potential to "standardize" PDKs (process design kit), and move away from proprietary/licensed EDA vendor formats. This is needed to democratize open source IC design flow and manufacturing. Open PDKs provide open access to IC design resources.

The compact/SPICE models of semiconductor devices are the core of open PDK efforts. SPICE executes implemented Verilog-A compact models. A model of a semiconductor device (passive elements and active, eg: diodes, mosfets, bjts) is primarily a "compact device model". Validation benchmarks are not yet available in the public domain. This project represents the very first attempt to implement these tests for the compact model available in open PDKs. It aims to establish such tests for the compact models in open PDKs, which are intended to be generic enough for model quality assurance testing with FOSS circuit simulators such as GnuCAP, ngspice, xyce, Qucs, among others.

The project's crosslinked websites: 
https://www.mos-ak.org/open_dir
https://github.com/dwarning/VA-Models
https://si2.org/cmc-standard-models/
