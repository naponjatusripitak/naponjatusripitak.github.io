---
layout: post
title: Rice Pledging, Rainfall and the Vote
description: A research design based on instrumental variables approach
date: 2017-06-09
redirect: /assets/pdf/Rainfall, Rice Subsidy, and the Vote.pdf
tags: social-science
---



Rice Pledging, Rainfall, and the Vote

Introduction
This paper provides a research framework for examining the electoral consequences of rice pledging scheme in Thailand. While existing studies have focused on the economic performance, fiscal implications, and welfare effects of the Thai government’s rice pledging scheme, little scholarly attention has been paid to the causal role that such policy plays in generating, securing, and maintaining political support. That there has been no systematic attempt to shed light on this causal connection is especially striking, considering that the rice pledging scheme has been widely criticized as a populist strategy in policy debates. Building on the literature of distributive politics and clientelism, this paper aims to refocus analytical attention to the political dimensions of the rice pledging scheme. Specifically, it argues that the rice pledging scheme constitutes a form of non-programmatic distributive politics, the salience of which as a mechanism for winning electoral support can be evaluated quantitatively in a research framework geared towards making causal inference.
Methodologically speaking, assessing the impact of the rice pledging scheme on vote choice can be difficult given the possibility of endogeneity and omitted variable bias. In an observational study like this one, establishing causal claims via ordinary least-squares regression runs the risk of conflating the actual effects of treatment with the effects of unobserved confounding factors. To circumvent these limitations, this paper proposes using rainfall variation as an instrumental variable to estimate the causal effect of participation in rice pledging scheme on vote share. 

Presentation of the Arguments
	The practice of distributing selective benefits in exchange for political support can take many forms and has many names: vote-buying (Schaffer 2007), machine politics (Scott 1969; Stokes 2005), clientelism (Hicken 2011; Gans-Morse, Mazzuca, and Nichter 2014), patronage (Kanchan 2007), and more. This study contributes to this existing body of literature on distributive politics by paying close attention to the rise of a new form of non-programmatic political arrangement which is highly institutionalized and formalized, economically unsustainable, yet hugely popular and widely perceived to be legitimate in accordance with the prevailing norms of social justice.
Since its introduction in 2001, the Thai government’s rice pledging scheme has come to play a central role in shaping electoral outcomes. Unlike conventional vote-buying and clientelistic strategies which rely on the delivery of cash, goods, and services via brokers and other informal intermediaries, the rice pledging scheme necessitates the use of state resources and institutions to facilitate linkages between voters and politicians. In other words, the state itself assumes the role of the patron. Future distribution is therefore contingent upon the successful capture of state power by a given political party. As such, voters who currently benefit from the rice pledging scheme are expected to have particularly strong preference for political candidates who represent the continuation of such policy in one form or another. Such voters, predominantly rice farmers, are not merely invested in the policy but are invested in the electoral victory of the party that promises to implement that policy. To illustrate how the rice pledging scheme has turned elections into high-stakes affairs for these voters, I proceed with a brief overview of the rice pledging scheme as it operates in practice.
	The rice pledging scheme is originally designed to provide rice farmers with the much-needed cash in the early harvesting season and a cushion against the volatility of rice prices in the world markets. Under the scheme, rice is pledged as collateral to secure loans of equal value to the pledging price from the Bank for Agriculture and Agricultural Co-operatives (BAAC). At the end of the harvesting season, if the market price exceeds the pledging price, farmers can choose to sell the rice in the market and use the revenue to repay the loan, keeping the remaining amount as profit. On the other hand, if the market price is lower than the pledging price, the government as the official buyer of last resort would procure the rice at the pledging price, thereby guaranteeing the minimum price. 
