# FiniteTorch

Opened 2018-05-21.

PyTorch layers for a Bayesian linear map parameterized by a KL divergence.

`layers/klmodules.py` defines `BayesFunc`. `bayesgrad.py` compares the exact gradient of that layer with a sampled gradient. `run.py`, `trainvalid/`, and `models/` are the training harness. CUDA kernels are in `cuda/`.

## Papers

- Amir Emad Marvasti, Ehsan Emad Marvasti, Ulas Bagci, and Hassan Foroosh. [Maximum Probability Theorem: A Framework for Probabilistic Machine Learning](https://www.computer.org/csdl/journal/ai/2021/03/09446965/1ua0q5D18Yg). *IEEE Transactions on Artificial Intelligence*, 2021.
- Amir Emad Marvasti, Ehsan Emad Marvasti, G. Atia, Ulas Bagci, and Hassan Foroosh. [Rediscovering Deep Neural Networks Through Finite-State Distributions](https://arxiv.org/abs/1809.10073). *IEEE Access*.
- Amir Emad Marvasti, Ehsan Emad Marvasti, and Ulas Bagci. [Out of Distribution Detection, Generalization, and Robustness Triangle with Maximum Probability Theorem](https://arxiv.org/abs/2203.12145). *ICECCME*, 2022.
