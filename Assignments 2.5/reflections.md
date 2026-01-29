Diode Temperature Simulation (LTspice)

Task Overview

This project investigates how temperature affects the electrical behavior of a 1N4148 diode using LTspice DC sweep simulation.

The diode was simulated at:

- 25 °C (room temperature)
- 75 °C (high temperature)

The circuit consists of a DC voltage source, a 1 kΩ series resistor, and the diode under test.

Observations

Forward Voltage

- At 25 °C, the diode begins conducting at approximately 0.7 V.
- At 75 °C, the forward voltage drops to around 0.6 V.

This shows that forward voltage decreases as temperature increases.

Reverse Current

- At 25 °C, reverse leakage current is extremely small.
- At 75 °C, reverse leakage current increases significantly.

Reverse current rises rapidly with temperature.

Why Temperature Affects Diodes

Higher temperature increases charge carrier energy inside the P-N junction, reducing the barrier voltage and increasing leakage current.

Importance in Real Systems

Temperature effects matter because they influence:

- Voltage regulation accuracy
- Power losses
- Leakage currents in sensitive circuits
- Reliability and thermal stability of electronic systems
