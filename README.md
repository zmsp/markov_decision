# MARKOV decision making 

[notebook/markov_experiments.ipynb](https://github.com/zmsp/markov_decision/blob/master/notebooks/markov_experiments.ipynb) file contains all the experiments.

# Quick Start
1. On a python environment run `pip3 install -r requirements.txt`
2. Run `jupter notebook` from the notebook directory
3. Profit


# About
I come up with two interesting MDPs and explain why they are interesting. The first MDP has a small number of states and the second MDP has a large number of states. I solve each MDP using value iteration and policy iteration. I choose to define convergence as the point where the value of the MDP converges to within a certain threshold. I expect that the MDP with a large number of states will take more iterations to converge than the MDP with a small number of states. I also expect that the MDP with a large number of states will converge to the same answer as the MDP with a small number of states. I pick my favorite reinforcement learning algorithm and use it to solve the two MDPs. I compare the performance of the reinforcement learning algorithm to the cases where I knew the model, rewards, and so on. I choose to use an exploration strategy that is known to work well.

1. two interesting MDPs were chosen
2. Each problems were solved using value iteration as well as policy iteration.
3. Problems were solved using qlearning. 

## Problems chosen
- In the frozen lake problem, the agent is faced with a grid of tiles, each of which is either frozen or thawed. The agent must move around the grid and try to reach the goal without falling into a hole.

- In the forest management problem, the agent is faced with a grid of trees, each of which can be chopped down or left alone. The agent must move around the grid and try to reach the goal without chopping down all the trees.

##  Quick analysis of the result:

- Value iteration is better for frozen lake because it doesn't rely on the model environment. 
- Policy iteration is better for forest management because of the smaller state space. 
- Q-learning works well for frozen lake because it can learn from experience.


# Graphs
Most of these graphs have gamma for X value. What is gamma you asked?
A gamma value in a Markov Decision Process is a discount factor that determines how much importance an agent places on future rewards.

### Forest management

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20%20Policy%20iteration-%20Convergence.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20%20Policy%20iteration-%20Rewards.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20%20Value%20iteration-%20Convergence.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20%20Value%20iteration-%20Rewards.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20Policy%20iteration-%20Problem%20size%20vs%20time.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20Policy%20iteration-%20execution%20time.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Forest%20Value%20iteration-%20execution%20time.png?raw=true)



### Frozen Lake
![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Policy%20iteration-%20Convergence.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Policy%20iteration-%20Problem%20size%20vs%20time.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Policy%20iteration-%20Rewards.png?raw=true)

![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Policy%20iteration-%20execution%20time.png?raw=trueg)


![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Value%20iteration-%20Rewards.png?raw=true)


![alt text](https://github.com/zmsp/markov_decision/blob/master/notebooks/outputs/Frozen%20lake%20Value%20iteration-%20execution%20time.png?raw=true)


