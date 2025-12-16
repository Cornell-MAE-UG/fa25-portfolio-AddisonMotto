---
layout: project
title: Analysis of Functions
description: Class project with Graphs
technologies: [MATLAB, python]
image: /assets/images/turbine.png
---


As part of MAE 4272, my team was tasked with designing, manufacturing, and experimentally validating a small-scale horizontal-axis wind turbine blade. The primary objective of the project was to maximize the turbine’s coefficient of power (C<sub>P</sub>) within the constraints of the Big Blue wind tunnel facility and the mechanical limits of the experimental hardware. This required translating aerodynamic theory into a physically realizable blade geometry that could operate safely, efficiently, and repeatably at low Reynolds numbers.

The project emphasized the full engineering workflow: aerodynamic modeling, design iteration, fabrication considerations, experimental testing, and post-processing of performance data. Rather than producing a purely theoretical design, the blade was evaluated under real flow conditions using controlled torque loading, allowing us to directly compare predicted performance with experimental results.

The blade geometry was developed using Blade Element Momentum (BEM) theory, which combines actuator disk momentum relationships with two-dimensional blade element aerodynamics. Our model solved for the spanwise chord and twist distributions required to meet a target tip-speed ratio of approximately 5, a value chosen to balance aerodynamic efficiency with structural and operational limits of the test setup.

Because the turbine operates at small scale, the blade experiences relatively low Reynolds numbers across most of its span. To account for this, the design was based around a representative Reynolds number of approximately 50,000. Lift and drag data were taken from low-Re airfoil studies, and the Selig 7075 airfoil was selected due to its favorable lift-to-drag performance in this regime. The blade was designed to operate at a near-constant angle of attack of approximately 6–6.5 degrees, corresponding to the airfoil’s peak aerodynamic efficiency.

Finite blade effects were incorporated into the design through Prandtl’s tip loss factor, which reduced the effective lift near the blade tip and influenced the final chord distribution. Using this corrected formulation, the BEM model predicted a peak coefficient of power of approximately 0.45 at the design tip-speed ratio. This theoretical prediction served as a benchmark for evaluating experimental performance.





