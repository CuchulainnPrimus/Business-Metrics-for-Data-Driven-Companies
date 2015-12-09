##Introduction To Return Measures

Money managers are professional investors who are paid to generate a return on other people's money. The money management industry has its own specialized metrics for investment returns in general and for manager's performance in particular.

We will now discuss returns and volatility of returns. Asset returns are calculated in three main ways. For a one-time investment, that pays off in the future, the absolute and annual rates of return can be calculated, either as a continually compounded, or as a {discrete} rate of return. Both continuously compounded, and {discrete} are acceptable metrics, but because the two metrics will not give the same result, in order to get a meaningful apples to apples comparison, always use the same method when comparing two or more returns.

The first method, which calculates the continuously compounded return involves taking the log, to the base e. Usually written as a natural log ln of the ratio of the final price divided by the first price.

```
Continuous Absolute Return = log_e (Final Price/Initial Price) = ln (Final Price/Initial Price) 
```
And this will give us a value for the absolute return. So, if we started with $100 and we ended up with $130, natural log of 1.3, this gives us .2624 or 26.24% for the absolute return over the two year period.
```
ln ($130/$100) = 0.2624 * 100% = 26.24%
```
Then, if we want to calculate the one year or annual return, we simply divided this value by the number of years, 2 years at a value of 13.12% per year.
```
Continuous Annual Return = Absolute Returen/Number of Years = 26.34%/2 = 13.12%
```
The second or (discrete) method involves taking the ratio of the final price divided by the first price minus 1.
```
Discrete Absolute Return = (Final Price/Initial Price) - 1
```
So the way you would do this, is simply to say, $130 divided by $100 - 1 would be equal to 0.3 which is equal to 30%.
```
(130$/$100) - 1 = 0.30 * 100% = 30%
```
So note that the exact same return of $130 gives us 26.24% using the continuously compounded method and 30% using the discrete method.

Now, if we wish to calculate the discrete annualized return, we will need to take the geometric mean of our ratio of final price over first price, and then subtract 1 from that:
```
Discrete Annualized Return = (Final Price/Initial Price)^(1/Number of years) - 1
```
So, in other words, we're going to take our ratio, $130, divided by $100 and we're going to take it to the power that reflects how many time intervals we want to have. So, if we want to have two time intervals for 2 years, we are going to take:
```
($130/$100)^(1/2 years) - 1=1.3^0.5 - 1 = 1.1402 - 1 = 0.1402 * 100% = 14.02%
```
So, again, notice that we get a different value for the geometric mean or discrete annualized return of 14.02% versus the annualized continuously compounded return of 13.12%.

When an investment is not made all at once, but cash is invested at several different times, the metric used to evaluate the overall return is to identify a single fixed discrete, annual rate of return to apply to each of the payments that, if summed, would result in the final pay out. This value is called the internal rate of return, or IRR. For example, assume an investment of $1 million at year 0, and an additional $1 million at year 1, to develop a property that is sold for $5 million at year 4. We set up the problem as an algebra problem where we solve for x:
```
(1 + x)^4 + (1 + x)^2 = 5
```

In other words:
```
(1 + 0.2962)^4 + (1 + 0.2962)^3 = 2.8223 + 2.1778 = 5.001 
```
Next, we're going to look at calculating the geometric mean of a series of annual returns. So, let's suppose that I have four annual returns, +25%, -18%, +10%, and -4%. What I want to know is if I have $1 at the beginning of the four year period, how many dollars will I have at the end of the four year period?

The way that I can calculate this is by looking at each year at a time, and then taking the product. So, I can say for year one,$1 would be $1.25. For year two, $1 would be 0.82 cents. For year three, $1 would be $1.10. And year four, $1 would be 0.96 cents. If I multiply all these together,I'll find that I have 1.0824 or $1.08
```
($1.25)($0.82)($1.10)($0.96) = $1.0824 ~ $1.08
```
and a little bit of extra, for an absolute return over the four year period of 
```
($1.0824/$1.00) - 1 = 0.0824*100% = 8.24%,
```
a little over 8%.

And if I want to convert this to an annualized return, I'm going to take the geometric mean over four time intervals of the value 1.0824. And the way that I do that is
```
($1.0824/$1.00)^(1/4 years) - 1 = 1.0824^0.25 -1 = 1.01999 - 1 = 0.01999*100% ~ 2%
```
and this gives me a geometric mean return of 2%. So, as we've just seen, the geometric mean return of our four different annual returns is just about 2% {as shown in the red bars of the figure below}. So we could have had an investment that returned exactly 2% here for 4 years.

![image](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/xSvVOGfUEeWAwg6u9PPi2Q_53ae2a20a4e02e9fb1fac3f710454c61_Return7.jpg?expiry=1449792000000&hmac=4zGmYU5oaS4e7ZZChGY6ORfwPnSbf4W5U901ZXnLtiE)

And it would've achieved the same outcome as our much more scattered returns, ranging from +25% all the way down to -18%..
