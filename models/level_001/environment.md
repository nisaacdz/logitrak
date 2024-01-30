### Level 1: Basic Forward Movement

#### Training Environment:
- **Path World:** A linear path representing the delivery route.
- **Location:** A single delivery point located along the path.
- **Agent:** A basic agent (delivery vehicle) positioned at the start of the path.

#### Training Objectives:
1. **Forward Movement:** Teach the agent to move forward along the path towards the delivery point.

#### Training Parameters:
- **Observation Space:** Current position of the agent on the path.
- **Action Space:** Move forward action.
- **Rewards:** Positive reward for reaching the delivery point, negative reward for any other action.

#### Curriculum Level Specifics:
- **Initial State:** Agent starts at the beginning of the path.
- **Episode Termination:** An episode ends when the agent reaches the delivery point.

#### Training Process:
- **Episodic Training:** Train the agent in episodes, focusing on moving forward along the path.
- **Reward System:** Provide positive rewards for reaching the delivery point and negative rewards for other actions.
- **Model Checkpoints:** Save the model checkpoint after successful training at this level.

#### Evaluation:
- **Success Metrics:** Measure the agent's success rate in reaching the delivery point.
- **Progress Monitoring:** Observe the improvement in the agent's forward movement skills over multiple training episodes.
