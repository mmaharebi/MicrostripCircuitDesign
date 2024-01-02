# Microstrip Circuit Design
Welcome to the repository for the Microwave and Optical Design Lab Project 2. This project delves into the intricate process of designing and implementing planar passive microstrip structures using printed circuit boards (PCBs). With a focus on four distinct experiments, each centered around various types of couplers or power dividers, the project aims to achieve several objectives:

## Demands
### Learn the Art of Microwave Circuit Design:
- Understand the intricacies of designing, building, and testing microwave planar circuits through the use of microstrip lines and printed circuit boards.
### Master Microwave Couplers and Power Dividers:
- Develop familiarity with key concepts and parameters related to microwave couplers and power dividers, such as coupling coefficient, isolation, bandwidth, phase difference, etc.
### Bridge the Gap Between Simulation and Measurement:
- Compare simulation and measurement results of the designed structures, meticulously analyzing any sources of discrepancy.
### Optimize Structure Performance:
- Apply optimization techniques and methods to enhance the performance of the structures.

## Experiment Overview:
### Experiment 1: Directional Coupler
#### Objective:
- Design and build a directional coupler with a specified coupling coefficient using coupled microstrip lines.
#### Tasks:
- Utilize Pozar's book and linecalc software for dimensions and impedances.
- Simulate in ADS schematic and EM environments, comparing results with design goals.
- Measure scattering parameters and phase difference.
- Analyze transition from coaxial cable to microstrip line.
- Optional: Attempt bandwidth enhancement with multisection coupled line coupler method.
### Experiment 2: Branch-Line Coupler
#### Objective:
- Design and construct a branch-line coupler using quarter-wave microstrip lines.
#### Tasks:
- Employ linecalc software for line dimensions.
- Simulate in ADS schematic and EM environments, comparing results with design goals.
- Measure scattering parameters and phase difference.
- Analyze transition from coaxial cable to microstrip line.
- Optional: Explore bandwidth enhancement with multisection branch-line coupler method.
### Experiment 3: Rat-Race Coupler
#### Objective:
- Design and construct a rat-race coupler using half-wave microstrip lines.
#### Tasks:
- Use linecalc software for line dimensions.
- Simulate in ADS schematic and EM environments, comparing results with design goals.
- Measure scattering parameters and phase difference.
- Analyze transition from coaxial cable to microstrip line.
- Optional: Investigate power division ratio variations and effects of impedance matching.
### Experiment 4: Wilkinson Power Divider
#### Objective:
- Design and build a Wilkinson power divider using quarter-wave microstrip lines and a 100-ohm resistor.
#### Tasks:
- Calculate dimensions with linecalc software.
- Simulate in ADS schematic and EM environments, comparing results with design goals.
- Measure scattering parameters and phase difference.
- Analyze transition from coaxial cable to microstrip line.
### Report Structure:
For each experiment, the following sections are required in your report:

- Introduction:

Provide a brief overview of the theory and principles underlying the structure under study.
- Design:

Detail the design procedure, including calculations for dimensions and impedances. Include schematic and layout diagrams in ADS.
- Simulation:

Present and analyze simulation results in ADS schematic and EM environments. Compare with design goals and explain differences. Include simulation results of the transition from coaxial cable to microstrip line in HFSS or CST software.
- Measurement:

Present and analyze measurement results of scattering parameters and phase difference. Compare with simulation results, explaining sources of error and discrepancy.
- Conclusion:

Summarize main findings and achievements, discuss limitations and challenges, and suggest possible improvements and future work.
- References:

- Include a list of sources used or cited in your report.

Remember to submit the PCB layout file in DWG format, following the standard template and naming convention. Attach all simulation files in a zip file, excluding results folders to reduce file size.

## Project Report: Design and Implementation of Rat-Race Coupler
This comprehensive project report outlines the theoretical foundation and simulation intricacies involved in crafting a Rat-Race Coupler for an operational frequency of 2.4 GHz. The specified bandwidth for this device is set at 1.5 GHz with a stringent criterion of Sii < -25 dB. All substrate details, microstrip-to-coaxial transition parameters, and other relevant aspects adhere to project instructions.

### Theory of Rat-Race Coupler
The report delves into the theoretical underpinnings, providing a rigorous derivation of the scattering parameters for the Rat-Race Coupler in both even and odd modes. Additionally, the equations essential for calculating line widths and lengths are meticulously presented, offering a clear understanding of the design's theoretical framework.

### Simulation of Rat-Race Coupler
The simulation results, conducted through the use of ADS and Ansys Electronics Desktop software, are showcased in the report. The initial design undergoes optimization by fine-tuning select parameters. Special attention is given to investigating the impact of the microstrip-to-coaxial transition and resistor discontinuity. The final design demonstrates commendable performance metrics, including favorable return loss, insertion loss, and output phase difference.

### Figures and Tables
Numerous figures and tables are seamlessly integrated into the report, providing visual clarity on dimensions, schematics, and simulation outcomes of the Rat-Race Coupler. Each figure and table is appropriately numbered and referenced in the text, enhancing the report's overall readability and comprehension.

### References
The report draws upon various references, enriching the reader's understanding of Rat-Race Coupler theory and design intricacies. The comprehensive list of references is thoughtfully compiled at the end of the report, offering readers the opportunity to explore additional resources for a deeper grasp of the subject matter.
