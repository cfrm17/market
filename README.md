# Financial Market Basics

A financial market is a market where people trade financial products. Typical financial markets are the fixed income and interest rate market, the currency market, the equity market, the commodity market and the credit market. 

One of the central tenets of financial economics is the necessity of some tradeoff between risk and expected return. This presentation gives an overview of financial market basics

Keywords:
Financial market, financial returns, market price, model price, no arbitrage, risk neutral measure.

	Financial Market Definition
	A financial market is a market where people trade financial products.
	Types of financial markets
	Fixed income and interest ate market
	Currency market
	Equity market
	Commodity market
	Credit market
	There are spot market and derivative market within each market above.

	Financial return
	Financial return is the measure of profit or loss on an investment.
	Return is more important than value itself.
	Return types
	Absolute return: 	R_A=V_t-V_(t-1)
	Relative return:		R_R=V_t/V_(t-1) -1
	Log return:		R_L=ln⁡(V_t/V_(t-1) )
	Return attributes
	Log return is similar to continuous compounding.
	Log return is additive, i.e., R_02=R_01+R_12.
	For a short horizon, R_R≈R_L
	Returns are nearly independent and similar to a random walk.
	Returns in future are unpredictable.

	Price Determination
	Actual market price determination
	Determined by supply and demand
	Gauged in the real-world measure
	Supply side determination factors
	Transaction costs
	Liquidity
	Risk/reward preferences of suppliers
	Capital availability
	Tax rules
	Differential information
	Demand side determination factors
	Transaction costs
	Liquidity
	Accounting
	Tax rules
	Model price determination
	Determined by model and calibration
	Gauged in the risk neutral measure
	If a trade has the market price, then
	Model is mainly used to compute risk, such as sensitivities.
	Model price needs to be calibrated to the market price.
	If a trade doesn’t have a market price
	Model price is used for transaction.
	Model should be calibrated to price Vanilla products correctly.

	No Arbitrage and Risk Neutral Probability Measure
	No arbitrage
	The law of one price: The same cash flow should have the same price.
	It is impossible to invest 0 today and receive positive tomorrow.
	Two portfolios having the same payoff at a given future date must have the same price today.
	Risk neutral probability measure or simply risk neutral measure
	Risk neutral probability measure is no arbitrage.
	The Arrow security prices are so-called risk neutral probabilities.
	A risk-neutral probability is not a real mathematical probability.
	These prices are called probabilities as they fulfill the criteria of probabilities so that probability theory can be used.
	In mathematics, Martingale measure is equivalent to risk neutral measure

	Fixed Income and Interest Rate Market Basics
	Fixed income and interest rate market mainly consists of bonds, notes, debenture, certificates, mortgages, money market funds and interest rate derivatives.
	Central to any interest rate related topics is to calculate accrued interest.
	Two factors are needed in order to compute accrued interest: compounding and day count.
	Commonly used compounding:
	Annual compounding: the accrual interest is given by
A(0,t)=〖(1+r)〗^t
Where r is annual compounded interest rate and t is the accrual period in years.
	N-time compounding per year, such as semi-annually (n=2), quarterly (n=4), monthly (n=12), etc.: the accrual interest can be expressed as
A(0,t)=(1+r/n)^nt
	Continuously compounding: the accrual interest can be represented as
A(0,t)=exp⁡(rt)
	Simply compounding: the accrual interest is given by
A(0,t)=rt


	Day count convention or day count fraction
	Day count convention is used to determine accrual period.
	Commonly used day count conventions are 30/360, Act/Act, Act/365, Act/360, etc.
	For example, the accrual period of 30/360 convention between t_1 (Y_1,M_1,D_1) and t_2 (Y_2,M_2,D_2) is
t_12={360*(Y_2-Y_1 )+30*(M_2-M_1 )+(D_2-D_2)}/360


	Interest rate curve:
	Yield curve or zero-coupon curve or zero curve is the term structure of interest rates.
	Zero bond curve is the term structure of discount factor.
	Bond curve is the term structure of bonds.
	Swap curve is the term structure of liquid instruments, such as futures and swap rates.

	Currency or FX Market Basics
	Market convention is one of the biggest sources of confusion for those new to the currency market.
	FX quotation
	The quotation 1.25 EUR/USD, for instance, means that one Euro is exchanged for 1.25 USD.
	In this case, EUR (nominator) is the base currency and USD (denominator) is the quoted currency.
	Spot date
	The spot date or value date is the day the two parties actually exchange the two currencies.
	A currency pair requires a specification of the number of days between trade date and spot date, typically 2 business days.
	Holidays
	The holidays of a currency pair is the union of the holidays of two currencies.

	Equity Market Basics
	Equity price is reported by Exchanges.
	Dividend convention
	Record date or cut-off date is the date of dividend payment eligibility. The shareholders of record as of the record date will be entitled to receive the dividend.
	Ex-dividend date is set exactly 2 business days before the record date. On and after the ex-dividend date, a buyer of the stock will not receive the dividend.
	The stock price usually drops at the ex-dividend date.
	Dividend types:
	Discrete dividend.
	Dividend yield or continuous dividend.

	Historical Volatility vs Implied Volatility
	Historical volatility
	It is the standard deviation of the return time series of an asset.
	It is obtained under the real world measure.
	Implied volatility
	It is a model parameter used to back up the market price.
	It is derived under the risk neutral measure.
	Implied volatilities could be bigger or smaller than historical volatilities.



References:

https://finpricing.com/lib/IrCurve.html

https://bitbucket.org/cfrm17/market/downloads/market-10.pdf

