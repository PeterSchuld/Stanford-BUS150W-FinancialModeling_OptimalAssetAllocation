# Stanford-BUS150-Financial Modeling-
Stanford Continuing Studies course BUS 150 "Financial Modeling and Business Decisions" by Iddo Hadar, Summer 2017

### Final Assignment: »Proposal for an analytical Asset Allocation Model using MS Excel«

#### Customer/Decision Maker: ####
Prepared for Members of the Senior Management of a US Pension Fund (Asset Allocation Comitee) to support the Strategic Asset 
Allocation Decision of Portfolio weights for varioustock markets, taken quarterly. 

#### Decision: #### 
Invest in efficient portfolios with the highest Expected Excess Return = E(Return_PF) - E(Risk_Free_Return) for a given level of
Expected Risk E(Vola). If the pension fund can invest in credit risk free fixed income instruments as well (e.g. US government
bonds), than only invest in the most efficient PF (Market Portfolio) that has the highest possible Sharpe Ratio = E(Excess
Return_PF) / E (Vola_PF) for any level of risk.

#### Key Relationships/Drivers: ####
Stock market returns are stochastic variables and stock returns follow a log normal distribution (LN)

#### Key Assumptions: ####
Expected Future Return of a Portfolio μ = E(Return_PF) = Geometric Average Past Returns of weighted stock constituents. Expected
Future Standard Derivation of a portfolio δ = E(STD) = Past STD of that portfolio, Expected Correlation ρ = E(Corr) between two or
more stocks is equal to past correlations. Therefore, the Expected futurestock price and it's distribution is fully determined by 
it's past μ and δ. μ(PF) = weight (stock_1) * μ(stock_1) + weight (Stock_2) * μ(stock_2). δ (PF) = weight (stock_1)^2 * δ
(stock_1)^2 + weight(stock_2)^2 * δ (stock_2)^2 + 2 * δ (stock_1) * δ (stock_2) * ρ (Stck_1, Stock_2)

#### Key Constraints: ####
Sum of weights = 100 (i.e. no leverage). Weight of USD (incl. HKD) min. 40%.

#### Model User(s): ####
Senior Analyst or Portfolio Manager at a Pension Fund

#### Source for Raw Data: ####
Yahoo Finance (Indices) and FXTOP for currencies 
