# Temporal-feature-aggregation-network
## Implementation contains：
**model_3d**
**model_gru**
**model_transformer**
**model_tan**

## Requirements

The code is based on **Python 3**. 
    
## How to run



Train original DQN:

	python dqn.py --env env_name
    
Train soft DARQN:

	python drqn_soft.py --env env_name
    
Train global DQN:

	python dqn_global.py --env env_name

Train local DQN:

	python dqn_local.py --env env_name
