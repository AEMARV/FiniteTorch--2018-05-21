# FiniteTorch

Opened 2018-05-21.

PyTorch layers for a Bayesian linear map parameterized by a KL divergence.

`layers/klmodules.py` defines `BayesFunc`. `bayesgrad.py` compares the exact gradient of that layer with a sampled gradient. `run.py`, `trainvalid/`, and `models/` are the training harness. CUDA kernels are in `cuda/`.
