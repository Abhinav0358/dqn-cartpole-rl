# dqn-cartpole-rl
A PyTorch implementation of Deep Q-Learning to solve the CartPole-v1 environment using reinforcement learning techniques like experience replay and target networks.

## Getting Started

### 1. Clone the repository (or copy the files)
```bash
git clone <your-repo-url>
cd cartpole_dqn_project
```

### 2. Install dependencies
We recommend using a virtual environment:
```bash
python -m venv env
env\scripts\activate
pip install -r requirements.txt
```

### 3. Train the model
```bash
python train.py
```
- Trains the agent over 500 episodes.
- Plots the reward over time.
- Saves the trained model as `cartpole_dqn.pth`.

### 4. Evaluate 
```bash
python evaluate.py
```
- Loads the trained model.
- Runs and renders the agent interacting with the CartPole environment.
- Press `Ctrl+C` to manually stop the rendering loop.

## Output
- A reward vs. episode plot will be shown.
- Model weights saved to `cartpole_dqn.pth`.
- Visual demonstration of the trained agent balancing the pole.
