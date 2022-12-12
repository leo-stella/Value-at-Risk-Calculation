# Value-at-Risk-Calculation

Calculate financial value at risk using python

## What is Value at Risk?

Value at Risk or VaR is a statistical measure of how much a Trade or Portfolio might lose over a given
period of time, given a set of historical or simulated Profit & Loss numbers.

For example, given a set of Profit & Loss values, if the 93% worst P&L was a $10m loss, 

there is a (1-0.93) 7% chance that the portfolio could lose $10m on a given day. 

97% is known as the confidence level. 

I will use Historical Value method to calculate VaR here. (Other methods : variance-covariance)

The first part is calculating VaR for a single trade. The user will insert the trade number and confidence level

and the resulting VaR will be shown. 

A graph is shown too for easy understanding. 

The second part is calculating the VaR for a whole portfolio (all the trades in the csv file). 

The user input will be confidence level only. 

Notice that portfolio VaR is not simply adding all trade's VaR, but adding P&L value of each day first, then performing the VaR calculation. 

Feel free to comment if you have easier, more efficinet ways of calculating VaR. 
