# An Introduction to Variational Inference and Probabilistic Programming with Pyro-PPL - Lab

This repository contains materials for two computer science graduate-level labs on variational inference and probabilistic programming held in 2022/23 at a public university in Italy. The students are expected to know Python well, and to have fully grasped the theory during lectures behind Bayesian inference, MCMC and variational inference. The two lab sessions are then aimed at presenting how these algorithms are implemented and used on real-world problems.

Feel free to use this material however you please.

## Contents

There are two separate lectures, each having a ~2-3 hour approximate duration. The first, contained in [PyroLecture](PyroLecture.ipynb) introduces Pyro-PPL, while the second, contained in [MiniPyroLecture](MiniPyroLecture.ipynb), delves into Pyro's internals through the [Mini-Pyro](https://pyro.ai/examples/minipyro.html) example. Also, they are intended to be presented in this particular order. The notebooks themselves contain a fair amount of text describing the topics, but their intended use is by an experienced instructor so many details present in the code are intended to be verbally described during the lecture and are omitted from the descriptions.

Outline of the Pyro lecture:

1. A quick refresher on probabilistic machine learning
2. The fundamental components of a probabilistic programming language
3. A quick refresher on the variational autoencoder model (VAE)
4. The VAE implemented in pure PyTorch
5. The VAE implemented in Pyro
6. Discussion

Outline of the Mini-Pyro lecture:

1. The fundamental components of a probabilistic programming language - setting goals
2. Presenting the Bayesian linear regression (BLL) model applied to the "Rugged Terrain" problem
3. A detailed walkthrough of the Mini-Pyro code
4. Applying Mini-Pyro to the "Rugged Terrain" problem
5. Applying Pyro to the "Rugged Terrain" problem
6. Comparing the results to Hamiltonian Monte Carlo
7. Discussion


## How to Run

First make sure that you have Python and Jupyter installed, and then launch Jupyter. Any version of Python greater or equal than 3.6 should work.

Otherwise, and this might be a better choice for a class of students, load the notebook into Google Colab and run it there.

## References

[1] Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). Latent dirichlet allocation. Journal of machine Learning research, 3(Jan), 993-1022.

[2] Blei, D. M., Kucukelbir, A., & McAuliffe, J. D. (2017). Variational inference: A review for statisticians. Journal of the American statistical Association, 112(518), 859-877.

[3] Ranganath, R., Gerrish, S., & Blei, D. (2014, April). Black box variational inference. In Artificial intelligence and statistics (pp. 814-822). PMLR.

[4] Nunn, N., & Puga, D. (2012). Ruggedness: The blessing of bad geography in Africa. Review of Economics and Statistics, 94(1), 20-36.

[5] Kingma, D. P., & Welling, M. (2013). Auto-encoding variational bayes. arXiv preprint arXiv:1312.6114.

*Code and examples adapted from*:

https://pyro.ai/examples/intro_long.html

https://pyro.ai/examples/svi_part_i.html

https://pyro.ai/examples/svi_part_iii.html

https://pyro.ai/examples/minipyro.html

https://pyro.ai/examples/bayesian_regression.html

https://pyro.ai/examples/bayesian_regression_ii.html
