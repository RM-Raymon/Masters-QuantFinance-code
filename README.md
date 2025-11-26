This folder contains ipnyb files that are answers to the QF620 module: Stochastic modelling and calculus

The project involves application of various stochastic models to cover key topics in the quantitative finance industry, such as the following

1) Derivation of **closed-form valuation formulas** for vanilla and exotic payoffs
2) **Fitting of Implied Volatility quoting models** to the implied volatility smile on the market
3) **Static replication** of exotic payoffs
4) **Dynamic hedging** of an options position according to the Black-Scholes Dynamic Hedging theory

Several models are included in the project, each with their own use.

### Valuation models

| Model                   | Description                                        |
|-------------------------|----------------------------------------------------|
| Bachelier's model       | Normal random walk                                 |
| Black-Scholes model     | Lognormal random walk                              |
| Black-76 model          | Lognormal random walk using the forward price      |
| Displaced-diffusion     | Weighted average of normal and lognormal random    |


### IV quoting models

| Model                   | Description                                                                                 |
|-------------------------|---------------------------------------------------------------------------------------------|
| Displaced-Diffusion model | Backing out the implied volatility from options priced with the displaced-diffusion formula |
| SABR model              | Purpose-built model to directly quote implied volatilities based on hyperparameters and market inputs |


### Other models

| Model                               | Description                                                                                  |
|-------------------------------------|----------------------------------------------------------------------------------------------|
| Carr–Madan static replication formula | Model-free valuation of option payoffs                                                       |
| Black–Scholes Dynamic Hedging         | The idea that an options position can be hedged using a portfolio of the underlying and bonds |
