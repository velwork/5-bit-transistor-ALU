# Simulation documentation

The schematic was simulated through the KiCad Simulator using ngspice. The five operations were exercised with A=`00101` and B=`00011`. Output pins `Y0`–`Y4` were checked from the DC operating-point output.

The CSV files record the expected and observed results. Full text output from each run is preserved under `Results/Raw_Logs/`. Output bits in the CSV are ordered `Y4` to `Y0`; raw log node names are `Y0` through `Y4`.

Observed output levels in these runs: LOW ≈ 0.0415–0.0417 V; HIGH = 5 V. These are measured values for these simulations, not a general electrical specification. The selector voltage is also included in each raw log.

To reproduce: open `Hardware/Schematic/ALU.kicad_sch` in KiCad, open the integrated Simulator, apply the recorded inputs and operation selection, run the configured analysis, and inspect the output-node voltages. Exact simulator setup details should be checked against the local KiCad project configuration.
