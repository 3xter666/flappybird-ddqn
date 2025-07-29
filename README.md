# Deep Q-Network (DQN) FlappyBird Project for UIT's CS106 (Artificial Intelligence)

A comprehensive implementation of Deep Q-Network (DQN) and Double DQN algorithms for training an AI agent to play FlappyBird .

## 📋 Project Overview

This project implements and compares two reinforcement learning algorithms:
- **Deep Q-Network (DQN)**: The foundational deep reinforcement learning algorithm
- **Double DQN**: An improved version that addresses the overestimation bias of standard DQN

The agent learns to play FlappyBird through trial and error, using experience replay and target networks to stabilize training.

## 🚀 Features

- **Complete DQN Implementation**: Built from scratch using PyTorch
- **Double DQN Support**: Toggle between standard DQN and Double DQN
- **Experience Replay**: Efficient memory buffer for stable learning
- **Configurable Hyperparameters**: Easy experimentation via YAML configuration
- **Training Visualization**: Real-time plots of rewards and epsilon decay
- **Model Persistence**: Save and resume training sessions
- **Comprehensive Logging**: Detailed training logs with timestamps

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/dqn-flappybird.git
cd dqn-flappybird
```

2. **Create a virtual environment**
```bash
conda create -n dqnenv python=3.9
conda activate dqnenv
```

3. **Install dependencies**
```bash
pip install torch gymnasium matplotlib numpy pyyaml
pip install flappy-bird-gymnasium
```

## 🎯 Usage

### Training a New Model

**Standard DQN:**
```bash
python agent.py flappybird_dqn1 --train
```

**Double DQN:**
```bash
python agent.py flappybird_ddqn1 --train
```

### Resume Training
```bash
python agent.py flappybird_dqn1 --train --resume
```

### Test Trained Model
```bash
python agent.py flappybird_dqn1
```

## ⚙️ Configuration

Edit hyperparameters.yaml to customize training:

## Demo

https://github.com/user-attachments/assets/422d9d46-f3a0-4034-82f5-49d01b6bf701

