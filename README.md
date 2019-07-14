# ConventionPrediction
Here, I use a bayesian multilevel multinomial model to predict the first ballot results at the  2018 DFL (Democratic) State Convention,  with data aggregated to the Party Unit level (ex: State Senate district) to guarantee anonymity. While using aggregated data obviously isn't ideal, this sort of strategy shows a lot of promise, especially if individual level predictors could be harnessed as another level of the multilevel model. As it stands, this is mostly a proof of concept for bayesian multilevel models in this context. To use something like this in practice, one could use prior predictive simulation to game out the convention under various assumptions, or condition on the first ballot data and use it to analyze trends in support and predict subsequent ballots as your floor team collects further data.

A version of this write up (with plots) can be found on [my website](https://andytimm.github.io/2019/07/13/convention-model.html).

This was my final project for my Bayesian Statistics course at NYU Steinhardt in spring 2019. 
