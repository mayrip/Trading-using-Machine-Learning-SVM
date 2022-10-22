# Trading-using-Machine-Learning-SVM
This repo gives an introduction to trading using support vector machines

Support Vector Machine (classification) can be used for trading using multiple decision factors. It is to be noted that the data for training as well as testing should be large enough and decision factors change over time with changes in market regimes. For real life usage, its recommended to train the data till n-1th time stamp. It is also to be noted that in this notebook we have not taken into account trading cost which can be a large amount. We also assume no-slipages and that the user would get exact trading price. Even though these factors aren't taken into account the backtested result are satisfactory. An interesting thing to watch would be a result weekly training and testing that is taking one trading decision instead of taking a daily decision.

This notebook takes Reliance Industries Ltd. as our stock for trading.