In practice, however, farmers lack any incentive to sell their rice in the markets, because the pledging price is set well above the market price.  By allowing farmers to pledge their rice with no limits on the quantity of rice and at exorbitant prices, the rice pledging scheme thus provides rice farmers with unprecedented levels of government subsidies and leverage over middleman and wholesalers. It is important to note that, due to government budgetary constraints, payments to farmers are delayed until the government raises enough money by selling the rice in the stockpile to exporters once market prices improve. Rice farmers who participated in the rice pledging scheme, therefore, are more likely to support only political parties that are committed to the rice pledging scheme like the one described above and less likely to vote for other contenders who may or may not maintain the policy for two important reasons: (1) to preserve the existing institutional arrangements under which they are the primary recipients of state-provided benefits, and (2) to ensure that the government upholds the other end of the bargain in delivering the payments to farmers when they are due. These two objectives are different, yet both are perceived to be achievable only under the circumstance in which the incumbent party undertaking the rice pledging scheme wins the election. Although mediation analysis provides one approach to distinguishing between the two causal pathways, this possibility will not be considered systematically in this research design given that such analysis may be more amenable to survey data rather than the type of data explored here.

Empirical Strategy
	In a perfect but impossible world, we would assign a group of rice farmers to be treated with rice pledging scheme and record how they vote. Then, we would rewind the clock and record how the same group of rice farmers would have voted without that treatment. The comparison of the two outcomes would yield a causal estimate of the effects of rice pledging scheme on vote choice. In an ideal but rarely feasible world, we would randomly assign the group of rice farmers to treatment and compare the average vote choice of the treatment and control group, yielding the average treatment effect of the rice pledging scheme on vote choice (see Wantchekon 2003 for a similar type of experimental design). Unfortunately, neither of these two scenarios are possible given the reality of the universe, the nature in which the rice pledging scheme as a treatment is assigned, and the availability of the data.
	First, rice farmers across Thailand voluntarily participated in the rice pledging scheme. While the policy obviously targeted rice-growing regions in which the majority of voters reside, the policy was universally applied with no excludability or restrictions. As such, farmers engaged in self-selecting themselves into treatment for any number of reasons—to the extent that we do not know enough about the treatment assignment mechanism to model it. This confounded assignment implies that farmers’ participation in the rice pledging scheme may be endogenous, that is, correlated with the error term due to the presence of unobserved and uncontrolled confounding variables. The level of treatment is also continuous given that some farmers pledged higher quantity of rice than others. These moving parts make it difficult for us to implement any simple difference in means test or conventional regression-based methods.
	Second, while the data exists at the individual level for participation in the rice pledging scheme, individual vote choice in Thai elections cannot be directly observed. Using a survey instrument to measure vote preference presents one possibility, but one which is likely to be influenced by social desirability bias or fail to estimate voters’ true preferences. 
The research design addresses the problem of confounded treatment assignment by utilizing rainfall as an instrumental variable for participation in the rice pledging scheme. On the other hand, it deals with the problem of unavailability of individual-level election data by shifting the unit of analysis to the district level, for which election data is available, and aggregating other variables accordingly.

Rainfall as Instrumental Variable 
	Why use of rainfall variation as an instrumental variable to estimate the effects of participation in rice pledging scheme on vote choice? Following Miguel and Satyanath (2004) who utilizes rainfall as an instrument for economic performance in agricultural countries, I consider the use of rainfall based on similar criteria.
First, the validity of rainfall as an instrumental variable can be assessed based on the extent to which it is exogenous, or Cov(z,ϵ)=0. I assume that rainfall variation has the characteristics of an as-if random process which more or less randomly sorts districts into treatment and control groups in ways that are unlikely to be related to vote choice, the outcome variable, and a range of other variables and potential confounders, observed or unobserved. Therefore, I treat rainfall variation as an exogenous variation. This assumption implies that rainfall variation affects the outcome of vote choice only through its effect on the treatment of rice pledging scheme. This is a strong assumption—whether such exclusion restriction actually holds is difficult to evaluate as it cannot be tested. However, if such an assumption were to be violated, the degree to which this will generate a bias in our estimate will ultimately depend on the strength of the instrument. This leads to the discussion of the relevance of rainfall variation as an instrumental variable in this study.
Second, whether rainfall variation serves as a valid instrumental variable can be determined on the basis of its relevance, or Cov(z,x)≠0. Theoretically speaking, there is a reason to expect that rainfall variation has an impact on rice output, and by extension on the level of participation in the rice pledging scheme as measured by the amount of rice pledged. At the most fundamental level, districts receiving higher average rainfall are expected to have higher rice output. This is the conclusion reached by Levine and Yang (2014) study of the relationship between rainfall and agricultural output in Indonesia. The same type of relationship may be found in Thailand which shares a similar tropical monsoon climate and is similarly engaged in rice cultivation. On the other hand, whether rainfall variation has a further impact on the amount of rice pledged as part of the rice pledging scheme may be a matter of debate. Luckily, it is possible to evaluate this hypothesis by conducting an F-test on the coefficient of rainfall variation in the first-stage regression which would reveal its strength as an instrument.

