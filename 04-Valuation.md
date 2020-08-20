# Housing valuation {#ch:Valuation}


## Introduction {#sec:IntroValuation}

This chapter is devoted to the assessment of the real estate. Section \@ref(sec:Valuation) explains, why we need to assess the value of properties. In section \@ref(sec:Hedonic), the hedonic approach to the valuation of the real estate is introduced. Section \@ref(sec:Repeated) discusses an alternative valuation method, which is known as the repeated-measures index. In this section, we will talk about the standard approach and about the weighted, or the Case-Shiller approach. In section \@ref(sec:Spatial), we describe the spatial econometric tools that can be useful for analyzing the property value, given its immovable nature and importance of locational characterstics.

## Real estate valuation {#sec:Valuation}

### Motivation
Why valuation of the real estates is needed? There are several reasons why people should bother assessing the value of the property, which are thoroughly discussed below.
	
First, it is important to evaluate the just compensation in compulsory acquisition. Even in the free market economies, the authorities sometimes confiscate the property of the citizens. This can be related, for example, to the construction of a new road or a hydroelectric plant. Typically, the owners receive compensation for the real estate they lose. However, is this compensation fair? Or is the price offered by the authorities far below what your property is worth?

Second, the knowledge about the property value is necessary for the fair taxation. In most countries, the owners of the real estate pay property taxes on the annual basis. In Russia, for instance, the value of each property is registered in the cadastre. The authorities using certain methodology and information about characteristics of the real estate estimate its taxable value. Is this value fair or is it set to high, since it does not take into account some important factors reducing the true value of the property?

Third, the information about the value of the real estate is needed for the market transactions. For example, you want to buy or sell a dwelling. In that case, you have to know its fair market price. If you buy the dwelling, you do not want to pay a price that is too high. In case you sell it, you have to be sure that the price you are paid is not too low.

Fourth, property can be bought using borrowed money or used as security in order to obtain a mortgage loan. Both the bank lending money and the borrower need to know the fair value of the property. What happens, if the assessment was wrong? In case of bank, this can lead to the impossibility to recover the lent money, if the borrower defaults. In case of the borrower, the failure to assess the real estate correctly can lead to a lower amount of loan.

this question. The agents who are interested in assessing the real estate are sellers, buyers, investors, banks, and state. In other words, the assessment of property is important for the major market players. 

### Valuation methods
There are three main methods of assessing the value of the real estate: Sales comparison method; income, or investment, method; and cost method. In what follows, we will discuss each method using the same framework. First, we will briefly summarize the essence of the method. Second, we will show in which areas the method is mostly used. Third, we will show how each method can be derived.


### Sales comparison method
*Essence of the method*. The market value of real estate is related to prices of comparable, competitive properties. The method derives the value from direct comparison with sales of similar or comparable properties in the market.
	
*Popularity*. The method is regarded as the most valid indicator of market value. It is the most widely used valuation method in practice.
		
*Derivation*. The derivation of the sales comparison method is based on the following principles: utility; supply and demand; and substitution.

*Utility*: The value of each property depends on a bundle of utility-forming characteristics associated with it. For example, its size; location; physical condition, etc. *Supply and demand*: Market prices arise from interactions between buyers and sellers. *Substitution*: the housing price is the price paid to acquire a substitute property having similar utility within a reasonable amount of time. Thus, in order to obtain a housing price estimate, one needs to take a sample of dwellings containing data on their characteristics and prices and to take into account the contribution of each relevant characteristic to the observed price.

According to the sales comparison method, the price of a property can be decomposed into contributions of different characteristics:
\begin{equation}
	p_i^{SCM} = \sum_{j=1}^J \alpha_j x_{ij}
\end{equation}
where $p_i^{SCM}$ is the assessed price of a dwelling; $x_{ij}$ is the value of characteristic $j$ of dwelling $i$; and $\alpha_j$ is the "shadow price'', or value contribution of characteristic $j$.

There are some issues related to the sales comparison method. The sales comparison requires sufficiently competitive markets to work well. This implies that the following conditions must be met. First, there must be many buyers and sellers in active competition. Second, no individual should be able to influence prices, i.e., all market agents are price takers. Third, the product traded at the market (e.g., dwelling) should be fairly homogeneous. Fourth, the prices represent equilibrium between supply and demand.

