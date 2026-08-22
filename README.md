# ETABS RC Building Seismic Modelling

Structural modelling and nonlinear seismic analysis of a 14-story 
RC frame building in ETABS, covering model setup, linear static 
analysis, nonlinear hinge assignment, and pushover analysis.

## Overview

- Building: 14-story RC frame, Seismic Zone 2B, Soil Profile SB
- Framing: Intermediate Moment Resisting Frame (IMRF)
- Codes: UBC-97, ACI-318-11, ASCE 7-22, FEMA-356, ATC-40
- Software: ETABS

## Workflow

1. **Model setup** - geometry, sections, materials
2. **Linear static analysis** - load patterns, modal verification
3. **Nonlinear hinge modelling** - auto hinges (P-M2-M3 columns, 
   M3 beams), verified against manual moment calculation
4. **Pushover analysis** - target displacement per FEMA-356, 
   evaluated at SLE/DBE/MCE hazard levels
5. **Modelling iterations** - multiple section/reinforcement 
   configurations checked against FEMA hinge performance criteria
6. **Analysis output** - storey shear, drift, displacement, 
   overturning moment, hinge formation

## Purpose

Demonstrates practical ETABS workflow for nonlinear seismic 
modelling and analysis, from model setup through pushover 
interpretation.

## Note

Model files (.EDB) are excluded from this repo. See `.gitignore`.