# Mnist-nd

This repo provided the adjusted code to generate mnist-nd, the benchmarking dataset to disentangle the influence of dimensionality on the clustering performance.

Workshop Paper : [MNIST-Nd: a set of naturalistic datasets to benchmark clustering across dimensions](https://arxiv.org/abs/2410.16124)
```
@misc{turishcheva2024mnistndsetnaturalisticdatasets,
      title={MNIST-Nd: a set of naturalistic datasets to benchmark clustering across dimensions}, 
      author={Polina Turishcheva and Laura Hansel and Martin Ritzert and Marissa A. Weis and Alexander S. Ecker},
      year={2024},
      eprint={2410.16124},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2410.16124}, 
}
```

### Acknowledgements
* We adjusted the PyTorch version of the following repo to train a m-VAE -https://github.com/jariasf/GMVAE.git
* We also adjusted code from here for early stopping - https://github.com/Bjarten/early-stopping-pytorch
* For TMM we used the implementation from - https://github.com/jlparki/mix_T
