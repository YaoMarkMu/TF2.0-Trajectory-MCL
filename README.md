# Tensorflow 2.0 Version of Trajectory MCL

TensorFlow2.0 implementation of ["Trajectory-wise Multiple Choice Learning for Dynamics Generalization in Reinforcement Learning"](https://arxiv.org/abs/2010.13303) (NeurIPS 2020).

Since the TF1.0 code was too painful for researchers to follow, this repo upgrades the T-CML code to the more friendly TF2.0 version for further development and research by researchers

## Instructions

Install required packages with below commands:

```
conda create -n tmcl python=3.6
pip install -r requirements.txt
```

Train and evaluate agents:

```
python -m run_scripts.run_tmcl --dataset [hopper/slim_humanoid/halfcheetah/cripple_ant] --normalize_flag
```

