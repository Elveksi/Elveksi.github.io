## How does this work?

We gathered data from Finnish Meteorological institue (Ilmantieteenlaitos) and all the data is from certain obeservation station, which is Helsinki-Vantaa airport. Data is from the beginning of 1960 to -. We used SARIMA machine learning model to predict snow depth in December. SARIMA name comes from S=seasonal, AR=autoregressive, I = intergrated and MA=moving average. Basically, model learns seasonality of snow depth from previous years and use that to predict snow depth in the future. We provide prediction for Christmas eve and confidence intervals for the snow depth. 

---

### Results and interpretation

From the graph we can see that our model takes seasonality account in a lovely way and we seem to have exactly 16.4cm snow depth during Christmas eve. 95% confidence interavals...

```{image} ../images/fun-fish.png
:alt: fishy
:class: bg-primary mb-1
:width: 200px
:align: center
```
