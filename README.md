# VenterGPT

Implementation of kaparthy's `nanoGPT` to make an angry GPT.

## Disclaimer

I do not own the model. Please refer to the original repository [link to nanoGPT](https://github.com/karpathy/nanoGPT).

## Why Jupyter Notebook?

I did experiment with the model in a python file locally and ran it with CPU and mps (as recommended by the original repository). However, this was still very slow locally. I wanted to speed up the process as well as not make my poor macbook suffer. So I decided to use Google Colab Pro with premium GPU runtime.

## How to use

1. Open the ipynb file in Google Colab and run it.
2. Make sure the runtime is set to GPU (better if it is premium GPU).
3. If you encounter any errors while running it, please refer to the comments made in each block.

## PLEASE READ this before running each file

1. For `shakespeare-prac.ipynb`, change dtype to float16 in `train.py`.
2. For `openweb-prac.ipynb`, make sure you have enough disk space. The default Colab disk space is 30GB, so it will be likely you need to upgrade to Colab Pro for more disk space.
