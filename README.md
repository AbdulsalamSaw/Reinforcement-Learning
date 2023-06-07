# reinforcement_learning
## General Introduction:
Q-learning to solve a reinforcement learning problem OpenAI Gym1 is a standard API that provides simulated game environments for RL agents to act according to observations.

## Training
- 1. Choose one game from Gym and initialize it.
- 2. Identify the state space (observation_space) size and the action space size.
- 3. Initialize the Q-Table (observation_space_size, action_space_size)
- 4. Initialize the hyper-parameters as learning_rate = 0.1, discount_factor = 0.5, exploration = 0.1, epochs = 1000
- 5. Your goal is to train the model with different number of epochs to find the best policy such  that it maximizes the rewards and minimizes the number of steps from S to G.
- 6. Conduct training on different epochs settings:
- 7. Start with 1000 epochs and record rewards and steps as indicated in the first table below, followed by 5000 epochs and 10000 epochs for the other two tables.
- 8. Compare the three tables in terms of which one provides better policy.
## Testing and Evaluation
- 1. Repeat The last training with 10000 epochs with different discount_factor values as indicated 
in the table below,
- 2. After each training let the agent play 10 times and compute the average of rewards and the 
average of steps as evaluation metrics.
- 3. Compare results and evaluate which discount factor achieved better rewards and less steps.
