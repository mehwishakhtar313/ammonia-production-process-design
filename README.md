# Design of an Ammonia Production Unit with Optimized Energy Index

**Final Year Design Project | B.E. Chemical Engineering | NUST | 2025**

## Project Overview

This project focused on the process design and energy optimization of an industrial ammonia production unit based on the Haber–Bosch process. The study investigated the effects of reactor dimensions and operating parameters on conversion, hydrogen production, and overall energy consumption, with particular attention to steam and furnace fuel usage.

Aspen Plus V14 was used to simulate the ammonia production process and conduct sensitivity analyses. The project also included material and energy balances, reactor design, heat-exchanger calculations, preliminary economic analysis, process control, and HAZOP analysis.

## Objectives

- Develop an Aspen Plus simulation of an ammonia production process.
- Perform material and energy balances across major process units.
- Investigate the effects of reactor dimensions and operating conditions on conversion.
- Evaluate operating parameters to identify suitable conditions for process efficiency.
- Design selected equipment and assess the preliminary economic feasibility of the plant.
- Identify process hazards and consider instrumentation and control strategies.

## Process Description

The simulated process covers the main stages of conventional ammonia production:

1. **Feed preparation and desulfurization:** Removal of sulfur compounds from the natural gas feed.
2. **Steam reforming:** Conversion of hydrocarbons into hydrogen-rich synthesis gas in the pre-reformer and primary reformer.
3. **Secondary reforming:** Introduction of air to support further reforming and provide nitrogen for ammonia synthesis.
4. **Shift conversion:** Conversion of carbon monoxide into carbon dioxide while generating additional hydrogen.
5. **CO₂ removal and methanation:** Removal of carbon dioxide and residual carbon oxides.
6. **Ammonia synthesis:** Reaction of hydrogen and nitrogen in the synthesis loop, followed by ammonia separation.

### Overall Process

![Overall ammonia production process](images/ammonia_overall_process.png)


### Aspen Plus Simulation

![Aspen Plus process flowsheet](images/ammonia_process_flowsheet.png)

## Methodology

### 1. Process Simulation

- Developed the process flowsheet in Aspen Plus V14.
- Configured process components and thermodynamic property methods, including Peng–Robinson, SRK, and Steam NBS as documented in the thesis.
- Modelled catalytic reforming reactors using Langmuir–Hinshelwood–Hougen–Watson (LHHW) kinetics.
- Applied simplified rate expressions to the high-temperature shift, low-temperature shift, and methanator sections.

### 2. Material and Energy Balances

Performed material balances across major process units and evaluated energy balances for selected equipment and process sections. These calculations supported the process design and assessment of utility requirements.

### 3. Reactor Design and Sensitivity Analysis

Investigated the influence of reactor dimensions on conversion while maintaining a length-to-diameter ratio of 3 in the reported sensitivity study.

The reported optimum reactor tube lengths were:

| Reactor | Optimum length |
|---|---:|
| Pre-reformer | 2 m |
| Primary reformer | 5 m |
| Secondary reformer | 1 m |
| High-temperature shift converter | 3 m |
| Low-temperature shift converter | 5 m |
| Methanator | 2 m |

![Reactor length sensitivity analysis](images/reactor_length_sensitivity.png)

### 4. Operating-Parameter Optimization

Sensitivity analyses examined three operating parameters:

- **Steam-to-carbon ratio:** The reported optimum was 2.8, balancing hydrogen production and steam-related energy demand.
- **Primary reformer outlet temperature:** The reported optimum was 734°C, balancing conversion improvement against increasing energy consumption.
- **Air-to-carbon ratio:** The reported optimum was 1.9, considering methane conversion, hydrogen production, and nitrogen dilution.

![Operating parameter optimization](images/operating_parameter_optimization.png)

### 5. Equipment Design and Process Safety

The project also included:

- Primary reformer and high-temperature shift converter design calculations.
- Heat-exchanger sizing, heat duty, LMTD, overall heat-transfer coefficient, and pressure-drop calculations.
- Preliminary equipment-cost and plant economic estimates.
- Process control-loop diagrams and HAZOP analysis of the primary reformer section.

## Key Findings

- Sensitivity analysis identified reactor dimensions beyond which additional length produced limited improvement in conversion.
- The reported operating-parameter optima were a steam-to-carbon ratio of 2.8, primary reformer outlet temperature of 734°C, and air-to-carbon ratio of 1.9.
- The thesis concluded that the plant was already operating near its optimum conditions, with limited potential for further energy-index improvement through the studied adjustments alone.
- The project connected process simulation and equipment design with energy assessment, economic estimation, and process safety.

These findings reflect the reported study; the project did not establish a quantified plant-wide percentage reduction in energy consumption.

## Tools and Engineering Skills

- Aspen Plus V14
- Chemical process simulation
- Material and energy balances
- LHHW reaction kinetics
- Reactor design and sensitivity analysis
- Heat-exchanger design
- Preliminary economic analysis
- Process control and HAZOP

## Project Information

- **Project type:** Undergraduate final-year design thesis
- **Institution:** School of Chemical and Materials Engineering, National University of Sciences and Technology (NUST), Pakistan
- **Year:** 2025
- **Team project:** The thesis lists Mehwish Akhtar as team leader.
- **Supervisor:** Dr. Muhammad Adnan

## Scope and Limitations

The project was an academic process-design and simulation study. Its findings should be interpreted within the assumptions and models documented in the thesis. The reported sensitivity optima do not, by themselves, demonstrate a measured improvement in an operating plant.

## Future Work

- Quantify energy-index changes against a clearly defined baseline.
- Investigate heat integration and waste-heat recovery opportunities.
- Validate simulation outputs against reliable plant or published reference data.
- Extend the optimization to additional process and utility constraints.

