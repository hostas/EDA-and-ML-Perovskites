# Feature engineering

It is important to check how are our features correlated. This information can help in feature engineering and reduction. Having features which are lineary dependent on each other probably won't improve our model. We should strive to provide nonlinear features which bring new information about our data.

![Abstract](https://github.com/jiri-hostas/EDA-and-ML-for-Perovskites/blob/master/Graphics/Correlation-of-descriptors.png)

**Figure 1**: Clearly columns A2/B2 and A2*B2 do not add new information and are mostly empty, so they can be discarded. This can be explained by the fact that we don't have many alloy double perovskites in our dataset and part of this information is contained already at the A2 and B2 elemental features.
