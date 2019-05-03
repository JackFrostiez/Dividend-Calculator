# Dividend-Calculator

A small dividend calculator in Python because I like doing stocks so why not?

***Note: Only works with manual inputs as of now***

## What's the point of this?
Someone may want to just keep reinvesting the profits that they earned from dividends into getting more shares, therefore increasing future profits. If you're that someone, then this might help you out!

## Ok, so how does it work?
You have to input five things however you want:
* Price    - _The current average price of the stock_
* Shares   - _The amount of shares you own for this stock_
* Dividend - _The dividend amount you earn per share_
* Quarters - _The amount of quarters the stock pays in every year_
* MaxYears - _The amount of years to project calculations_

### __Let's say for instance that:__  
* We own __90 shares__ of __F ( Ford )__
* __9.25 per share__ as of 4/8/2019  
* __F ( Ford )__ pays dividends in __4 quarters__ every year
* We want to project __10 years__ worth of dividend investment calculations  
    ```python
    Price = 9.25
    Shares = 90  
    Dividend = 0.15  
    Quarters = 4
    MaxYears = 10
    ```

After inputting the values, there will be an output result of dividend calculations.

__Here's one of the years from the output:__

![alt text](https://github.com/JackFrostiez/Dividend-Calculator/blob/master/Div_Calculator/Example1.png "Yearly Example Output")

__Let's go through the meaning of the output:__
* In each year are 4 Quarters showing the __Annual Income__, and __Annual Shares__
* In each quarter we show the four keywords:  
    * __Profit__
    * __P/P__
    * __ReInvest__
    * __Cur__

* Those terms are just simply short for :  
    * __P/P__ = __Profit/Price__ _is calculated to find how many additional stocks to buy based on the profit earned_
    * __ReInvest__ = __ReInvest Stocks__ _is rounded down from __P/P__ to estimate the exact amount of additional stocks to buy_
    * __Cur__ = __Current Stocks__ _is the current amount of stocks in that quarter_
    
    
    
__I am still trying to improve it by adding more features.__  
__I'm open to any comments or feedback.__  
__Thanks for reading! Hope that it was useful and that you enjoyed it!__  

