# Option-Smile-Calibration
A repository with a collection of various techniques to calibrate option implied volatility smile

## SABR Model
The first notebook of the collection focuses on the use of the SABR Model to calibrate to market observed implied volatility smile.
As the first notebook of the series, a detailed explanation of the data processing steps is provided. This will be omitted from future notebooks in the series.

A detailed explanation of the SABR Model, along with an analysis of the impact of varying the parameters to the fitted smile is explored.
Readers would be able to appreciate the advantages of the SABR model and understand how the SABR model can be implemented.

## Displaced-Diffusion Model
The second notebook of the collection focuses on the Displaced-diffusion model. This model is more commonly used to fit interest rate options due to its capability to fit options with negative underlying prices, which is the case during the negative interest rate regime during the decade of 'quantitative easing'. We explore a simpler model and analyze its usefulness to fit the equity index option smile.

Due to its simplicity, the Displaced-diffusion model is capable of fitting the slope and the level of the market-observed smile by varying its parameter $\beta$, but is ineffective to fit the curvature of the smile. The verdict of the analysis is that the displaced-diffusion model may not be the most effective for near-dated options with a prominent smile.

## OptionMetrics Tutorial
The third notebook offers a short introduction to OptionMetrics and the SQL script one can use to pull the data required for analysis. This is also an extension of the second notebook, to explore the effectiveness of the Displaced-Diffusion model on a further dated option.
