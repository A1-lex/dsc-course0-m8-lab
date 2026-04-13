# Aviation Accidents Analysis

## Project Overview
This project analyzes aviation accident data to recommend safer airplane makes and models for an airline/insurer client.

The analysis focuses on aircraft with:
1. Lower likelihood of fatal or serious passenger injury.
2. Lower likelihood of total aircraft destruction.

## Scope
1. Dataset window used for recommendations: 1983 onward.
2. Aircraft scope: professional airplane builds (non-amateur).
3. Separate recommendations for:
   - Small aircraft (estimated passengers < 20)
   - Large aircraft (estimated passengers >= 20)

## Repository Contents
1. Cleaning notebook: [Aviation_Accidents_Cleaning.ipynb](Aviation_Accidents_Cleaning.ipynb)
2. Analysis notebook: [Aviation_Accidents_Data_Analysis.ipynb](Aviation_Accidents_Data_Analysis.ipynb)
3. Dataset folder: [data](data)

## Method Summary
1. Clean and standardize key fields (date, make/model, injury columns, damage).
2. Build derived safety metrics, including injury-rate and destruction indicators.
3. Compare makes/models with minimum sample-size checks for robust conclusions.
4. Evaluate at least two additional factors affecting injury and damage outcomes.

## Outputs
1. Cleaned dataset exported from the cleaning notebook for reuse in analysis: [data/aviation_accidents_cleaned.csv](data/aviation_accidents_cleaned.csv).
2. Visual and statistical comparisons for small and large aircraft groups.
3. Evidence-based make/model recommendations.

## Run Order
1. Run [Aviation_Accidents_Cleaning.ipynb](Aviation_Accidents_Cleaning.ipynb) to generate the cleaned dataset.
2. Run [Aviation_Accidents_Data_Analysis.ipynb](Aviation_Accidents_Data_Analysis.ipynb) to reproduce figures, summaries, and recommendations.

## Key Findings
1. Small-aircraft recommendations are led by Cessna, Beechcraft, Piper, Maule, Aviat, and Aeronca examples with lower injury and destruction rates.
2. Large-aircraft recommendations are led by Boeing and Airbus models, with Boeing 737 and Airbus A320 family examples performing well in the analysis.
3. Weather condition and flight phase both matter: IMC and maneuvering/climb conditions show higher injury fractions, while VMC and landing are safer.

## Status
Project framing, cleaning, EDA, and final recommendations are complete.

