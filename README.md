# Multi-Criterion-Optimization
Multi-Criterion Portfolio Optimization with Mean-Variance-Skewness-Kurtosis Portfolio

> Content  

1. Multi Asset Portfolio 

a.	Individual performance of a multi asset portfolio 

b.	Equally weighted performance of the multi asset portfolio  




2. Single Criterion Optimization 

a.	Excess Return optimization 

b.	Variance optimization 

c.	Skewness optimization 

d.	Kurtosis optimization 





3. Multi-criterion Optimization 

a.	Non-normalized criterion approach

b.	Normalized criterion approach 

c.	Normalized criterion with investor preference approach 



> Note: 

**MVSK_Optimization.ipynb** : Cover all the content mentionned above with the use of scipy minimize library to find optimal portfolios. In this case of complex optimization problem, the use of this optimization library isn't optimal and can block the optimization in local minimum.


**MVSK_Optimization_MC_Optimizer_Engine.ipynb** : Aims to solve the local minimum issue stated above by using a time costly method of mapping an important quantity of random weight to find a more accruate optimality. 