As a rule, the market price is used as proxy for fundamental value. However, it can largely deviate from the fundamental value. For example, the equivalence between the market price and the fundamental value does not hold during the buildup of speculative bubbles. In thin markets, where few transactions take place, the method can lead to invalid results.	
			

### Investment, or income, method
*Essence of the method*. This method is based on the stream of income related to the real estate, which needs to be assessed. In case of the real estate, the income is the rent paid periodically for the right to use the property. Then, the value of income-producing property is function of the amount of rent achievable and return required by investor.
	
*Popularity*. The method is mainly used for the valuation of commercial real estate. It is less often used for the valuation of the residential properties.

*Derivation*. In order to assess the value, two pieces of information are needed: the magnitude of rent, or cash flow; and the required rate of return, or discount rate. The method has two basic variants: the direct capitalization method and the discounted cash flow (DCF).

According to the investment, or income, method, the price of a property is the discounted flow of net rental revenue:
\begin{equation}
	p_i^{IM} = \sum_{t=1}^T \frac{r_{it}}{(1+\tau)^t}
\end{equation}
where $p_i^{IM}$ is the assessed price of a dwelling; $r_{it}$ is the net rental revenue for dwelling $i$ in year $t$; $\tau$ is some discount rate; and $T$ is the planning horizon over which the cash flow is expected (e.g., in Germany, $T=20$ years). The net rental revenue is a difference between the rental revenue (rents paid by the tenants to the owner) minus all costs related to the property (current maintenance costs, expenses for larger refurbishments, property taxes).

The following issues are related to the investment, or income, method: The method requires the agents to be rational. This means that they must have full information about the market (discount rates, market rents, operational expenses, etc.). In addition, the rental housing and capital markets must be in equilibrium. Otherwise, the valuer cannot be sure that the input information is valid. The method provides a proxy of the investment value, instead of the market value. The DCF approach requires making assumptions about revenues, expenses, and discount rates, many of which cannot be observed empirically. Forecasting cash flows and discount rates for over 10 years in the future presents serious challenges.


### Cost method
*Essence of the method*. A rational purchaser of the real estate will not pay more for it than the cost of constructing an equally desirable substitute less depreciation. Therefore, the value of the property corresponds to the cost of building the existing structure and of making improvements (direct cost plus indirect costs plus entrepreneurial profit) minus all accrued depreciation as of effective date of valuation plus the value of land.

*Popularity*. Unlike the previous two valuation methods (sales comparison and investment method), the cost method is considered to be the method of last resort. Many valuers do not accept it as a legitimate valuation method. It is mainly used in the cases, where there is no reliable market activity (schools, hospitals, churches, public libraries, etc.).

*Derivation*. This method is derived based on the following principles: substitution; contribution; externalities; as well as the highest and best use.

*Substitution*: It is assumed that a prudent buyer would pay no more for a property than the cost to acquire a similar site and construct improvements of equivalent utility.
*Contribution*: The property components (land and structural improvements) must be in proper proportion, if optimum value is to be achieved. *Externalities*: There are factors that are outside of the property but which also affect its market value: crime; pollution; noise; and degrading neighborhoods. The valuer should try to take these factors into account. *Highest and best use*: The assessed value should have as a reference the optimum market related use of real estate.

According to the cost method, the price of a property can be represented as a sum of expenses made to build or reconstruct the property (land, building, refurbishment):
\begin{equation}
	p_i^{CM} = \sum_{j=1}^J (c_j - d_j) + p^L_i
\end{equation}
where $p_i^{CM}$ is the assessed price of a dwelling; $c_j$ is the cost of item $j$; $d_j$ is its depreciation; and $p^L_i$ is the value of the land plot.

\textit{Problems related to the cost method}. Typically, when the cost method must be used, there is no full knowledge of all relevant information. The cost sunk in constructing the building may not be realizable in prices, at least not in the short run. A mere summation of land and structure costs may not generate results in accordance with actual transaction prices. The additive approach is not in accordance with market behavior: in the market, properties are transacted as wholes. The depreciation calculations are relatively arbitrary, which diminish credibility of the method. The value of land is supposed to be established by means of comparable sales of similar vacant land. However, such sales are likely to be absent in built-up areas.


