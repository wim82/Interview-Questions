# Trading ING stocks

Imagine that you are trading ING stocks and you would like to create a small program to maximize your profit.
Suppose you could access yesterday's stock prices as an array, where:

* The indices are the time in minutes past trade opening time, which was 09:00;
* The values are the price in EUR of ING stock at that time;

So if the stock cost 16 EUR at 10:30, `stockPriceYesterday[90] = 16`.
Write an efficient method that takes stockPriceYesterday and **returns the best profit I could have made from 1 purchase and 1 sale of 1 ING stock yesterday**.

For example:

```
    int[] stockPriceYesterday = new int[] {10, 7, 5, 8, 11, 9};

    getMaxProfit(stockPriceYesterday);
    //returns 6 (buying for 5 EUR and selling for 11 EUR)
```

No "shorting" - you must buy before you sell. You may not buy and sell in the same time step (at least 1 minute must pass).