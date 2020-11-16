# Daily Algoritm Trader
This project is to trade stock based on individualized rolling averages. Rolling averages are found by averaging a given range of numbers based on time. This often smooths out curves and can highlight a long term period of growth or decline. Some of the more often used rolling averages are `200 days vs 50 days` & `30 days vs 5 days`. The function I built out allows you to input a set number of shares and the two rolling average ranges. To trade, the function will sell off of the stock when there is either a `Golden or Death Cross` I say either, because it can be quickly changed by flipping the >< signs in the function.

## Notebooks
#### algorithm.ipynb
This notebooks is the function that sells and buys stocks, with a set number of shares. Once it reaches the last date, it will display the difference value the initial number of shares would have if they were left alone and the value of algorithm gained or lost over time. It will also showcase the gains and losses over time for both as time went on. This provides a more detailed graph of the change in value compared to each other.

#### rolling-averages.ipynb
This notebook is to showcase the rolling averages over time.
