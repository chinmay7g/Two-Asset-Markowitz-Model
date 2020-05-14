# Two-Asset-Markowitz-Model

![portfolio](https://user-images.githubusercontent.com/55191934/81898924-4799f200-95d7-11ea-823e-f36cd5d1252a.PNG)

The main basis of this entire model is based on Sharpe ratio.

Sharpe ratio : It gives the model's performance with a risk-adjusted factor.
Greater the sharpe ratio, highly attractive is the investment avenue. It basically explains the risk-reward phenomenon.
Assumes that data is normally distributed.

Sharpe Ratio = (Return - Risk-Free-Return)/(Std. Deviation)

The Markowitz thery or the Modern Portfolio Theory states that adding two low-correlated assets to portfolio for diversification
reduces the risk without sacrificing returns.

For this given project, which compares the Vangaurd stock vs the US. Govt.bond which have a low correlation,
in a 50-50 allocation yield a Sharpe ratio of 0.338, highest amongst others.

Key learnings:

1. Importance of Sharpe ratio and Sortino ratio too.

2. Essence of the Modern Portflio Theory.

3. Variance of the two-assets is given by formula:

VAR = (allocation_1%)^2*(variance(asset_1)) + (allocation_2%)^2*(variance(asset_2)) + 2*(allocation_1)* (allocation_2)* (covariance of asset1 and asset2)
