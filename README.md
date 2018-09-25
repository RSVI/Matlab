# Risk Sensitive Value Iteration algorithm and optimized strategies
Risk Sensitive Markov Decision Process (RS-MDP) allows modeling risk-averse and risk-seeking attitudes in decision-making process. An algorithm that may solve problems  modeled as RS-MDPs is the Risk Sensitive Value Iteration algorithm. This algorithm uses a k factor to model the risk-attitude and it is based on a scalar transformation function by parts and discount factor. In this article, strategies are proposed to optimize this algorithm. First, an analysis about the influence of discount factor and risk factor on the stationary policy and its impact in the convergence time of the algorithm is performed.
From this analysis, optimizations strategies are proposed based on dynamically changing the risk factor and the step-size alpha during the execution of the algorithm; and also the asynchronous updating of the state values is explored. The results of experiments with the Crossing River domain in two distinct rewards scenarios show that: (i) the processing cost in extreme risk policies, for both risk-averse and risk-prone, is high; (ii) a high discount value increases the convergence time and reinforces the chosen risk attitude; (iii) policies with intermediate risk factor values have a low computational cost and show a certain sensitivity to risk based on the discount factor; and (iv) an optimization strategy that dynamically changes the risk factor considering an alpha value relative to k and with assyncronous updating can decrease the convergence time of the algorithm, especially with extreme values of the risk factor.
