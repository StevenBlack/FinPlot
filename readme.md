# 📈 FinPlot

A Mathematica function to display and manipulate financial DateListPlots in a generic and flexible way.

```
FinPlot[
  FinancialData["XAU/USD", {1960 - 01 - 01}]
  ,"Gold price (USD)"
  ,<|
    filling -> Axis
    ,imagesize -> 1000
    ,export -> True
    ,origindate -> {1960-01-01}
  |>
]
```


![](Gold-price-USD.jpg)
