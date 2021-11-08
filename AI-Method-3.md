# AI Method 3 - Approximate Q-Learning

Your notes about this part of the project, including acknowledgement, comments, strengths and limitations, etc.

# Table of Contents
- [Reinforcement Learning](#governing-strategy-tree)
  * [Motivation](#motivation)
  * [Application](#application)
  * [Trade-offs](#trade-offs)     
     - [Advantages](#advantages)
     - [Disadvantages](#disadvantages)
  * [Future improvements](#future-improvements)

## Reinforcement Learning
The machine learning technique maximizes the accumulated rewards by training the agent to take actions. An approximate Q-learning agent comprehends the environment by perceiving the observations of the current state, and therefore acts to increase the reward points.

### Motivation  
The Approximate Q-Learning agent is being used in this project as an attacking agent. In this approach, the agent is provided with a set of observations from each state, using which the agent will choose an action which provides maximized rewards.

We have implemented Approximate Q-Learning algorithm as an attacking agent. The observations taken per state are 
  * Score of successor state
  * Nearest food
  * Distance between the ghost and the pacman
  * Possible action per state
  * Distance to the safe zone if the enemy is near.

Each observation is stored in a list along with its weights. Later, the Q(state,action) is represented as g(feature1(state,action),feature1(state,action),...,featureN(state,action)). The weights are updated by adding the weights of the current state and the difference in weights of discounted successor state and current state.

The pacman will prefer the action with maximized weight value for each state.

[Back to top](#table-of-contents)

### Application  

[Back to top](#table-of-contents)

### Trade-offs  

#### *Advantages*  
 * Reinforcement learning agent autodidacts, even in the absence of a training database. 
 * More complex problems can be solved with the help of Reinforcement learning algorithm. 
 * The agents also learns from the pervious observations made by another agent.

#### *Disadvantages*
* Learning process takes much time.
* The agent requires lots of data and computation, in order to provide better results. 
* The agent doesn't know the whole environment, as it depends mainly on the previous state and the successor state.
* Too much of learning process, reduces the accuracy of the algorithm

[Back to top](#table-of-contents)

### Future improvements
* The pacman agent, cannot handle the state where it is sandwiched between 2 ghosts. The situation can be avoided by teaching the pacman not to go around the traps.
* The pacman doesn't react to the power pellets as of now. 
* We can also implement some other strategies that when the pacman collected the power pellet, it needs to collect the food with higher distance
* We need to implement defence mechanism for the Pacman agent, only offense mechanism is not enough to improve the winning probabilities.

[Back to top](#table-of-contents)
