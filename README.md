Exploring how using *state-injections* inside a parametrized quantum linear optical circuit can increase its dimensional expressivity, by looking at the Jacobian rank of the output density matrix -- c.f. https://arxiv.org/abs/2410.01572.

# Photonic state injection -- dimensional-expressivity

Warning! The quantum optics library `qoptcraft` does not support `python>=3.12`, so use version `3.11`.

Example setup commands that should work:

```shell
conda create -n qml python=3.11
conda activate qml
pip install jupyter qoptcraft seaborn

# Then install pytorch however you like
# (see the helper at https://pytorch.org/), e.g. for linux-cpuonly: 
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

# Finally, open the notebook with:
jupyter-lab
```
