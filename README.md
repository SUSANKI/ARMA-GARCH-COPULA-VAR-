# ARMA-GARCH-COPULA-VAR-
Method of calculating VaR ( Value at risk) using ARMA-GJR_GARCH and COPULA method

Value at Risk (VaR) is one of the most widely used risk measure in risk management. It is defined as the worst loss to be expected of a portfolio over a given time horizon at a given confidence level. We estimate portfolio VaR using an approach combin-
ing Copula functions, Extreme Value Theory (EVT) and GARCH models. We apply this approach to a portfolio consisting of stock indices from CTG, MSN, VIC, VNM (Vietnam). To estimate the VaR of this portfolio, we first use an asymmetric GARCH model and an EVT method to model the marginal distributions of each log returns series and then use Copula functions (Gaussian, Student’s t, Clayton, Gumbel and Frank) to link the marginal distributions together into a multivariate distribution. We then use Monte Carlo Simulation
(MCS) approach to find estimates of the portfolio VaR. To check the goodness of fit of the approach we use Backtesting methods. From the results, we conclude that, in general the GARCH-EVT-Copula approach performs well and specifically the GARCH-EVT-Student’s t Copula outperforms all other GARCH-EVT-Copulas and traditional methods such as Historical Simulation (HS) and Variance Covariance (VC).

Keywords: Value at Risk (VaR), Copula, GARCH, Extreme Value Theory (EVT), Backtesting.
