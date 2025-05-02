# 📈 FinPlot

A Mathematica function to display and manipulate financial DateListPlots in a generic and flexible way.

```
xauusd =FinancialData["XAU/USD",{1960-01-01}];
xauusdplot=FinPlot[
    {xauusd, xauusd - 800, (xauusd *0.75) - 380}
    ,"Gold price (USD)"
    ,<|
        imagesize->1000
        , normalize->True
    |>
];
xauusdplot
```


![](Gold-price-USD.jpg)
