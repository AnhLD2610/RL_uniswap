# Uniswap Environment Training

This project provides a reinforcement learning environment based on Uniswap and allows for training an agent using historical data.

## Setup

Make sure you have all the required dependencies installed. Then you can start training the agent.

## Usage

### 1. Define the Environment

The environment is defined in `uniswap_env.py`. It simulates trading in the Uniswap protocol based on historical data.

### 2. Start Training

To start the training process, run:

```bash
python main.py
```

This script initializes the environment and begins training the model using the specified configurations.

### 3. Adjusting the Dataset Size

To use a larger dataset, you can modify the `max_rows` parameter in the data preparation function:

```python
df = prepare_data(df, max_rows=1000)
```

Change `1000` to a higher value to increase the number of samples used in training.

