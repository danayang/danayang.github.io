---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## Preprints
<br>
<b>Consistent recovery threshold of hidden nearest neighbor graphs </b> <br> 
Jian Ding, Yihong Wu, Jiaming Xu and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1911.08004) preprint arXiv:1911.08004</i>, 2019.
<details>
  <summary>Abstract</summary>
  Motivated by applications such as discovering strong ties in social networks and assembling genome subsequences in biology, we study the problem of recovering a hidden $2k$-nearest neighbor (NN) graph in an $n$-vertex complete graph, whose edge weights are independent and distributed according to $P_n$ for edges in the hidden $2k$-NN graph and $Q_n$ otherwise. The special case of Bernoulli distributions corresponds to a variant of the Watts-Strogatz small-world graph. We focus on two types of asymptotic recovery guarantees as $n\to \infty$: (1) exact recovery: all edges are classified correctly with probability tending to one; (2) almost exact recovery: the expected number of misclassified edges is $o(nk)$. We show that the maximum likelihood estimator achieves (1) exact recovery for $2 \le k \le n^{o(1)}$ if $\lim\inf\frac{2\alpha_n}{\log n}>1$; (2) almost exact recovery for $1\le k\le o\left(\frac{\log n}{\log\log n}\right)$ if $\liminf \frac{kD(P_n||Q_n)}{\log n}>1$, where $\alpha_n \triangleq -2 \log \int \sqrt{d P_n d Q_n}$ is the R&eacute;nyi divergence of order $\frac{1}{2}$ and $D(P_n||Q_n)$ is the Kullback-Leibler divergence. Under mild distributional assumptions, these conditions are shown to be information-theoretically necessary for any algorithm to succeed. A key challenge in the analysis is the enumeration of $2k$-NN graphs that differ from the hidden one by a given number of edges.
</details>
<br>
<b> Optimal query complexity for private sequential learning</b> <br> 
Jiaming Xu and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1909.09836) preprint arXiv:1909.09836</i>, 2019.
<details>
  <summary>Abstract</summary>
  Motivated by privacy concerns in many practical applications such as Federated Learning, we study a stylized private sequential learning problem: a learner tries to estimate an unknown scalar value, by sequentially querying an external database and receiving binary responses; meanwhile, a third-party adversary observes the learner's queries but not the responses. The learner's goal is to design a querying strategy with the minimum number of queries (optimal query complexity) so that she can accurately estimate the true value, while the adversary even with the complete knowledge of her querying strategy cannot. Prior work has obtained both upper and lower bounds on the optimal query complexity, however, these upper and lower bounds have a large gap in general. In this paper, we construct new querying strategies and prove almost matching upper and lower bounds, providing a complete characterization of the optimal query complexity as a function of the estimation accuracy and the desired levels of privacy. We also extend the results to the sequential learning model in higher dimensions.
</details>
<br>
<b> Rapid mixing of a Markov chain for the exponentially weighted aggregation estimator</b> <br> 
David Pollard and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1909.11773) preprint arXiv:1909.11773</i>, 2019.
<details>
  <summary>Abstract</summary>
  The Metropolis-Hastings method is often used to construct a Markov chain with a given $\pi$ as its stationary distribution. The method works even if $\pi$ is known only up to an intractable constant of proportionality. Polynomial time convergence results for such chains (rapid mixing) are hard to obtain for high dimensional probability models where the size of the state space potentially grows exponentially with the model dimension. In a Bayesian context, Yang, Wainwright and Jordan (2016) (=YWJ) used the path method to prove rapid mixing for high dimensional linear models.
This paper proposes a modification of the YWJ approach that simplifies the theoretical argument and improves the rate of convergence. The new approach is illustrated by an application to an exponentially weighted aggregation estimator. 
</details>
<br>
<b> Fair quantile regression</b> <br> 
John Lafferty, David Pollard and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1907.08646) preprint arXiv:1909.08646</i>, 2019.
<details>
  <summary>Abstract</summary>
  Quantile regression is a tool for learning conditional distributions. In this paper we study quantile regression in the setting where a protected attribute is unavailable when fitting the model. This can lead to "unfair" quantile estimators for which the effective quantiles are very different for the subpopulations defined by the protected attribute. We propose a procedure for adjusting the estimator on a heldout sample where the protected attribute is available. The main result of the paper is an empirical process analysis showing that the adjustment leads to a fair estimator for which the target quantiles are brought into balance, in a statistical sense that we call $\sqrt{n}$-fairness. We illustrate the ideas and adjustment procedure on a dataset of $200{,}000$ live births, where the objective is to characterize the dependence of the birth weights of the babies on demographic attributes of the birth mother; the protected attribute is the mother's race.
