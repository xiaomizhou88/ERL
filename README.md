# ERL
Exploration based Reinforcement Learning

# PixelCNN DQN
A tensorflow implementation of ['Count-Based Exploration with Neural Density Model'](https://arxiv.org/abs/1703.01310). It uses PixelCNN to measure the sparsity of one state and give corresponding bonus.

# DQN
DQN is modified from ['DQN-tensorflow'](https://github.com/devsisters/DQN-tensorflow)

# PixelCNN
PixelCNN is modified from ['gated-pixel-cnn'](https://github.com/jakebelew/gated-pixel-cnn)

# How to use ?
`python main.py --mode top-pixelcnn`
or
`python main.py --mode pixelcnn`

The autoencoder mode is not verified yet.


# References
- [PixelCNN++ paper](https://openreview.net/pdf?id=BJrFC6ceg) with [Code](https://github.com/jakebelew/gated-pixel-cnn)
- [DQN Code](https://github.com/devsisters/DQN-tensorflow)
