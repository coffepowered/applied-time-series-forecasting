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
- `book` [Demand forecasting best practices](https://www.manning.com/books/demand-forecasting-best-practices) (N. Vandeput)
- `slide` [Retail sales forecasting at Walmart](https://forecasters.org/wp-content/uploads/gravity_forms/7-c6dd08fee7f0065037affb5b74fec20a/2017/08/Seaman_ISF-2017.pdf) (Seaman). Predict for what? Addresses replenishment and pricing issues
- `paper` [Forecasting with trees](https://assets.amazon.science/17/31/0d99831d4add92e711a56abc75f8/forecasting-with-trees.pdf): why tree-based methods achieved excellent results in the M5 competitions? What are the directions to improve even further?
- `paper` [Learnings from (various) Kaggle forecasting competitions](https://arxiv.org/ftp/arxiv/papers/2009/2009.07701.pdf) (Bojer and Meldgaard)


## Others
- `paper` [Empirically validated probabilistic forecasts of energy technology costs](https://www.sciencedirect.com/science/article/pii/S254243512200410X). How to estimate stuff in a regime of technological uncertainty (due to [learning effects](https://en.wikipedia.org/wiki/Experience_curve_effects))? 

# People, thoughts and organizational aspects
- [Sarem Seitz](https://www.sarem-seitz.com/). Featured: [when point forecasts fail]([https://www.sarem-seitz.com/](https://www.sarem-seitz.com/when-point-forecasts-are-completely-useless/#introduction)https://www.sarem-seitz.com/when-point-forecasts-are-completely-useless/#introduction), [autoregressive random forests](https://www.sarem-seitz.com/forecasting-with-decision-trees-and-random-forests/#introduction), [on probabilistic forecasts](https://www.sarem-seitz.com/why-i-prefer-probabilistic-forecasts-hitting-time-probabilities/#executive-summary-by-chatgpt)
- Marco Cerliani. Featured: [forecasting with trees (hybrid modelling)](https://towardsdatascience.com/forecasting-with-trees-hybrid-modeling-for-time-series-58590a113178)
- `paper` `retail` [Managing Functional Biases in Organizational Forecasts: A Case Study of Consensus Forecasting in Supply Chain Planning](https://www.researchgate.net/publication/227633773_Managing_Functional_Biases_in_Organizational_Forecasts_A_Case_Study_of_Consensus_Forecasting_in_Supply_Chain_Planning)

# Practical tips 

This section is not strictly related to time series but collects useful tips in Python, Model deployment and specific libraries
- [Tricking data science: time series](https://bextuychiev.github.io/tricking-data-science/book/machine_learning/time_series.html)

# Waitlist
1. Monash Time Series Forecasting Archive (arxiv)
2. Modern strategies to time series regression ([arxiv](https://arxiv.org/abs/2010.15997))
3. Forecasting for social good (arxiv)
4. FRANS automatic feature extraction via CNN ([arxiv](https://arxiv.org/abs/2209.07018))
5. "Our simplified HINT approach shifts away from multivariate inputs, leading to a 13% accuracy increase over existing solutions (such as MinTrace, PERMBU, HierE2E) across four hierarchical datasets" [arxiv](https://arxiv.org/abs/2305.07089), [nixtla tutorial](https://nixtla.github.io/neuralforecast/examples/hierarchicalnetworks.html)
6. How to win a forecasting competition? [Youtube video](https://www.youtube.com/watch?v=kkpFZA1sVSA)
7. `paper` [Good and bad judgment in forecasting, lessons from four companies](https://forecasters.org/wp-content/uploads/Good-and-Bad-Judgment-in-Forecasting_Issue8.pdf)
8. `paper` [Can we obtain valid benchmarks from published surveys of forecast accuracy? (Kolassa)](https://forecasters.org/wp-content/uploads/Valid-Benchmarks-from-Published-Surveys-of-Forecast-Accuracy_Foresight11.pdf)
9. `book` Supply Chain Strategy and Financial Metrics: The Supply Chain Triangle Of Service, Cost And Cash [on amazon](https://www.amazon.com/Supply-Chain-Strategy-Financial-Metrics/dp/0749482575)
10. `book` The Business Forecasting Deal: Exposing Myths, Eliminating Bad Practices, Providing Practical Solutions [on Amazon](https://www.amazon.com/Business-Forecasting-Deal-Eliminating-Practices-ebook/dp/B003NE61MQ)
11. 