</details>
<br>
<b> The cost-free nature of optimally tuning Tikhonov regularizers and other ordered smoothers</b> <br> 
Pierre C. Bellec and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1905.12517) preprint arXiv:1905.12517</i>, 2019.
<details>
  <summary>Abstract</summary>
  We consider the problem of selecting the best estimator among a family of Tikhonov regularized estimators, or, alternatively, to select a linear combination of these regularizers that is as good as the best regularizer in the family. Our theory reveals that if the Tikhonov regularizers share the same penalty matrix with different tuning parameters, a convex procedure based on $Q$-aggregation achieves the mean square error of the best estimator, up to a small error term no larger than $C\sigma^2$, where $\sigma^2$ is the noise level and $C>0$ is an absolute constant. Remarkably, the error term does not depend on the number of estimators as long as they share the same penalty matrix, i.e., it applies to any grid of tuning parameters, no matter how large the cardinality of the grid is. This reveals the surprising "cost-free" nature of optimally tuning Tikhonov regularizers, in striking contrast with the existing literature on aggregation of estimators where one typically has to pay a cost of $\sigma^2\log(M)$ where $M$ is the number of estimators in the family. The result holds, more generally, for any family of ordered linear smoothers. This encompasses Ridge regression as well as Principal Component Regression. The result is extended to the problem of aggregating Tikhonov regularizers with different penalty matrices.
</details>
<br>
<b> Estimation of convex supports from noisy measurements</b> <br> 
Victor-Emmanuel Brunel, Jason M. Klusowski and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1804.09879) preprint arXiv:1804.09879, under revision for Bernoulli</i>, 2018.
<details>
  <summary>Abstract</summary>
  A popular class of problem in statistics deals with estimating the support of a density from $n$ observations drawn at random from a $d$-dimensional distribution. The one-dimensional case reduces to estimating the end points of a univariate density. In practice, an experimenter may only have access to a noisy version of the original data. Therefore, a more realistic model allows for the observations to be contaminated with additive noise.

In this paper, we consider estimation of convex bodies when the additive noise is distributed according to a multivariate Gaussian distribution, even though our techniques could easily be adapted to other noise distributions. Unlike standard methods in deconvolution that are implemented by thresholding a kernel density estimate, our method avoids tuning parameters and Fourier transforms altogether. We show that our estimator, computable in $(O(\ln n))^{(d-1)/2}$ time, converges at a rate of $O_d(\log\log n/\sqrt{\log n})$ in Hausdorff distance, in accordance with the polylogarithmic rates encountered in Gaussian deconvolution problems. Part of our analysis also involves the optimality of the proposed estimator. We provide a lower bound for the minimax rate of estimation in Hausdorff distance that is $\Omega_d(1/\log^2 n)$.
</details>
<br>
<b> Remarks on Kneip's linear smoothers</b> <br> 
S&ouml;ren R. K&uuml;nzel, David Pollard and Dana Yang.
<i>[arXiv](https://arxiv.org/abs/1405.1744) preprint arXiv:1405.1744</i>, 2014.
<details>
  <summary>Abstract</summary>
  We were trying to understand the analysis provided by Kneip (1994, Ordered Linear Smoothers). In particular we wanted to persuade ourselves that his results imply the oracle inequality stated by Tsybakov (2014, Lecture 8). This note contains our reworking of Kneip's ideas.
</details>


## Publications
<br>
<b> Posterior asymptotic normality for an individual coordinate in high-dimensional linear regression</b> <br>
Dana Yang.
<i>Electronic Journal of Statistics</i>, 13(2), pages 3082-3094, 2019. 
[[journal]](https://projecteuclid.org/euclid.ejs/1569290683)
[[pdf]](http://danayang.github.io/files/betaone.pdf)
<details>
  <summary>Abstract</summary>
  It is well known that high-dimensional procedures like the LASSO provide biased estimators of parameters in a linear model. In a 2014 paper Zhang and Zhang showed how to remove this bias by means of a two-step procedure. We show that de-biasing can also be achieved by a one-step estimator, the form of which inspires the development of a Bayesian analogue of the frequentists' de-biasing techniques.
</details>
<br>
<b> Estimating the coefficients of a mixture of two linear regressions by expectation maximization</b> <br> 
Jason M. Klusowski, Dana Yang and W.D. Brinda.
<i>IEEE Transactions on Information Theory</i>, 65(6), pages 3515-3524, 2019.
<details>
  <summary>Abstract</summary>
  
</details>
<br>
<b> H&ouml;lder's identity</b> <br> 
W.D. Brinda, Jason M. Klusowski and Dana Yang.
<i>Statistics & Probability Letters</i>, Volume 148, Pages 150-154, 2019.
<details>
  <summary>Abstract</summary>
  
</details>
<br>
<b> Two dimensional Yau-Hausdorff distance with applications on comparison of DNA and protein sequences</b> <br> 
Kun Tian, Xiaoqian Yang, Qin Kong, Changchuan Yin, Rong L. He and Stephen S-T Yau.
<i>PloS one</i>, 10(9), 2015.
<details>
  <summary>Abstract</summary>
  
</details>