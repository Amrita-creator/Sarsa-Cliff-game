# SARSA on CliffWalking

## Project Overview
This project explores the implementation of the SARSA (State–Action–Reward–State–Action) reinforcement learning algorithm to solve the CliffWalking environment. The objective is to train an agent that can navigate from the starting point to the goal while avoiding the cliff.


## Environment
The CliffWalking environment is a grid-based world where the agent must move from the start position to the goal. The bottom row contains a cliff, and stepping into it results in a large negative reward and resets the agent to the start position.

Through repeated interactions, the agent learns to avoid the cliff and follow a safer path along the grid.

## Learning Approach
The project uses the SARSA algorithm, an on-policy reinforcement learning method. The agent updates its knowledge of the environment based on the current state, action taken, reward received, and the next state-action pair.

To balance exploration and exploitation, the agent follows an epsilon-greedy strategy, allowing it to explore different actions while gradually favoring better ones.

## Results
After training over multiple episodes, the agent learns to navigate the environment safely and reach the goal while avoiding the cliff. The trained agent demonstrates how reinforcement learning can help systems learn optimal behavior through experience.

## Key Takeaways
- Understanding the fundamentals of reinforcement learning
- Learning how on-policy methods like SARSA work
- Observing how agents improve through interaction with an environment
- Gaining practical insight into exploration vs exploitation

## Future Improvements
- Compare SARSA with other reinforcement learning algorithms
- Experiment with different exploration strategies
- Apply reinforcement learning to more complex environments

## Author
Amrita Chaturvedi  
B.Tech Computer Science Engineering  
Interested in Machine Learning and Reinforcement Learning