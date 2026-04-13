# Aviation Accident Analysis

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
1. Cleaned dataset exported from the cleaning notebook for reuse in analysis.
2. Visual and statistical comparisons for small and large aircraft groups.
3. Evidence-based make/model recommendations.

## Status
Initial project framing completed. Cleaning and analysis results will be added as notebook work is finalized.

