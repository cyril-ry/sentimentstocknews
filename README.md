# Can we earn buying stocks based on sentiment news analysis? (Answer: Nearly)
## Description
Predicting how much this or that paper will cost in advance is impossible, since the cost depends on constantly incoming information.
However, we can try to identify certain trends related to the public perception of the company (this is close to Behavioral Finance). And on the basis of them to make our bets (the price of the stock will rise in the near future). Trends are just as stable in time. And we do not analyze the price of the stock in time, but the general opinion of the company in time.
We, with api limitations, will watch the news for the first 15 days, evaluate how positive they are, assume that we invest if the news is positive, short it, if the news is negative, and then see how the market plays for the remaining 15 days.

## Paper plan is following
### Gathering news API
- [x] API for 15 days
- [ ] API for more days, need new news source
### Gathering stock API
- [x] Stock for last 15 days
- [ ] API for more days, need new stock source
### Assesing sentiment for stock using VADER (we take here median of the day)
- [x] VADER sentiment with median
### Finding stocks
- [x] looked at some stocks
- [ ] need more sample of stocks to assess
### Backtesting results
- [x] need more sample of stocks to assess
- [ ] need proper backtesting
### Results
- [x] some results are suggesting that strategy works
- [ ] need more sample for robust results
