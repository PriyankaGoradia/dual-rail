# Digital Electronics Project #1: Dual Rail DC Power Supply

## Abstract
In this project, we designed and prototyped a ±10V, 25mA dual rail supply ensuring voltage regulation (<5%) and ripple voltage (<0.5%). The design encompassed three stages: rectifier, filter, and regulator. Part 1A involved designing and implementing the rectifier and filter stages successively, while Part 1B focused on the regulator stage, specifically using a zener-shunt regulator to minimize voltage ripple.

## Design
The project was divided into three main stages:
1. **Rectifier Stage:** Utilizing a full wave rectifier to convert bipolar signals into positive and negative unipolar signals.
2. **Filter Stage:** Employing a capacitor filter to smoothen the rectified signals and reduce AC components.
3. **Regulator Stage:** Incorporating zener-shunt regulators to further minimize voltage ripple.

## Simulation Results
Simulation results were obtained using LTSpice. The output voltages, ripple percentages, and voltage regulation were analyzed to validate the design.

## Prototype Results
Prototype results were obtained by implementing the designed circuits on an SK-10 breadboard and measuring the output voltages using an oscilloscope. These results were compared against simulation and theoretical values.

## Conclusion
The project successfully achieved the objectives of designing a dual rail DC power supply meeting specified constraints. Performance evaluation showed satisfactory results, with voltage regulation and ripple percentages within expected ranges.


