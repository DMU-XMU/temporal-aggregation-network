# Temporal-feature-aggregation-network
Implementation contains：
1. a2c with 3D_conv
2. a2c with GRU
3. a2c with Transformer
4. a2c with TAN
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
