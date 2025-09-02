# Rate Kinetics of Burning Candle

## Overview
This project is a course assignment for ChE331 (Chemical Engineering) under the guidance of Prof. Raj Ganesh S. Pala. It investigates the rate kinetics of candle burning through experimental analysis. The study models the combustion process of candle wax (approximated as C25H52) and determines its reaction order, dependency on wax concentration or height, and optimal dimensions for longevity.

**Author:** Tushar Verma (221147)  
**Date:** 14th Nov 2024 

## Aim
To analyze and determine the rate kinetics of a burning candle, focusing on the combustion reaction:  
C₂₅H₅₂ + 38O₂ → 25CO₂ + 26H₂O

## Objectives
- Calculate and model the rate expression for candle burning.
- Determine the overall order of reaction for complete combustion.
- Investigate if the burning rate depends on the concentration of candle wax or candle height, and establish any relations.
- Optimize candle dimensions (e.g., height-to-area ratio) to maximize burning duration.

## Materials Required
- 5-6 candles of varying sizes but similar wax volume (or ~400g wax, cotton wick, beakers of different sizes, and a burner if making custom candles).
- Optional: Temperature or thermal sensor to measure flame temperature variations with candle height.

## Procedure
1. Prepare 5-6 candles with different dimensions but constant wax volume.
2. Burn each candle and record conversion (Xa) vs. time at ~8-minute intervals.
3. Approximate conversion as (1 - Xa) ≈ (vol_left / vol_total), or use height ratios since cross-sectional area is constant.
4. Repeat for all candles and note total burn time for each.
5. Analyze data to model kinetics and optimize dimensions.

## Experiments and Observations
Seven experiments were conducted with candles of varying shapes (cylindrical, conical) and dimensions. Data includes height left, conversion (Xa), time, volume converted, and volume left. Graphs of conversion vs. time were plotted for each, showing linear trends with high R² values (e.g., 0.9776 to 0.9972).

### Key Data Summary (from Experiments)
- **Exp 1-3:** Tall cylindrical candles (h_cy=11 cm, dia=1.3 cm) with initial cone section. Burn times ~51-64 minutes, linear conversion rates ~0.014-0.0235/min.
- **Exp 4:** Shorter cylinder (h_cy=8.5 cm, dia=1.5 cm). Burn time ~30 minutes, rate ~0.0332/min. Noted cup melting causing flickering.
- **Exp 5:** Wide cylinder (h_cy=3.5 cm, dia=3 cm). Burn time ~60 minutes (partial), rate ~0.0068/min.
- **Exp 6:** Cylinder (h_cy=3 cm, dia=2.5 cm). Partial data due to cardboard cover catching fire.
- **Exp 7:** Cylinder (h_cy=2.3 cm, dia=2 cm). Burn time ~60 minutes (partial), rate ~0.0048/min.

Raw data is available in attached Excel files: `data.xlsx` and `data(AutoRecovered).xlsx`.

## Analysis and Results
- Conversion (change in volume) is linearly proportional to time, indicating equal volume decrease over equal intervals, independent of candle shape.
- The reaction follows zero-order kinetics (dXa/dt = constant ~0.01), with linear conversion-time curves (R² ≈ 1).
- Burning rate is independent of wax concentration or height; it depends on oxygen availability near the flame.
- A "cup" forms during burning where solid wax melts to liquid, rises via capillary action, vaporizes, and combusts. Cup instability (e.g., leaks) causes uneven burning.
- Radius/height ratio does not affect volume change rate. For optimization, select designs with stable top cups.

## Possible Sources of Errors
- Wind causing uneven flame and cup breakage, increasing combustion rate.
- Limited oxygen in enclosed setups (e.g., beakers), reducing luminosity and rate (seen in Exp 5-7).
- Cardboard containers catching fire, halting data collection (Exp 6).
- Variations in flame width due to oxygen availability from different container dimensions.

## Repository Structure
- `ChE331_exp_proj_221147.pdf`: Full project report with detailed tables, graphs, and analysis.
- `data.xlsx` / `data(AutoRecovered).xlsx`: Raw experimental data in spreadsheet format.

## How to Replicate
1. Prepare candles as described.
2. Burn and record data manually or using sensors.
3. Plot conversion vs. time using tools like Excel or Python (e.g., matplotlib).
4. Fit linear models to confirm zero-order kinetics.

For further details, refer to the attached PDF report.
