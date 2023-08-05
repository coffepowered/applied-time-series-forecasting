Available tags:
- Document mode: `slide`, `paper`, `book`, `article`
- Document type: `research`, `application`

Ideas: 
- feed this repo to an LLM to enable search and summarization

# Techniques and modelling
* Modeling: from basic to advanced concepts
    - [Non-Stationarity in Time-Series Analysis: Modeling Stochastic and Deterministic Trends](https://psyarxiv.com/z7ja2/): a didactic paper on how to deal with time series non-stationarity (and on the consequences of ignoring it)
    - [Principles and Algorithms for Forecasting Groups of Time Series: Locality and Globality](https://arxiv.org/abs/2008.00444)
* Cross-validation
    - Experiments on cross-validation ([Samuele Mazzanti](https://towardsdatascience.com/12-ways-to-test-your-forecasts-like-a-pro-a783016c2515), inspired by [Victor Cerqueira et al](https://arxiv.org/abs/1905.11744))
* Feature-based approaches
    - `paper` [Characteristic-based clustering for time series](https://robjhyndman.com/publications/ts-clustering/index.html). Using feature-based approaches to cluster time series greatly reduces the dimensionality of your problem
    - `slide` Meta-learning on how to forecast time series. [FFORMS: what type of models are most suitable for a given time serie](https://robjhyndman.com/papers/fforms.pdf)?
* Metrics
    - `paper` Forecast Evaluation for Data Scientists: Common Pitfalls and Best Practices. [Hewamalage, Ackermann, Bergmeir](https://arxiv.org/abs/2203.10716)
# Applications

## Retail forecasting
- `slide` [Retail sales forecasting at Walmart](https://forecasters.org/wp-content/uploads/gravity_forms/7-c6dd08fee7f0065037affb5b74fec20a/2017/08/Seaman_ISF-2017.pdf) (Seaman). Predict for what? Addresses replenishment and pricing issues
- `paper` [Forecasting with trees](https://assets.amazon.science/17/31/0d99831d4add92e711a56abc75f8/forecasting-with-trees.pdf): why tree-based methods achieved excellent results in the M5 competitions? What are the directions to improve even further?

## Others
- `paper` [Empirically validated probabilistic forecasts of energy technology costs](https://www.sciencedirect.com/science/article/pii/S254243512200410X). How to estimate stuff in a regime of technological uncertainty (due to [learning effects](https://en.wikipedia.org/wiki/Experience_curve_effects))? 

# People and thoughts
- [Sarem Seitz](https://www.sarem-seitz.com/). Featured: [when point forecasts fail]([https://www.sarem-seitz.com/](https://www.sarem-seitz.com/when-point-forecasts-are-completely-useless/#introduction)https://www.sarem-seitz.com/when-point-forecasts-are-completely-useless/#introduction), [autoregressive random forests](https://www.sarem-seitz.com/forecasting-with-decision-trees-and-random-forests/#introduction), [on probabilistic forecasts](https://www.sarem-seitz.com/why-i-prefer-probabilistic-forecasts-hitting-time-probabilities/#executive-summary-by-chatgpt)
- Marco Cerliani. Featured: [forecasting with trees (hybrid modelling)](https://towardsdatascience.com/forecasting-with-trees-hybrid-modeling-for-time-series-58590a113178)


# Waitlist
1. Monash Time Series Forecasting Archive (arxiv)
2. Modern strategies to time series regression ([arxiv](https://arxiv.org/abs/2010.15997))
3. Forecasting for social good (arxiv)
4. FRANS automatic feature extraction via CNN ([arxiv](https://arxiv.org/abs/2209.07018))
5. "Our simplified HINT approach shifts away from multivariate inputs, leading to a 13% accuracy increase over existing solutions (such as MinTrace, PERMBU, HierE2E) across four hierarchical datasets" [arxiv](https://arxiv.org/abs/2305.07089), [nixtla tutorial](https://nixtla.github.io/neuralforecast/examples/hierarchicalnetworks.html)