## Stratified valuation {#sec:Stratified}
How to assess the value of real estate practically? The most evident approach is to compute median or mean prices of a subsample of property objects. However, this approach can be misleading. The composition of the sample can change from year to year. For example, in one year more high quality dwellings are offered for sale than in the next one. Since high quality dwellings are worth more, the average price in the first year will be higher than in the second one, although the price for comparable dwellings remained unchanged. In general, the quality of new dwellings increases and, hence, the quality of the whole housing stock improves. However, the price increases related to the quality improvement must be separated from the overall market price increases that are not related to the characteristics of dwellings.

Price changes must be decomposed in inflationary and quality changes. There are three approaches that can solve this problem: stratified valuation; hedonic model, which uses data on different dwellings and multiple regression method; and repeat sales approach, which takes advantage of dwellings sold more than once during the sample period.

The **stratified valuation** method is probably the simplest and the most intuitive approach to assessing the real estate. It consists in collecting a subset of objects (e.g., dwellings) that have as much as possible similar structural and locational characteristics and computing an average or median price for them. For instance, a proxy for the price of $i$-th dwelling in period $t$ can be computed as:

\begin{equation}\label{eq:Stratified}
p_{it}=\frac{\sum_{j=1}^J p_{jt}}{J}
\end{equation}
where $p_{jt}$ is the price of $j$-th dwelling in period $t$, which has similar characteristics as the dwelling $i$, that is, comparable area, number of rooms, floor, building, construction materials, district, etc. If the dwellings that are used in order to compute the average price are chosen carefully and have a very large degree of similarity with dwelling $i$, then the proxy will be very accurate. It is the method that many people intuitively use when looking at the Internet advertisements and selecting a subsample thereof to gauge the value of a dwelling they have in mind.

However, this approach has an evident disadvantage: There is a tradeoff between the similarity of comparable dwellings and their number, $J$. The more similar dwellings are chosen, the fewer they are. And if the market is not active, the valuer risks not to find a sufficiently large number of dwellings to compare with. The hedonic approach that we are going to discuss next is not subject to this limitation.

## Hedonic approach {#sec:Hedonic}
According to the hedonic approach to real estate valuation, each dwelling or any other real estate object can be considered as a set of features. Each of these feature has its value. Therefore, the total value of the dwelling is the sum of the values of its features.

The original purpose of the hedonic approach is the construction of the price index. How can the inflationary price increase can be identified? There are at least to possibilities to do it.

The first option is to use the period-specific regressions. In this case, a separate regression is run on data from each time period. The estimated equations can be used to predict the value of a "standard unit'' in each period. The characteristics of the unit being valued, thus, do not change over the estimating period. The price index results from dividing the predicted value of the standard unit in period $t$ over that in period $t-1$. Formally, the period-specific regression can be expressed:
	
\begin{equation}
		p_{it} = f_t(S_i, L_i)
\end{equation}
where $p_{it}$ is the price of the $i$-th dwelling in period $t$; $f_t(\cdot)$ is the functional form linking price of housing to its features; $S_i$ is a set of structural features; and $L_i$ is a set of locational features.

The second option, consists in estimating a single regression, which is run on the pooled data from sales in all time periods. This regression must include time dummies: for $T$ periods, $T-1$ dummies are needed. Each of them takes value 1, if the dwelling is sold in the corresponding period, and 0, if the dwelling is sold in different period. The intercept will reflect the average value of a benchmark dwelling in some basis period. Then, the series comprised of the estimates of the intercept and of the coefficients of time dummies will reflect the movement in prices, which is not related to their characteristics. The single regression can take the following linear form:

\begin{equation}
		p_{it} = f(S_i, L_i, T_i)
\end{equation}
where $T_i$ is the time dummy.

