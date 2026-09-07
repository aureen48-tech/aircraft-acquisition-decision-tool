# Aircraft Acquisition Decision Tool

## A Python-Based Framework for Airline Fleet Investment Analysis

An independent aerospace engineering and data analytics project developing a Python-based decision-support tool for evaluating aircraft acquisition decisions from both operational and financial perspectives.

## Project Overview

Aircraft acquisition is a major strategic decision for airlines, requiring consideration of acquisition cost, operating economics, revenue generation, financial return and operational suitability.

This project develops a simplified Python-based framework to compare three narrow-body aircraft:

- Airbus A320neo
- Boeing 737 MAX 8
- Airbus A321neo

The objective is to investigate which aircraft provides the strongest combination of financial return, operating economics and strategic performance under different market conditions.

## Methodology

The model evaluates aircraft using:

- Operating cost analysis
- Revenue and profitability modelling
- Cost per Available Seat Kilometre (CASK)
- Revenue per Available Seat Kilometre (RASK)
- Break-even load factor
- Break-even ticket fare
- Net Present Value (NPV)
- Internal Rate of Return (IRR)
- Payback period
- Sensitivity analysis
- Scenario analysis
- Multi-criteria decision analysis

## Base-Case Scenario

The model considers a hypothetical airline operating a representative 3,000 km medium-haul route over a 15-year investment period.

Key assumptions include:

| Parameter | Value |
|---|---:|
| Route distance | 3,000 km |
| Flight time | 4 hours |
| Annual utilisation | 3,500 flight hours |
| Load factor | 82% |
| Average ticket price | USD 180 |
| Fuel price | USD 0.85/kg |
| Analysis period | 15 years |
| Discount rate | 10% |
| Residual value | 20% of purchase price |

## Results

Under the base-case assumptions, all three aircraft generated positive operating profits and positive NPVs.

| Aircraft | Annual Operating Profit | NPV | IRR | Payback |
|---|---:|---:|---:|---:|
| A320neo | $10.32M | $26.12M | 17.38% | 5.33 years |
| 737 MAX 8 | $9.43M | $22.25M | 16.68% | 5.51 years |
| A321neo | $13.21M | $41.41M | 20.21% | 4.70 years |

The Airbus A321neo achieved the strongest overall financial performance under the assumptions used in the model.

## Sensitivity Analysis

The model investigates the effect of changes in:

- Fuel price
- Passenger load factor
- Average ticket price
- Annual aircraft utilisation

Three operating scenarios are also considered:

1. Conservative
2. Base case
3. High growth

## Multi-Criteria Decision Model

Aircraft selection is not based solely on financial return. A weighted decision model incorporates:

- NPV — 30%
- CASK — 20%
- Break-even load factor — 15%
- Purchase price — 10%
- Fuel efficiency — 10%
- Capacity — 10%
- Operational flexibility — 5%

## Key Finding

The analysis demonstrates that the aircraft with the lowest acquisition cost is not necessarily the strongest long-term investment.

Under the assumptions used in this study, the Airbus A321neo provided the strongest combination of financial performance and operational potential.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Financial modelling
- Data analysis
- Sensitivity analysis

## Repository Contents

- `Aircraft_Acquisition_Decision_Tool.ipynb` — Main Python analysis
- `results/` — Generated visualisations
- `report/` — Full research report
- `requirements.txt` — Python dependencies

## Research Report

The full project report is available on ResearchGate:

[Aircraft Acquisition Decision Tool – ResearchGate]( 10.13140/RG.2.2.22095.85924)

## Disclaimer

This is an independent analytical project based on a hypothetical airline operating scenario. The numerical assumptions and results are illustrative and intended to demonstrate a decision-support methodology rather than provide a commercial aircraft procurement recommendation.

## Author

**Aureen Afzal**

MSc Engineering with Innovation & Entrepreneurship  
University College London

BEng Aerospace Engineering  
City St George's, University of London
