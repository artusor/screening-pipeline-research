# Screening Pipeline Research
###### Jun 2023 - Aug 2023
Theoretical and exploratory study of multi-stage screening pipelines involving a large number of candidates such as those used for drugs or material synthesis recipes. Touched upon the reinforcement learning problem of the multi-armed bandit (exploration vs exploitation) by running simulation studies that yielded the reward distribution of different mathematical filtering policies, some of which Bayesian, with varying stage covariance structures. From the simulation studies, evaluated the performance of each policy through its respective mean reward with standard deviation, and found that only 2 distinct distribution shapes (of reward with respect to policy type) resulted from 6 stage covariance structure classes, regardless of sample size. The stage covariance structures belonging to one of these two distinct distribution shape categories shared two characteristics: a mathematical closeness between two specific stages, and, unlike the other covariance structure classes studied, the best-performing policy was simply skipping the pipeline and randomly selecting candidates to evaluate at the final stage such as in a real-life experiment. These findings could help future researchers leverage the known stage covariance structure of their own studies by selecting the best corresponding screening policy.
