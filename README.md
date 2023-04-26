# The effects of Present Bias on Migration Decision: Insights from a Markov Decision Process Approach

### Abstract:

> The reasons for migration decision are extremely complex. Classical models of migration reason that these decisions are driven by push-pull mechanisms. However,
these models often fail to explain why two seemingly identical individuals with similar 
push and pull factors may produce differing migration behaviours. To address
this discrepancy, we turn to behavioural economics for insight. In this paper, I
develop a dynamic micro-migration choice model in which present-biased agents
attempt to solve their migration decision problems under uncertainty. This model
expands on previous approaches by incorporating repeated migration decisions, accounting 
for failed migration attempts, and introducing present bias through hyperbolic 
discounting. Utilizing computational methods, I demonstrate that when
migration costs are considered, the probability of migration decreases with present
bias for agents with identical observable characteristics.

### Full references for Code:

#### The intuition for our hyperbolic discounting appraoch is borrowed from:

Fedus, W et al. (2019) “Hyperbolic discounting and learning over multiple horizons”. arXiv preprint arXiv:1902.06865

Code:
[Google Brain - Hyperbolic discounting and learning over multiple horizons authors: Fedus, William and Gelada, Carles and Bengio, Yoshua and Bellemare, Marc G and Larochelle, Hugo](https://github.com/google-research/google-research/tree/master/hyperbolic_discount)

and the corresponding [paper](https://arxiv.org/pdf/1902.06865.pdf)

#### The general MDP appraoch and Value iteration/epsilon greedy algorithms have been based on:

Sutton, R.S. and Barto, A.G. (2015) Reinforcement learning: An introduction. Massachusetts: MIT Press Ltd.

Further Resources for code:

The [Quant Econ guides on Dynamic Programming within Economics](https://quantecon.org/notebooks/) have been of immense help for design of the MDP.

https://stackoverflow.com/questions/61519294/implementing-q-value-iteration-from-scratch

https://wandb.ai/wandb/common-ml-errors/reports/How-To-Use-GPU-with-PyTorch---VmlldzozMzAxMDk 

https://towardsdatascience.com/implement-value-iteration-in-python-a-minimal-working-example-f638907f3437

https://www.geeksforgeeks.org/epsilon-greedy-algorithm-in-reinforcement-learning/

https://stackoverflow.com/questions/56726682/problems-with-coding-markov-decision-process
