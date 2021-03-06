# Multi-Agent Reinforcement Learning for Liquidation Strategy Analysis
Source code for paper:Multi-agent reinforcement learning for liquidation strategy analysis accepted by ICML 2019 AI in Finance: Applications and Infrastructure for Multi-Agent Learning.

* ![screenshot](Multi-agent.png)

## Abstract

Liquidation is the process of selling a large number of shares of one stock sequentially within a given time frame, taking into consideration the costs arising from market impact and a trader's risk aversion. The main challenge in optimizing liquidation is to find an appropriate modeling system that can incorporate the complexities of the stock market and generate practical trading strategies. In this paper, we propose to use multi-agent deep reinforcement learning model, which better captures high-level complexities comparing to various machine learning methods, such that agents can learn how to make best selling decisions. 

## Proposed Methods

* We theoretically analyze the Almgren and Chriss model and extend its fundamental mechanism so it can be used as the multi-agent trading environment. Our work builds the foundation for future multi-agent environment trading analysis. 
* We analyze the cooperative and competitive behaviors between agents by adjusting the reward functions for each agent, which overcomes the limitation of single-agent reinforcement learning algorithms. 
* We simulate trading and develop optimal trading strategy with practical constraints by using reinforcement learning method, which shows the capabilities of reinforcement learning methods in solving realistic liquidation problems.




