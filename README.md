# Simulate-March-Madness-2023
Simulate March Madness 2023
Simulate March Madness 2023

## Background

 - [Strategy heatmaps for all submissions](https://www.kaggle.com/c/march-machine-learning-mania-2017/discussion/30333) (2017)
 - [March ML Mania 2023 Heatmap of Submissions](https://www.kaggle.com/code/jtrotman/march-ml-mania-2023-heatmap-of-submissions) (2023)
 

Welcome to this Jupyter notebook where we will simulate the 2023 March Madness basketball tournaments using a submission for the Kaggle competition. The above links show how we can convert a competition submission into a grid, which makes it very easy to read off probabilities for games with which we can simulate the whole tournament!

We will be using the median of the experts' submissions as our prediction model, but any other submission file will do. In addition, we will compare our simulated tournament results to 538's own forecast, a popular sports prediction website known for their statistical models and accurate forecasts.

Using the `TournamentSimulator` class below we can:

- Generate a bracket (using 0.5 for match predictions instead of a random in *0..1*)
- Simulate tournament from start
- Simulate tournament from a later stage using known results and the pre-tournament submission
- Compare distributions to fivethirtyeight *rd1_win*, *rd2_win*, etc...

Let's get started and see how well we can predict the outcome of the March Madness tournament!

## Contents

<div id="contents_list"></div>
