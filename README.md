**A list of Python-based MCMC packages**.
Also here's a nice list
of [MCMC algorithms](https://m-clark.github.io/docs/ld_mcmc/).


## abcpmc

> A Python Approximate Bayesian Computing (ABC) Population Monte Carlo (PMC)
implementation based on Sequential Monte Carlo (SMC) with Particle Filtering
techniques.
>
> Features:
> * Entirely implemented in Python and easy to extend
> * Follows Beaumont et al. 2009 PMC algorithm
> * Parallelized with muliprocessing or message passing interface (MPI)
> * Extendable with k-nearest neighbour (KNN) or optimal local covariance
matrix (OLCM) pertubation kernels (Fillipi et al. 2012)

<img src="./img/github.png" width="20" height="20"> [Repo](
https://github.com/jakeret/abcpmc) | 
<img src="./img/docs.png" width="20" height="20"> [Docs](
http://abcpmc.readthedocs.org/)
<br>


## astroABC

> astroABC is a Python implementation of an Approximate Bayesian Computation
Sequential Monte Carlo (ABC SMC) sampler for parameter estimation.
>
> Key features
> * Parallel sampling using MPI or multiprocessing
> * MPI communicator can be split so both the sampler, and simulation launched
by each particle, can run in parallel
> * A Sequential Monte Carlo sampler (see e.g. Toni et al. 2009, Beaumont et
al. 2009, Sisson & Fan 2010)
> * A method for iterative adapting tolerance levels using the qth quantile of
the distance for t iterations (Turner & Van Zandt (2012))
> * Scikit-learn covariance matrix estimation using Ledoit-Wolf shrinkage for
singular matrices
> * A module for specifying particle covariance using method proposed by Turner
& Van Zandt (2012), optimal covariance matrix for a multivariate normal
perturbation kernel, local covariance estimate using scikit-learn KDTree method
for nearest neighbours (Filippi et al 2013) and a weighted covariance 
(Beaumont et al 2009)
> * Restart files output frequently so an interrupted run can be resumed at any
iteration
> * Output and restart files are backed up every iteration
> * User defined distance metric and simulation methods
> * A class for specifying heterogeneous parameter priors
> * Methods for drawing from any non-standard prior PDF e.g using Planck/WMAP
chains
> * A module for specifying a constant, linear, log or exponential tolerance
level
> * Well-documented examples and sample scripts

<img src="./img/github.png" width="20" height="20"> [Repo](
https://github.com/EliseJ/astroABC) | 
<img src="./img/docs.png" width="20" height="20"> [Docs](
https://github.com/EliseJ/astroABC/wiki) |
<img src="./img/art.png" width="20" height="20"> [Article](
https://arxiv.org/abs/1608.07606)


## bmcmc

> bmcmc is a general purpose mcmc package which should be useful for Bayesian
data analysis. It uses an adaptive scheme for automatic tuning of proposal
distributions. It can also handle hierarchical Bayesian models via
Metropolis-Within-Gibbs scheme.

* Repo: https://github.com/sanjibs/bmcmc/
* Docs: https://bmcmc.readthedocs.io/en/latest/
* Article: [Markov Chain Monte Carlo Methods for Bayesian Data Analysis in
Astronomy, Sharma (2017)](https://arxiv.org/abs/1706.01629)

## [CosmoABC](https://github.com/COINtoolbox/CosmoABC)

## [DNest4](https://github.com/eggplantbren/DNest4)

## [ELFI](https://github.com/elfi-dev/elfi)

## emcee

> emcee is an MIT licensed pure-Python implementation of Goodman & Weare’s
[Affine Invariant Markov chain Monte Carlo (MCMC) Ensemble
sampler](http://msp.berkeley.edu/camcos/2010/5-1/p04.xhtml)

* Docs: http://dfm.io/emcee/current/, https://emcee.readthedocs.io/en/latest/
* Repo: https://github.com/dfm/emcee
* Article: [emcee: The MCMC Hammer, Foreman-Mackey et al.
(2012)](https://arxiv.org/abs/1202.3665)

## hmc

> A simple Hamiltonian MCMC sampler.

* Repo: https://github.com/bd-j/hmc

## [hoppMCMC](https://github.com/kerguler/hoppMCMC)

## [kombine](http://pages.uoregon.edu/bfarr/kombine/index.html)

## [MCcubed](http://pcubillos.github.io/MCcubed/)

## Nested Sampling

> Nested sampling estimates directly how the likelihood function relates to
prior mass. The evidence (alternatively the marginal likelihood, marginal
density of the data, or the prior predictive) is immediately obtained by
summation. It is the prime result of the computation, and is accompanied by an
estimate of numerical uncertainty. Samples from the posterior distribution are
an optional by-product, obtainable for any temperature. The method relies on
sampling within a hard constraint on likelihood value, as opposed to the
softened likelihood of annealing methods. Progress depends only on the shape of
the "nested" contours of likelihood, and not on the likelihood values. This
invariance (over monotonic re-labelling) allows the method to deal with a class
of phase-change problems which effectively defeat thermal annealing.

* [Official site](http://www.inference.phy.cam.ac.uk/bayesys/)
* Repo: https://github.com/js850/nested_sampling
* Docs: http://js850.github.io/nested_sampling/
* Original article: [Nested sampling for general Bayesian computation, John Skilling (2006)](http://projecteuclid.org/euclid.ba/1340370944)
* Article where the algorithm is used: [A Galaxy Model from 2MASS Star Counts in the Whole Sky Including the Plane; Polido, Jablonski & Lépine (2013)](http://arxiv.org/abs/1308.6238)
* [Wikipedia entry](https://en.wikipedia.org/wiki/Nested_sampling_algorithm)
* [Poster comparing with annealing](http://www.mrao.cam.ac.uk/~steve/malta2009/images/nestposter.pdf)

## [nestle](http://kylebarbary.com/nestle/)

## [NUTS](https://github.com/mfouesneau/NUTS)

## pgmpy

> pgmpy is a python library for working with Probabilistic Graphical Models.

* Repo: https://github.com/pgmpy/pgmpy
* Docs (and list of algorithms supported): http://pgmpy.org/
* Examples: https://github.com/pgmpy/pgmpy/tree/dev/examples
* Basic tutorial: https://github.com/pgmpy/pgmpy_notebook
* Article: [MCMC: Hamiltonian Monte Carlo and No-U-Turn
Sampler](http://khalibartan.github.io/MCMC-Hamiltonian-Monte-Carlo-and-No-U-Turn-Sampler/)

## ptemcee

> ...is a fork of Daniel Foreman-Mackey's wonderful emcee to implement parallel
tempering more robustly. As far as possible, it is designed as a drop-in
replacement for emcee. If you're trying to characterise awkward, multi-modal
probability distributions, then ptemcee is your friend.

* Repo: https://github.com/willvousden/ptemcee
* Docs: http://ptemcee.readthedocs.io/en/latest/

## [PyDREAM](https://github.com/LoLab-VU/PyDREAM)

## pyhmc

> Hamiltonian Monte Carlo or Hybrid Monte Carlo (HMC) is a Markov chain Monte
Carlo (MCMC) algorithm. Hamiltonian dynamics can be used to produce distant
proposals for the Metropolis algorithm, thereby avoiding the slow exploration
of the state space that results from the diffusive behaviour of simple
random-walk proposals. It does this by taking a series of steps informed by
first-order gradient information. This feature allows it to converge much more
quickly to high-dimensional target distributions compared to simpler methods
such as Metropolis, Gibbs sampling (and derivatives).

* Repo: https://github.com/rmcgibbo/pyhmc
* Docs: https://pythonhosted.org/pyhmc/index.html

## PyJAGS

> PyJAGS provides a Python interface to JAGS, a program for analysis of
Bayesian hierarchical models using Markov Chain Monte Carlo (MCMC) simulation.

* Repo: https://github.com/tmiasko/pyjags
* Docs: https://pyjags.readthedocs.io/en/latest/
* Blog article: https://martynplummer.wordpress.com/2016/01/11/pyjags/

## PyMC3

> PyMC3 is a probabilistic programming module for Python that allows users
to fit Bayesian models using a variety of numerical methods, most notably
Markov chain Monte Carlo (MCMC) and variational inference (VI). Its flexibility
and extensibility make it applicable to a large suite of problems. Along with
core model specification and fitting functionality, PyMC3 includes
functionality for summarizing output and for model diagnostics.

* Docs: http://docs.pymc.io/intro.html
* Repo: https://github.com/pymc-devs/pymc3
* Tutorials:
  1. [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)
  1. [Using PyMC3](http://people.duke.edu/~ccc14/sta-663-2017/19A_PyMC3.html)
  1. [Tutorial 5a: Parameter estimation with Markov chain Monte Carlo](http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/tutorials/t5a_mcmc.html)
* Recommended book: [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
* Recommended book: [Statistical Rethinking with Python and PyMC3](https://github.com/aloctavodia/Statistical-Rethinking-with-Python-and-PyMC3)
* Examples: https://stats.stackexchange.com/questions/119879/how-to-interpret-autocorrelation-plot-in-mcmc (autocorrelation)
* Article: [Probabilistic Programming in Python using PyMC, Salvatier et al. (2015)](https://arxiv.org/abs/1507.08050)

## [pymcmc](https://github.com/gmcgoldr/pymcmc)

## [py-mcmc](https://pypi.org/project/py-mcmc/)

## PyStan

> PyStan provides an interface to Stan, a package for Bayesian inference using
the No-U-Turn sampler, a variant of Hamiltonian Monte Carlo.*

* Stan's homepage: http://mc-stan.org/about/
* PyStan's homepage: https://pystan.readthedocs.io/en/latest/index.html
* Examples: https://stats.stackexchange.com/questions/162857/managing-high-autocorrelation-in-mcmc (autocorrelation)

## Sampyl

> Sampyl is a Python library implementing Markov Chain Monte Carlo (MCMC)
samplers in Python. It’s designed for use in Bayesian parameter estimation
and provides a collection of distribution log-likelihoods for use in
constructing models.

* Repo: https://github.com/mcleonard/sampyl/
* Docs: http://matatat.org/sampyl/index.html
* Example: http://matatat.org/ab-testing-with-sampyl.html

## [simpleabc](https://github.com/rcmorehead/simpleabc)

## [SPOTPY](https://github.com/thouska/spotpy)

## [XHMC](https://arxiv.org/abs/1601.00225)
