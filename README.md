In today’s interconnected and volatile financial markets, the capacity to anticipate and withstand large, adverse
price movements is crucial not only for institutional survival but also for systemic financial
stability. Value at Risk (VaR) has emerged as the industry standard for measuring and
controlling market risk. 
However, traditional VaR approaches, which are based on simple historical simulation or parametric models assuming normality, have notable limitations. Financial asset
returns rarely follow a normal distribution. Markets regularly display features such as
volatility clustering (periods of high and low volatility), leptokurtosis (fat tails and sharp
peaks, leading to frequent large moves), and nonlinear or asymmetric dependence among
assets. These complexities mean that standard VaR often underestimates the frequency
and severity of tail events, the very losses that institutions most need to guard against.
The purpose of this project is to create a robust VaR estimation framework for a
portfolio of stocks by:
• Incorporating volatility dynamics via GARCH-ARMA models.
• Modeling tail risks with the Generalized Pareto Distribution (GPD).
• Capturing center behavior with Kernel Density Estimation (KDE).
• Handling joint (multivariate) dependence with Copulas.
