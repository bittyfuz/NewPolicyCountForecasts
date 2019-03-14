# NewPolicyCountForecasts

In this repository are the codes I've written in R Markdown to fit for smoothing parameters that are used to forecast time series data.

The data, which is public, is the new policy count time series from Citizens Property Insurance, which is used in their annual budget.

The models increase in complexity: [npc_linreg](http://htmlpreview.github.io/?https://github.com/bittyfuz/NewPolicyCountForecasts/blob/master/npc_linreg.html) is the most basic model, which I used to get familiar with programming in Stan.
[npc_AAA](http://htmlpreview.github.io/?https://github.com/bittyfuz/NewPolicyCountForecasts/blob/master/npc_AAA.html) is the simplest time series model, and [npc_MMM](http://htmlpreview.github.io/?https://github.com/bittyfuz/NewPolicyCountForecasts/blob/master/npc_MMM_demo.html) is a more complex model which will be used in the [forecast code](http://htmlpreview.github.io/?https://github.com/bittyfuz/NewPolicyCountForecasts/blob/master/npc_MMM_forecast_demo.html).
