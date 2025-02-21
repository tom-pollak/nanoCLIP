# nanoViT

> Minimal ViT implementation from scratch in PyTorch. Inspired by [nanogpt](https://github.com/karpathy/nanoGPT). Designed to be simple and hackable.

Model code: [nanovit/vit.py](nanovit/vit.py).

- Verified by loading CLIP ViT-B/32 model weights.
- ViT from Scratch: (exercise) implement each module from scratch yourself in [Colab](https://colab.research.google.com/github/tom-pollak/nanoViT/blob/main/tutorials/vit_from_scratch.ipynb)

Training script for CIFAR-100: [train_cifar100.py](train_cifar100.py).

- 2.7M params ViT for 200 epochs runs in ~15mins on a 3090, achieves accuracy of 68.5% (ViTs aren't great at small scale datasets).

Also a ConvMixer implementation ([nanovit/convmixer.py](nanovit/convmixer.py)) as a baseline.
