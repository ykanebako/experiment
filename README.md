# A trivial experiment

## Run the notebook

On Linux, use Python 3.12 and Pipenv to install the locked dependencies:

```sh
pipenv sync
pipenv run jupyter lab different_label.ipynb
```

The environment uses Python 3.12 so the notebook stack can install Soup Sieve
4.0 or later. It does not support the original Python 3.7 environment.
The lock was generated and checked on Linux x86_64. It contains Linux-only
PyTorch dependencies and does not install on native Windows or macOS.

The lock passed a dependency-resolution dry run. The notebook was run separately
with the CPU build of PyTorch; a complete install of the locked CUDA stack was
not tested.
