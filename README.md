# Data for analyzing high dimensional generator particle dynamics

In [Effective Dynamics of Generative Adversarial Networks
](https://arxiv.org/abs/2212.04580), we begin by considering low dimensional generator particle clouds, and study their convergence properties as training parameters are modified. 
Here, we perform an analogous high-dimensional experiment, in which a cloud of particles in 784 dimenions are trained against a sample of 100 MNIST datapoints. 

This repo contains sampled data in `.gz` and `.npy` format. 

To analyze it in a convenient way, run the `Unpack_Analyze_Data` notebook in the same folder as the `.npy` data. 