Data and Measurement
The study relies on three primary types of data: election data, data on the rice pledging scheme, and rainfall data. This section addresses them individually.
	Election Data
The data on the Thai general elections can be obtained directly from the Election Commission of Thailand. For the purpose of this study, we focus on the 2005 election which is the only election in which the causal effects of rice pledging scheme on votes can be measured appropriately.  The data is available at the district level, indicating the total number of eligible voters and the total number of votes cast for each party which can be used to calculate the proportion of votes received by the Thai Rak Thai, the incumbent party that promised to continue the rice-pledging scheme it had implemented since 2001. This is the outcome variable of interest.

	Data on the Rice Pledging Scheme
The data on participation in the rice pledging scheme can be obtained from the Bank for Agriculture and Agricultural Co-operatives (BAAC). The data is available for the 2001/2002, 2002/2003, 2003/2004 harvesting seasons, indicating the number of farmers who participated in the rice pledging scheme and the amount of loans received by farmers at the district level. Given that the amount of loans is calculated based on the quantity of rice pledged, we can in fact transform the variable to reflect the quantity of rice in metric tons, or we can choose to leave it in terms of the amount of loans received or payments made in Thai Baht. This is the primary explanatory variable we are concerned with, since it indicates the level of participation in the rice pledging scheme.

	Rainfall Data
There are two types of data on precipitation in Thailand: rain gauge and satellite-retrieved data. The former can be obtained from the Thai Meteorological Department (TMD) and the Global Precipitation Climatology Project (GPCP). The data is collected from over 100 rain gauge stations distributed across Thailand, indicating the amount of daily and monthly rainfall in millimeter. This can be aggregated into average annual rainfall. One concern is that rain gauge data may not accurately capture the amount of rainfall per district, because rain gauge stations are not distributed evenly. We may run into the problem of missing data for those districts in which no rain gauge station has been set up. One option is to rely on multiple imputations as an approach to dealing with potentially missing values. A more reliable option, perhaps, is to make use of an alternative source of data, namely, satellite-retrieved data. This type of data can be sourced from Tropical Rainfall Measuring Mission (TRMM). TRMM Algorithm 3B42 provides infrared-based precipitation estimates which can be used for the purpose of the study.

