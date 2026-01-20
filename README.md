# MACRO Energy – Air Pollution Modeling Examples

This repository contains a set of modified assets and example systems based on the MACRO energy systems modeling framework, developed to explore air pollution impacts across different generation technologies and regions.

The goal of this work is to test and validate how changes in system structure, fuel mix, and regional assumptions propagate through emissions and pollution-related outputs.
Eventually, the goal is also to scale it to the Net Zero China project, whichis in progress in some of the example systems. 

The source is the MacroEnergy.jl repository.

## Repository Structure

- `assets/`  
  Contains modified asset definitions used in the MACRO framework, including generation technologies and associated parameters relevant for emissions and pollution analysis.

- `aluminum_eastern_us_three_zones/`  
  Example system configuration modeling aluminum production across three Eastern U.S. zones, used to test regional energy demand and emissions interactions.

- `eastern_us_three_zones_with_cement_.../`  
  Extended system configuration incorporating cement production to evaluate cross-sector impacts on energy use and pollution outcomes.

- `pollution_coal_power_three_zones_electricity/`  
  Example system isolating coal-based electricity generation to study pollution outputs under different regional assumptions.

- `pollution_naturalgas_power_three_zones_electricity/`  
  Natural gas electricity system used for comparative emissions and pollution analysis.

- `pollution_thermal_power_three_zones_electricity/`  
  Thermal power configuration for testing pollution sensitivity across generation technologies.

## Purpose and Approach

These examples are designed as controlled test cases rather than full-scale production runs. Each system:
- Uses simplified or representative regional assumptions
- Is structured to isolate specific drivers of pollution outcomes
- Supports reproducible experimentation and comparison across technologies

The emphasis is on **model structure, data organization, and interpretability**, rather than on proprietary inputs or finalized results.

## Notes on Data and Confidentiality

- All configurations use modified, simplified, or illustrative inputs
- This repository is intended to demonstrate modeling logic and system design
- It does not contain proprietary datasets or production forecasts

## Tools and Methods

- Structured asset definitions
- Scenario-based analysis across regions and technologies

