---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## Journal publications
<b> Estimation of convex supports from noisy measurements</b>
[[pdf]](http://danayang.github.io/files/ConvexBodyEstimation.pdf) <br> 
Victor-Emmanuel Brunel, Jason M. Klusowski and Dana Yang.<br> 
<i>Bernoulli</i>, to appear, 2020.
<details>
  <summary>Abstract</summary>
  A popular class of problem in statistics deals with estimating the support of a density from $n$ observations drawn at random from a $d$-dimensional distribution. The one-dimensional case reduces to estimating the end points of a univariate density. In practice, an experimenter may only have access to a noisy version of the original data. Therefore, a more realistic model allows for the observations to be contaminated with additive noise.

In this paper, we consider estimation of convex bodies when the additive noise is distributed according to a multivariate Gaussian distribution, even though our techniques could easily be adapted to other noise distributions. Unlike standard methods in deconvolution that are implemented by thresholding a kernel density estimate, our method avoids tuning parameters and Fourier transforms altogether. We show that our estimator, computable in $(O(\ln n))^{(d-1)/2}$ time, converges at a rate of $O_d(\log\log n/\sqrt{\log n})$ in Hausdorff distance, in accordance with the polylogarithmic rates encountered in Gaussian deconvolution problems. Part of our analysis also involves the optimality of the proposed estimator. We provide a lower bound for the minimax rate of estimation in Hausdorff distance that is $\Omega_d(1/\log^2 n)$.
</details>

<b> Posterior asymptotic normality for an individual coordinate in high-dimensional linear regression</b>
[[journal]](https://projecteuclid.org/euclid.ejs/1569290683)
[[pdf]](http://danayang.github.io/files/betaone.pdf)<br>
Dana Yang.<br> 
<i>Electronic Journal of Statistics</i>, 13(2), pages 3082-3094, 2019.
<details>
  <summary>Abstract</summary>
  It is well known that high-dimensional procedures like the LASSO provide biased estimators of parameters in a linear model. In a 2014 paper Zhang and Zhang showed how to remove this bias by means of a two-step procedure. We show that de-biasing can also be achieved by a one-step estimator, the form of which inspires the development of a Bayesian analogue of the frequentists' de-biasing techniques.
</details>
<b> Estimating the coefficients of a mixture of two linear regressions by expectation maximization</b>
[[journal]](https://ieeexplore.ieee.org/abstract/document/8606170)
[[pdf]](http://danayang.github.io/files/mix_linear.pdf)<br> 
Jason M. Klusowski, Dana Yang and W.D. Brinda.<br> 
<i>IEEE Transactions on Information Theory</i>, 65(6), pages 3515-3524, 2019.
<details>
  <summary>Abstract</summary>
  We give convergence guarantees for estimating the coefficients of a symmetric mixture of two linear regressions by expectation maximization (EM). In particular, we show that the empirical EM iterates converge to the target parameter vector at the parametric rate, provided the algorithm is initialized in an unbounded cone. In particular, if the initial guess has a sufficiently large cosine angle with the target parameter vector, a sample-splitting version of the EM algorithm converges to the true coefficient vector with high probability. Interestingly, our analysis borrows from tools used in the problem of estimating the centers of a symmetric mixture of two Gaussians by EM.

We also show that the population EM operator for mixtures of two regressions is anti-contractive from the target parameter vector if the cosine angle between the input vector and the target parameter vector is too small, thereby establishing the necessity of our conic condition. Finally, we give empirical evidence supporting this theoretical observation, which suggests that the sample based EM algorithm may not converge to the target vector when initial guesses are drawn accordingly. Our simulation study also suggests that the EM algorithm performs well even under model misspecification (i.e., when the covariate and error distributions violate the model assumptions).
</details>
<b> H&ouml;lder's identity</b>
[[journal]](https://www.sciencedirect.com/science/article/pii/S0167715219300148)
[[pdf]](http://danayang.github.io/files/Holder.pdf)<br> 
W.D. Brinda, Jason M. Klusowski and Dana Yang.
<i>Statistics & Probability Letters</i>, Volume 148, Pages 150-154, 2019.
<details>
  <summary>Abstract</summary>
  We clarify that H&ouml;lder's inequality can be stated more generally than is often realized.  This is an immediate consequence of an analogous information-theoretic identity which we call <i>H&ouml;lder's identity</i>. We also explain Andrew R. Barron's original use of the identity.
</details>
<b> Two dimensional Yau-Hausdorff distance with applications on comparison of DNA and protein sequences</b> (undergraduate thesis)
[[journal]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0136577)
[[pdf]](http://danayang.github.io/files/Yau_Hausdorff.pdf) <br> 
Kun Tian, Xiaoqian (Dana) Yang, Qin Kong, Changchuan Yin, Rong L. He and Stephen S-T Yau.<br> 
<i>PloS one</i>, 10(9), 2015.
<details>
  <summary>Abstract</summary>
  Comparing DNA or protein sequences plays an important role in the functional analysis of genomes. Despite many methods available for sequences comparison, few methods retain the information content of sequences. We propose a new approach, the Yau-Hausdorff method, which considers all translations and rotations when seeking the best match of graphical curves of DNA or protein sequences. The complexity of this method is lower than that of any other two dimensional minimum Hausdorff algorithm. The Yau-Hausdorff method can be used for measuring the similarity of DNA sequences based on two important tools: the Yau-Hausdorff distance and graphical representation of DNA sequences. The graphical representations of DNA sequences conserve all sequence information and the Yau-Hausdorff distance is mathematically proved as a true metric. Therefore, the proposed distance can preciously measure the similarity of DNA sequences. The phylogenetic analyses of DNA sequences by the Yau-Hausdorff distance show the accuracy and stability of our approach in similarity comparison of DNA or protein sequences. This study demonstrates that Yau-Hausdorff distance is a natural metric for DNA and protein sequences with high level of stability. The approach can be also applied to similarity analysis of protein sequences by graphic representations, as well as general two dimensional shape matching.
</details>

## Conference publications
<b> Optimal query complexity for private sequential learning against eavesdropping</b>
[[arXiv]](https://arxiv.org/abs/1909.09836) <br> 
Jiaming Xu, Kuang Xu and Dana Yang.
<i>AISTATS</i>, 2021.
<details>
  <summary>Abstract</summary>
  We study the query complexity of a learner-private sequential learning problem, motivated
by the privacy and security concerns due to eavesdropping that arise in practical applications
such as pricing and Federated Learning. A learner tries to estimate an unknown scalar value,
by sequentially querying an external database and receiving binary responses; meanwhile, a
third-party adversary observes the learner’s queries but not the responses. The learner’s goal is
to design a querying strategy with the minimum number of queries (optimal query complexity)
so that she can accurately estimate the true value, while the eavesdropping adversary even with
the complete knowledge of her querying strategy cannot.

We develop new querying strategies and analytical techniques and use them to prove tight
upper and lower bounds on the optimal query complexity. The bounds almost match across
the entire parameter range, substantially improving upon existing results. We thus obtain a
complete picture of the optimal query complexity as a function of the estimation accuracy and
the desired levels of privacy. We also extend the results to sequential learning models in higher
dimensions, and where the binary responses are noisy. Our analysis leverages a crucial insight
into the nature of private learning problem, which suggests that the query trajectory of an
optimal learner can be divided into distinct phases that focus on pure learning versus learning
and obfuscation, respectively.
</details>

<b> The cost-free nature of optimally tuning Tikhonov regularizers and other ordered smoothers</b>
[[pdf]](http://danayang.github.io/files/cost_free.pdf) <br> 
Pierre C. Bellec and Dana Yang.<br> 
<i>ICML</i>, 2020.
<details>
  <summary>Abstract</summary>
  We consider the problem of selecting the best estimator among a family of Tikhonov regularized estimators, or, alternatively, to select a linear combination of these regularizers that is as good as the best regularizer in the family. Our theory reveals that if the Tikhonov regularizers share the same penalty matrix with different tuning parameters, a convex procedure based on $Q$-aggregation achieves the mean square error of the best estimator, up to a small error term no larger than $C\sigma^2$, where $\sigma^2$ is the noise level and $C>0$ is an absolute constant. Remarkably, the error term does not depend on the number of estimators as long as they share the same penalty matrix, i.e., it applies to any grid of tuning parameters, no matter how large the cardinality of the grid is. This reveals the surprising "cost-free" nature of optimally tuning Tikhonov regularizers, in striking contrast with the existing literature on aggregation of estimators where one typically has to pay a cost of $\sigma^2\log(M)$ where $M$ is the number of estimators in the family. The result holds, more generally, for any family of ordered linear smoothers. This encompasses Ridge regression as well as Principal Component Regression. The result is extended to the problem of aggregating Tikhonov regularizers with different penalty matrices.
</details>
<b>Consistent recovery threshold of hidden nearest neighbor graphs (extended abstract) </b>[[pdf]](http://danayang.github.io/files/NN_COLT.pdf) <br> 
Jian Ding, Yihong Wu, Jiaming Xu and Dana Yang.<br> 
<i>COLT</i>, 2020.
<details>
  <summary>Abstract</summary>
  Motivated by applications such as discovering strong ties in social networks and assembling genome subsequences in biology, we study the problem of recovering a hidden $2k$-nearest neighbor (NN) graph in an $n$-vertex complete graph, whose edge weights are independent and distributed according to $P_n$ for edges in the hidden $2k$-NN graph and $Q_n$ otherwise. The special case of Bernoulli distributions corresponds to a variant of the Watts-Strogatz small-world graph. We focus on two types of asymptotic recovery guarantees as $n\to \infty$: (1) exact recovery: all edges are classified correctly with probability tending to one; (2) almost exact recovery: the expected number of misclassified edges is $o(nk)$. We show that the maximum likelihood estimator achieves (1) exact recovery for $2 \le k \le n^{o(1)}$ if $\lim\inf\frac{2\alpha_n}{\log n}>1$; (2) almost exact recovery for $1\le k\le o\left(\frac{\log n}{\log\log n}\right)$ if $\liminf \frac{kD(P_n||Q_n)}{\log n}>1$, where $\alpha_n \triangleq -2 \log \int \sqrt{d P_n d Q_n}$ is the R&eacute;nyi divergence of order $\frac{1}{2}$ and $D(P_n||Q_n)$ is the Kullback-Leibler divergence. Under mild distributional assumptions, these conditions are shown to be information-theoretically necessary for any algorithm to succeed. A key challenge in the analysis is the enumeration of $2k$-NN graphs that differ from the hidden one by a given number of edges. We also analyze several computationally efficient algorithms are provide sufficient conditions under which they ahieve exact/almost exact recovery. In particular, we develop a polynomial-time algorithm that attains the threshold for exact recovery under the small-world model.
</details>

## Preprints
<b>Consistent recovery threshold of hidden nearest neighbor graphs </b>[[arXiv]](https://arxiv.org/abs/1911.08004) <br> 
Jian Ding, Yihong Wu, Jiaming Xu and Dana Yang.<br> 
Under minor revision at <i>IEEE Transactions on Information Theory</i>, 2019.
<details>
  <summary>Abstract</summary>
  Motivated by applications such as discovering strong ties in social networks and assembling genome subsequences in biology, we study the problem of recovering a hidden $2k$-nearest neighbor (NN) graph in an $n$-vertex complete graph, whose edge weights are independent and distributed according to $P_n$ for edges in the hidden $2k$-NN graph and $Q_n$ otherwise. The special case of Bernoulli distributions corresponds to a variant of the Watts-Strogatz small-world graph. We focus on two types of asymptotic recovery guarantees as $n\to \infty$: (1) exact recovery: all edges are classified correctly with probability tending to one; (2) almost exact recovery: the expected number of misclassified edges is $o(nk)$. We show that the maximum likelihood estimator achieves (1) exact recovery for $2 \le k \le n^{o(1)}$ if $\lim\inf\frac{2\alpha_n}{\log n}>1$; (2) almost exact recovery for $1\le k\le o\left(\frac{\log n}{\log\log n}\right)$ if $\liminf \frac{kD(P_n||Q_n)}{\log n}>1$, where $\alpha_n \triangleq -2 \log \int \sqrt{d P_n d Q_n}$ is the R&eacute;nyi divergence of order $\frac{1}{2}$ and $D(P_n||Q_n)$ is the Kullback-Leibler divergence. Under mild distributional assumptions, these conditions are shown to be information-theoretically necessary for any algorithm to succeed. A key challenge in the analysis is the enumeration of $2k$-NN graphs that differ from the hidden one by a given number of edges.
</details>
<b> Rapid mixing of a Markov chain for the exponentially weighted aggregation estimator</b>
[[arXiv]](https://arxiv.org/abs/1909.11773) <br> 
David Pollard and Dana Yang.
<i>arXiv:1909.11773</i>, 2019.
<details>
<summary>Abstract</summary>
The Metropolis-Hastings method is often used to construct a Markov chain with a given $\pi$ as its stationary distribution. The method works even if $\pi$ is known only up to an intractable constant of proportionality. Polynomial time convergence results for such chains (rapid mixing) are hard to obtain for high dimensional probability models where the size of the state space potentially grows exponentially with the model dimension. In a Bayesian context, Yang, Wainwright and Jordan (2016) (=YWJ) used the path method to prove rapid mixing for high dimensional linear models.
This paper proposes a modification of the YWJ approach that simplifies the theoretical argument and improves the rate of convergence. The new approach is illustrated by an application to an exponentially weighted aggregation estimator. 
</details>
<b> Fair quantile regression</b>
[[arXiv]](https://arxiv.org/abs/1907.08646) <br> 
Dana Yang, John Lafferty, and David Pollard.
<i>arXiv:1909.08646</i>, 2019.
<details>
  <summary>Abstract</summary>
  Quantile regression is a tool for learning conditional distributions. In this paper we study quantile regression in the setting where a protected attribute is unavailable when fitting the model. This can lead to "unfair" quantile estimators for which the effective quantiles are very different for the subpopulations defined by the protected attribute. We propose a procedure for adjusting the estimator on a heldout sample where the protected attribute is available. The main result of the paper is an empirical process analysis showing that the adjustment leads to a fair estimator for which the target quantiles are brought into balance, in a statistical sense that we call $\sqrt{n}$-fairness. We illustrate the ideas and adjustment procedure on a dataset of $200{,}000$ live births, where the objective is to characterize the dependence of the birth weights of the babies on demographic attributes of the birth mother; the protected attribute is the mother's race.
</details>


## Miscellaneous manuscripts
<b> Remarks on Kneip's linear smoothers</b>
[[arXiv]](https://arxiv.org/abs/1405.1744)  <br> 
S&ouml;ren R. K&uuml;nzel, David Pollard and Dana Yang.
<i>arXiv:1405.1744</i>, 2014.
<details>
  <summary>Abstract</summary>
  We were trying to understand the analysis provided by Kneip (1994, Ordered Linear Smoothers). In particular we wanted to persuade ourselves that his results imply the oracle inequality stated by Tsybakov (2014, Lecture 8). This note contains our reworking of Kneip's ideas.
</details>

## Thesis
<b>A few topics in statistics</b>
[[pdf]](http://danayang.github.io/files/thesis.pdf)
<br style="line-height:1px">
(Much improved versions of all the chapters are available on arXiv)