However, the relationships between the dependent and explanatory variables must not necessarily be linear. The Box-Cox transformation offers a way to flexibly model the non-linear hedonic regression. It is formulated as follows:
\begin{equation}
		\frac{p_i^{\lambda}-1}{\lambda} = \alpha + \beta'S_i + \gamma'L_i + \delta'T_i + \varepsilon_i
\end{equation}
where $\lambda$ is a non-linearity parameter. Depending on it, the hedonic regression takes different forms (if $\lambda=1$, then Box-Cox model turns into linear equation; if $\lambda=0$, then the model turns to the semilogarithmic equation); $\alpha$ is the constant; $\beta$, $\gamma$, $\delta$ are parameters measuring contribution of characteristics; and $\varepsilon_i$ is the random disturbance.
	
Another way to model the non-linearity in the hedonic regression is to use the logarithm. This transformation can be applied to either dependent variable, or explanatory variables, or both. Below, all four possible transformations are considered.
	

The linear regression:
\begin{equation}
		p_i = \beta'S_i + \gamma'L_i + \delta'T_i + \varepsilon_i
\end{equation}

The log-linear (semilogarithmic) regression:
\begin{equation}
		\log(p_i) = \beta'S_i + \gamma'L_i + \delta'T_i + \varepsilon_i
\end{equation}

The linear-log regression:
\begin{equation}
		p_i = \beta'\log(S_i) + \gamma'\log(L_i) + \delta'T_i + \varepsilon_i
\end{equation}

The log-log regression:
\begin{equation}
		\log(p_i) = \beta'\log(S_i) + \gamma'\log(L_i) + \delta'T_i + \varepsilon_i
\end{equation}

The parameter estimates for different logarithmic transformations have different interpretation. Table \@ref(tab:LogInterp) reports these interpretations.

