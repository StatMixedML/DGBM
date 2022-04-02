# DGBM: Distributional Gradient Boosting Machines
We present a unified probabilistic gradient boosting framework for regression tasks that models and predicts the entire conditional distribution of a univariate response variable as a function of covariates. Our likelihood-based approach allows us to either model all conditional moments of a parametric distribution, or to approximate the conditional cumulative distribution function via Normalizing Flows. As underlying computational backbones, our framework is based on XGBoost and LightGBM. Modelling and predicting the entire conditional distribution greatly enhances existing tree-based gradient boosting implementations, as it allows to create probabilistic forecasts from which prediction intervals and quantiles of interest can be derived. Empirical results show that our framework achieves state-of-the-art forecast accuracy. 

## News
:construction: Repo is under construction

## Reference Paper
März, A. and Kneib, T. (2022) [*"Distributional Gradient Boosting Machines"*]().
