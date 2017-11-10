# FX_hedge_scenarios

This notebook reproduces an interesting case in "Advanced International Corp Finance" @ Columbia Business School, taught by Professor Bob Hodrick.

Namely, take a company "Y", whose revenues are in USD, while variable costs are in a foreign currency (say EUR). 
We assume sale numbers and the currency are random variables, lognormally distributed.

We then run simple MonteCarlo simulation to check the distribution of income if the company 
1. does not hedge its FX exposure
2. hedges with a forward whose notional equals the expected sales volumes (this can thus result in over or underhedges)
3. hedges with a vanilla option.
4. to_do: hedges with other option strategies.