Estimation Framework
	The study employs two-stage least squares (2SLS) regression analysis. In the first-stage regression, the goal is to capture the proportion of variation in our primary explanatory variable, participation in rice pledging scheme, that is uncorrelated with the error term associated with the outcome variable, the proportion of votes received by the Thai Rak Thai party. As such, I introduce rainfall variation as an exogenous variable (〖rain〗_i) and use this to predict the amount of rice pledged or amount of loans received (〖pledge〗_i). To account for district characteristics which may be related to vote share or capture additional variation in participation in the rice pledging scheme, I also include a list of district control variables 〖(X〗_i^') and district-specific intercepts 〖(α〗_1i). The actual content of the list of control variables will be determined in the research process. Equation 1 illustrates this first-stage regression:
〖pledge〗_i= α_1i+ π_1 〖rain〗_i+ 〖X_i^' π〗_2+ υ_i	(1)

At this point, it is possible to check whether rainfall can reliably be used as an instrumental variable. If the F-statistics generated by the first-stage regression is less than two, then the instrument is considered weak and thus may not be suitable for further analysis. On the other hand, if we do not run into this “weak instrument” problem, we can proceed with the second stage, using the fitted values ((〖pledge〗_i ) ̂) from Equation 1. Note, however, that it is also possible to apply the Wu-Hausman test to check for endogeneity of the standard OLS specification, excluding the instrumental variable, by utilizing the residuals from the first-stage regression. 
In the second stage, the goal is to use the exogenous portion of variation in our primary explanatory variable, participation in rice pledging scheme, to estimate the outcome variable of interest (〖voteshare〗_i). I include the same set of control variables and district-level fixed effects. This results in Equation 2:

〖voteshare〗_i= α_2i+ β_1 (〖pledge〗_i ) ̂+ 〖X_i^' β〗_2+ ϵ_i	(2)

Ultimately, we are interested in estimating β_1 which represents the effects of participation in the rice pledging scheme on the proportion of votes received by the Thai Rak Thai party. The coefficient can be interpreted as a change in district-level vote share resulting from a one-unit increase (or percent increase, depending on the nature of the transformation of the variable) in the amount of rice pledged (or amount of loans received as part of the scheme) in a given district. One final step in the analysis is to test the results from a conventional OLS specification excluding the instrumental variable against those estimated using the 2SLS specification with instrumental variable. This test would reveal, as with the Wu-Hausman test, whether the OLS estimates and 2SLS estimates are significantly different. Additionally, we can obtain heteroscedasticity-robust standard errors or clustered robust standard errors. In terms of reporting the results of the analysis, we can report the results of different model specifications, with fixed effects or without, with control variables or without, with alternative data sources, and with different types of standard errors.

Conclusion
	In this paper, I have devised a preliminary research framework for analyzing the effects of participation in rice pledging scheme on the proportion of votes received by the party upholding the scheme in Thailand, using rainfall variation as an instrumental variable. To reiterate, my hypothesis is that greater district-level participation in the rice pledging scheme is likely to generate higher district-level vote share for the party responsible for implementing and maintaining the policy. This causal relationship may seem obvious, but in fact can be quite theoretically significant given that alternative forms of distributive politics such as direct vote-buying, when measured quantitatively, have been regarded as waning in effectiveness. This conclusion is generally taken to imply a transition from non-programmatic and clientelistic form of distributive politics to a programmatic and policy-oriented one. A result that rules in favor of my proposed hypothesis would suggest that such transition is not complete—distributive politics remains deeply clientelistic even when it is centrally organized and rationalized as policymaking. Future work on this research design would do well to incorporate (1) further discussion about the potential violation of the exclusion restriction, (2) consideration of potential control variables, and (3) evaluation of possible mediation effects.
Bibliography
Chokngamwong, Roongroj, and Long S. Chiu. “Thailand Daily Rainfall and Comparison with TRMM Products.” Journal of Hydrometeorology 9, no. 2 (April 1, 2008): 256–66. doi:10.1175/2007JHM876.1.
Fang, Arnold H. “Linkage between Rural Voters and Politicians: Effects on Rice Policies in the Philippines and Thailand.” Asia & the Pacific Policy Studies 3, no. 3 (September 1, 2016): 505–17. doi:10.1002/app5.150.
Gans‐Morse, Jordan, Sebastián Mazzuca, and Simeon Nichter. “Varieties of Clientelism: Machine Politics during Elections.” American Journal of Political Science 58, no. 2 (2014): 415–432. doi:10.1111/ajps.12058.
Hicken, Allen. “Clientelism.” Annual Review of Political Science 14, no. 1 (2011): 289–310. doi:10.1146/annurev.polisci.031908.220508.
Kanchan, Chandra. “Counting Heads: A Theory of Voter and Elite Behavior in Patronage Democracies.” In Patrons, Clients and Policies: Patterns of Democratic Accountability and Political Competition, edited by Herbert Kitschelt and Steven I. Wilkinson, n.d.
Levine, David I., and Dean Yang. “The Impact of Rainfall on Rice Output in Indonesia.” Working Paper. National Bureau of Economic Research, July 2014. doi:10.3386/w20302.
Schaffer, Frederic Charles. Elections for Sale: The Causes and Consequences of Vote Buying. Boulder, Colo.: Lynne Rienner Publishers, 2007.
Scott, James C. “Corruption, Machine Politics, and Political Change.” The American Political Science Review 63, no. 4 (1969): 1142–1158. doi:10.2307/1955076.
Stokes, Susan C. “Perverse Accountability: A Formal Model of Machine Politics with Evidence from Argentina.” American Political Science Review 99, no. 3 (2005): 315–325. doi:10.1017/s0003055405051683.
Wantchekon, Leonard. “Clientelism and Voting Behavior: Evidence from a Field Experiment in Benin.” Natural Field Experiments. The Field Experiments Website, 2003. http://econpapers.repec.org/paper/febnatura/00339.htm.
