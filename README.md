# Flood Risk Monte Carlo Simulation (South Africa)

## Project Overview
This project models the financial impact of flood events using Monte Carlo simulation.  
The simulation generates 10,000 possible years of flood outcomes to estimate potential insurance losses.

## Methodology
The model assumes:
- Flood probability: 30% per year
- Three flood severity levels: Minor, Moderate, Severe
- Randomized loss ranges for each severity level

Monte Carlo simulation is used to estimate the distribution of possible annual losses.

## Risk Metrics

Expected Annual Loss (EAL): ~R5.94 million  
95% Value at Risk (VaR): ~R31.78 million  
Tail Value at Risk (TVaR): ~R69.37 million  

## Example Output

![Flood Loss Distribution](flood_loss_distribution.png)

## Tools Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Author
Rotshidzwa Makhari
BSc Mathematics & Statistics Student
