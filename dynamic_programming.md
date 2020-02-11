# Dynamic Programming
## Weighted Interval Scheduling  
$I_{1}I_{2}...I_{k}$ where $I_i = [s_{i}, f_{i}]$ and $w_{i} >0$.  
**Goal**: Find a compatible set of intervals, $A$, so as to maximize $\sum_{i\in A}w_{i}$.
## Typesetting Problem
Given a string $S=S_{1}S_{2}S_{3}...S_{n}$ and a penalty function $q$.  
**Goal**: split $S$ into $K$ lines where $i_k = n$ and $K$ is not fixed  
$S_{1}...S_{i_1}$  
$S_{i_1+1}...S_{i_2}$  
$S_{i_2+1}...S_{i_3}$  
:  
:  
$S_{i_{k-1}+1}...S_{i_k}$  
$min\sum_{t=0}^k q(S[i_{t}+1, i_{t+1}])$  
Let $OPT(i)$ be the cost of the optimal solution to subproblem $i$ 
(problem of typesetting of $S[1:i]$).  
$OPT(t) = cost(S[1:j])+q(S[j+1:t])$  
**Claim**:$OPT(t) = min_{j\in{[1,...,t-1]}}(OPT(j)+q(S[j+1:t])$ here we do not know which j is the best yet  
**Proof**: thishi


## Knapsack Problem

