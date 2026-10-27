# Design and Rating of a Shell-and-Tube Heat Exchanger
### Debutanizer Condenser Debottlenecking Case Study using DWSIM

Project report, Department of Chemical Engineering, Jadavpur University (October 2026).

## Overview
Design and rating of a single-shell, two-tube-pass exchanger that condenses
hydrocarbon vapour (75 °C, 8 bar, 15,000 kg/h) using 85,000 kg/h of cooling
water at 30 °C. The model was built in DWSIM (*Shell and Tubes Exchanger
Rating*) and checked against independent hand calculations.

## Key Results
| Quantity | Value |
|---|---|
| Heat duty | 1,249.2 kW |
| Overall coefficient (fouled) | 256.5 W/m²·K |
| LMTD | 31.33 °C |
| Required area | 155.4 m² |
| Installed area | 160.6 m² |
| Design margin | 3.3 % |
| Controlling resistance | Shell-side film (~78 %) |
| Area needed at +15 % flow | ~184 m² (about 14 % more than installed) |

## Geometry
Shell ID 600 mm · 450 tubes (19.05 mm OD, 6 m) · 2 tube passes ·
25 mm triangular pitch · single segmental baffles (450 mm spacing, 25 % cut).

## What the Report Covers
1. Process simulation in DWSIM and validation against a reference case
2. Heat duty, LMTD and required area
3. Mechanical and shell-side geometry
4. Tube-side velocity, film coefficient and pressure drop
5. Overall coefficient and fouling analysis
6. Debottlenecking at +15 % hydrocarbon flow

## Repository Contents
- `report/` – full report (PDF and DOCX)
- `simulation/` – DWSIM flowsheet file
- `images/` – figures used in the report

## How to Reproduce
1. Install [DWSIM](https://dwsim.org).
2. Open `simulation/heat_exchanger.dwxmz`.
3. Run the flowsheet and compare with Table 3 of the report.

## Tools
DWSIM · Hand calculations (Kern/Bell-Delaware-style correlations,
Dittus–Boelter, Colebrook)

## Author
**Subhamoy Panja**, B.E. Chemical Engineering, Jadavpur University

## License
Released under CC BY 4.0.