<caption> (\#tab:LogInterp) Interpretations of parameter estimates of logarithmic transformations </caption>

| Specification  | $\Delta x$ | $\Delta y$ |
|----------------|:-----------:|:---------|
| Linear | 1 unit | $\beta$ |
| Log-linear | 1 unit | $100 \cdot\beta$ |
| Linear-log | 1\% | $0.01 \cdot\beta$ |
| Log-log | 1\% | 1\% | 

For example, in case of the linear model, a change of the explanatory variable by one unit leads to the change of the dependent variable by $\beta$ units. If the dependent variable is the purchasing price per square meter in rubles and the explanatory variable in question is the number of rooms and $\beta=2000$, then the increase of this number by one will result in the increase of the square-meter price by 2000 rubles.

## Repeated-measures index {#sec:Repeated}
The hedonic approach employs information on large number of heterogeneous dwellings and estimates the coefficients that measure the contribution of different characteristics of dwellings to their value. However, the accuracy of these coefficients is not perfect, given the uncertainties related to the statistical estimates. @Bailey_et_al_1963 suggested to take advantage of information on the same dwellings sold more than once. Therefore, their method is called the **repeated-measures index**, or **repeat-sales index**. A good housing price index must capture price increase unrelated to change in quality. This increase can be best isolated by comparing similar dwellings and nothing is more similar than the same dwellings.

The repeated-measures method has two main advantages. First, it more accurately accounts for characteristics of properties. Second, it does not require the measurement of quality. The method has the following two disadvantages. First, it implies a waste of data, since in most data sets only a small proportion of all housing transactions  reappear and are used in the repeated-measures method. Second, such observations are possibly not representative of general population.

According to the methodology of the repeated-measures index, the price of $i$-th dwelling in period $t$ can be decomposed as:

\begin{equation}
	p_{it} = \alpha_i + \beta_t + \varepsilon_{it}
\end{equation}
where $p_{it}$ is logarithm of price; $\alpha_i$ is the underlying value and, hence, quality, of dwelling; $\beta_t$ is the value of the log price index; and $\varepsilon_{it}$ is the noise, $\varepsilon_{it} \sim N(0,\sigma^2)$.

For any two periods, $t_1$ and $t_0$, difference of log prices of dwelling $i$:
\begin{equation}
	p_{it_1} - p_{it_0} = \beta_{t_1} - \beta_{t_0} + \varepsilon_{it_1} - \varepsilon_{it_0}
\end{equation}

If generalized for all time periods, this yields a regression equation:
\begin{equation}
	p_{it_1} - p_{it_0} = \sum_{t=1}^T\beta_{t} D_{it} + \varepsilon_{it_1} - \varepsilon_{it_0}
\end{equation}
where $D_{it}$ is a set of dummy variables, such that:

\[ 
D_{it}=\left\{ \begin{array}{c} 
1\mbox{, if } t = t_1\\[1ex]
{}-1\mbox{, if } t = t_0
\end{array} \right.
\]
The OLS regression of the ratio of log prices on $D_{it}$ produces predicted values $\hat{\beta}_t$ for each year, which correspond to the growth rate of the index relative to the base year. Finally, the house price index is obtained as:
\begin{equation}
	\hat{P}_t = 100 \times \exp(\hat{\beta}_t)
\end{equation}

As a further development of the repeated-measures index, @Case_Shiller_1987 suggested a **weighted repeat sales** index (WRS). Their index has the following motivation. The standard repeat sales index relies upon two assumptions: first, the noise term, $\varepsilon_{it}$, is uncorrelated across houses and through time; and, second, its variance, $\sigma^2_{\varepsilon}$, is constant. However, the variance of error term is not constant across houses. It is likely to be related to the interval of time between sales. Thus, homes sold after long time intervals have great influence on the index relative to homes sold over short time intervals. Therefore, such long time interval observations should be given less weight.

The drift through time of individual house values occurs due to random differences in the amount of upkeep expended across houses or to random changes in neighborhood quality. Formally, the Case-Shiller WRS index can be expressed as:
		
\begin{equation}
		p_{it} = a_{it} + b_t + \varepsilon_{it}
\end{equation}
where $p_i$ is the log price of $i$-th dwelling in period $t$; $a_{it}$ is the individual value drift such that $a_{it} = a_{it-1} + u_{it}$ ($u_{it}\sim N(0,\sigma^2_u$); and $b_t$ is the city-wide level of housing prices at time $t$. The purpose of the WRS is to estimate $b_t$.

The WRS index is estimated in three stages. In stage 1, a standard repeat sales regression is estimated:
\begin{equation}
	p_{it_1} - p_{it_0} = \sum_{t=1}^T\beta_{t} D_{it} + \varepsilon_{it_1} - \varepsilon_{it_0}
\end{equation}
In stage 2, a regression for squared errors from stage 1 is estimated:
\begin{equation}
	\tilde \varepsilon^2_{it} = c + \gamma(t_1 - t_0) + \eta_{it}
\end{equation}
where dependent variable is defined as $\tilde\varepsilon_{it} = \varepsilon_{it_1} - \varepsilon_{it_0}$; constant $c$ is an estimate of $2\sigma^2_{\varepsilon}$; slope $\gamma$ is an estimate of $\sigma^2_u$.

In stage 3, the following weighted regression is estimated:
\begin{equation}
	\frac{p_{it_1} - p_{it_0}}{\hat{\varepsilon}_{it}} = \sum_{t=1}^T\delta_{t} D_{it} + \epsilon_{it_1} - \epsilon_{it_0}
\end{equation}



## Spatial dependence {#sec:Spatial}
One of the most important properties of the real estate is its immobility. Therefore, the space matters. Spatial effects take two forms: spatial heterogeneity and spatial dependence. Spatial heterogeneity means that the objects differ in space. For example, there are rich and poor neighborhoods, there are central and peripheric districts of the city, which differ in terms of their location and their characteristics. Formally, spatial heterogeneity can be expressed as follows:
\begin{eqnarray}
		p_i = f_k(X_i\beta+\varepsilon_i) & i = 1,\ldots,N
\end{eqnarray}
where $p_i$ is the price for dwelling $i$; $k$ is the index denoting some location; $f_k(\cdot)$ is the location-specific function relating the price of the dwelling to its characteristics, $X_i$; $\beta$ is the vector of parameters to estimate, and $N$ is the number of dwellings. Thus, the elasticities of the dwelling's value to its characteristics can vary as a function of space. The price of the centrally located dwellings can react differently to the proximity to some urban amenities or to the public transit than the dwellings located in the outskirts of the city. If the spatial heterogeneity is not taken into account in our hedonic model, this can lead to the inefficiency and/or biasedness and inconsistency of the parameter estimates.
	
The spatial dependence means that the closer the objects are to each other the stronger they are correlated. Why this may be the case? The objects located next to each other tend to be subject to the same influences. For example, two dwellings situated in the same building depend on its state and, hence, are more closely related to each other than to the dwellings in a different building. Two dwellings located in the same neighborhood are subject to the impact of pretty the same socio-economic, demographic, climatic, ecological, and other characteristics of the neighborhood. The farther the two dwellings are from each other the less common impacts they share and, therefore, the less they are dependent on each other. For example, this dependence can be reflected in the values of dwellings.

In mathematical terms:
	
\begin{eqnarray}
		p_i = f(p_j) & \mbox{ } i = 1,\ldots,N & j \neq i
\end{eqnarray}
Thus, the price of dwelling $i$ depends on the price of dwelling $j$. Moreover, this dependence gets stronger the closer dwelling $i$ to the dwelling $j$. The proximity between dwellings can be measured using different means. One example is the direct distance between them. The failure to account for the spatial dependence can lead to the inefficiency and/or biasedness and inconsistency of the parameter estimates.

The general spatial model can be formulated as follows:

\begin{equation}
\begin{array}{c} 
p = \rho W_1 p + X\beta + \varepsilon \\
\varepsilon = \lambda W_2\varepsilon + u \\
u \sim N(0, \sigma^2I_N)
\end{array}
(#eq:SpatialModel)
\end{equation}

where $p$ is the vector of housing prices; $X$ is the matrix of explanatory variables; $W_1$ and $W_2$ are the $N\times N$ spatial weight matrices; $\rho$ and $\lambda$ are the coefficients of spatial dependence; and $u$ is the serially and spatially uncorrelated disturbance term.
	
There are several special cases of the general model in equation \@ref(eq:SpatialModel) that often used in the literature. The first is the **spatial autoregressive** (SAR) model:
\[\begin{array}{c}
	p = \rho W_1 p + X\beta + u \\
	u \sim N(0, \sigma^2I_N)
\end{array}
\]

The second is the **spatial error** (SEM) model:
\[\begin{array}{c} 
	p = X\beta + \varepsilon \\
	\varepsilon = \lambda W_2\varepsilon + u\\
	u \sim N(0, \sigma^2I_N)
	\end{array}
\]
	
An important element of each model with spatial dependence is the spatial weight matrix. Usually, it takes the following form:
\[\left(\begin{array}{cccc} 
	w_{11} & w_{12} & \ldots & w_{1N} \\
	w_{21} & w_{22} & \ldots & w_{2N} \\
	\vdots & \vdots & \ddots & \vdots \\
	w_{N1} & w_{N2} & \ldots & w_{NN} \\
	\end{array}\right)
\]
where $w_{ij}$ is the measure of proximity between $i$ and $j$, such that $w_{ii}=0$ for all $i=1,\ldots,N$.

Typically, spatial weights are inverse functions of distances between objects $i$ and $j$, $d_{ij}$:
\begin{equation}
	w_{ij} = d_{ij}^{-\delta}\mbox{, where }\delta>0
\end{equation}

Often very distant observations are discarded, since they have no noteworthy impact, while their exclusion would simplify estimations. This can be done using two options. The first option is to set a cutoff distance, $c$:
	\[d_{ij}=\left\{\begin{array}{c} 
	d_{ij}\mbox{, if } d_{ij}<d\\
	0\mbox{, otherwise.}
	\end{array}\right.
\]
The second option is to keep only $K$ nearest neighbors and discard all the other.

The elements of spatial weight matrix are usually (not always) row-standardized:
\begin{equation}
	\tilde{w}_{ij} = \frac{w_{ij}}{\sum_{k=1}^Kw_{ik}}
\end{equation}
Therefore, the $i$-th element of vector $Wp$, $\sum_{j=1}^J\tilde{w}_{ij}p_j$, can be interpreted as a weighted average of the neighbors of dwelling $i$.

																		
### Geographically weighted regression {#sec:GWR}
As pointed out in the previous section, the housing markets are localized and, hence, characterized by spatial dependence and spatial heterogeneity. The spatial dependence is accounted for in the models with spatial dependence. The geographically weighted regression (GWR) provides a means for modelling the spatial heterogeneity by allowing relationships between the explanatory and dependent variables to vary in space. The utility of GWR consists in that it can be used to look for localized exceptions or deviations from global trends.

The standard OLS regression:
	
\begin{equation}
		p_{i} = \beta_0 + \sum_{k=1}^K \beta_k x_{ik} + \varepsilon_i
\end{equation}

The geographically weighted regression:
\begin{equation}
		p_{i} = \beta_0(u_i,v_i) + \sum_{k=1}^K \beta_k(u_i,v_i) x_{ik} + \varepsilon_i
\end{equation}
where $(u_i,v_i)$ are the coordinates of dwelling $i$; and $\beta_k(u_i,v_i)$ is the realization of continuous function $\beta_k(u,v)$ at point $i$.

The standard OLS estimator of parameters:
	
\begin{equation}
		\beta = (X'X)^{-1}X'y
\end{equation}

The GWR estimator of parameters:
\begin{equation}
		\beta(u_i,v_i) = (X'W(u_i,v_i)X)^{-1}X'W(u_i,v_i)y
\end{equation}
where $W(u_i,v_i)$ --- $N\times N$ weight matrix, whose diagonal elements, $w_{ij}$, are the geographical weighting of observed data for point $i$ and off-diagonal elements, $w_{jl}=0$ s.t. $j\neq l$.

## Recommended literature {.unnumbered #sec:LitValuation}

| Topic | Source |
|----------------|:--------------------|
| Real estate valuation | @Mooya_2016| 
| Hedonic approach | @Malpezzi_2003 |
| Repeated-measures index |@Bailey_et_al_1963|
| Case-Shiller approach |@Case_Shiller_1987 |
| Spatial dependence | @LeSage_Kelley_2009|
| Geographically weighted regression | @Grose_et_al_2008 |


## Exercises {.unnumbered #sec:ExValuation}

1. Assume that you estimated a hedonic regression for housing rent (rubles per month for dwelling) and obtained the following results:


Table: (\#tab:Hedonic)Estimation results of a hedonic regression

Variable                                      Estimated coefficient
-------------------------------------------  ----------------------
Constant                                                      10000
Number of rooms                                                 500
Availability of elevator (1 = yes, 0 = no)                      300
Distance from the city center, km                              -200
Building material: brick                                       3000
Building material: concrete                                   -1000

  a. How much will be the rent for a 2-room flat in a building with walls of brick, having an elevator, and located at 1 km from the city center?
  b. How much will be the rent for a similar flat in a building made of concrete, having an elevator, and located at 10 km from the city center? 
  c. How big will be the difference in the rents of both flats and what will be the contribution into this difference due to the distance to the city center?
2. Assume that you would like to buy a residential building. You know that the building has 20 apartments, the monthly rent paid by the tenant of each apartment to the landlord is 20,000 rubles, the banking long-term interest rate is 10\%, and your planning horizon is 10 years. Assume also that the maintenance cost is 800,000 rubles per year per whole building. Will you buy the building, if the owner offers it for 30 million rubles? Will your decision change, if the interest rate declines to 7, 6, or 5\%?
3. Suppose that there is a non-residential building constructed 20 years ago that you would like to transform into a hospital. Are you ready to pay for this building 15 million rubles, given that the initial construction cost was 10 million rubles; depreciation rate is 2\%; the land is worth 3 million rubles; and the transformation cost is 4 million rubles? Which valuation method do you need to use in this case?
4. Explain why the prices of dwellings located in the same neighborhood can be correlated?

	
## Key terms	{.unnumbered #sec:KTValuation}


----------------------------  ------------------------  -----------------------------------
sales comparison method       hedonic approach          Case-Shiller approach              
investment or income method   stratified valuation      spatial dependence                 
cost method                   repeated-measures index   geographically weighted regression 
----------------------------  ------------------------  -----------------------------------
