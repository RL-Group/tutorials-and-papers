# Deep Reinforcement Learning

## Lecture 1: Markov Decision Processes and Solving Finite Problems

[Video](https://www.youtube.com/watch?v=IL3gVyJMmhg&index=7&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec1.pdf)

## Lecture 2: Policy Gradient Methods

[Video](https://www.youtube.com/watch?v=BB-BhTn6DCM&index=8&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec2.pdf)

* Karpathy's Deep RL Tutorial: [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
* John Schulman's thesis: [Optimizing Expectations: From Deep Reinforcement Learning to Stochastic Computation Graphs](http://joschu.net/docs/thesis.pdf)
* R. J. Williams. [Simple statistical gradient-following algorithms for connectionist reinforcement learning](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf). Machine learning (1992)
* R. S. Sutton, D. McAllester, S. Singh, and Y. Mansour. [Policy gradient methods for reinforcement learning with function approximation](https://web.eecs.umich.edu/~baveja/Papers/PolicyGradientNIPS99.pdf). NIPS. MIT Press, 2000
* Jan Peters, Stefan Schaal. [Policy Gradient Methods for Robotics](http://www-clmc.usc.edu/publications/P/peters-IROS2006.pdf) (2006)
* D. Silver, G. Lever, N. Heess, T. Degris, D. Wierstra, et al. [Deterministic Policy Gradient Algorithms](http://proceedings.mlr.press/v32/silver14.pdf) ICML 2014.
* N. Heess, G. Wayne, D. Silver, T. Lillicrap, Y. Tassa, et al. [Learning Continuous Control Policies by Stochastic Value Gradients](https://arxiv.org/abs/1510.09142) arXiv preprint arXiv:1510.09142 (2015).
* T. Jie and P. Abbeel. [On a connection between importance sampling and the likelihood ratio policy gradient](http://rll.berkeley.edu/~jietang/pubs/nips10_Tang.pdf) Advances in Neural Information Processing Systems.  2010, pp. 1000–1008.
* A3C paper: V. Mnih, A. P. Badia, M. Mirza, A. Graves, T. P. Lillicrap, et al. [Asynchronous methods for deep reinforcement learning](https://arxiv.org/abs/1602.01783) (2016)

## Lecture 3: Q-Function Learning Methods

[Video](https://www.youtube.com/watch?v=Wnl-Qh2UHGg&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX&index=9)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec3.pdf)

* T. Jaakkola, M. I. Jordan, and S. P. Singh.  [On the convergence of stochastic iterative dynamic programming algorithms](https://www.researchgate.net/publication/220499733_On_the_Convergence_of_Stochastic_Iterative_Dynamic_Programming_Algorithms). Neural computation (1994);
* C. J. Watkins and P. Dayan.  [Q-learning](https://link.springer.com/content/pdf/10.1007/BF00992698.pdf). Machine learning (1992).
* M. Riedmiller.  [Neural fitted Q iteration–first experiences with a data efficient neural reinforcement learning method](https://pdfs.semanticscholar.org/2820/01869bd502c7917db8b32b75593addfbbc68.pdf). Machine Learning: ECML 2005. Springer, 2005.

## Lecture 4: Advanced Q-Function Learning Methods

[Video](https://www.youtube.com/watch?v=h1-pj4Y9-kM&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX&index=10)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec4.pdf)

* V. Mnih, K. Kavukcuoglu, D. Silver, A. Graves, I. Antonoglou, et al. [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602) (2013)
* M. G. Bellemare, Y. Naddaf, J. Veness, and M. Bowling.  [The Arcade Learning Environment:  An Evaluation Platform for General Agents](https://arxiv.org/abs/1207.4708) Journal of Artificial Intelligence Research (2013)
*  V. Mnih, K. Kavukcuoglu, D. Silver, A. A. Rusu, J. Veness, et al. [Human-level control through deep reinforcement learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf). Nature (2015)
* H. V. Hasselt.  [Double Q-learning](https://papers.nips.cc/paper/3964-double-q-learning.pdf). NIPS. 2010
* H. Van Hasselt, A. Guez, and D. Silver.  [Deep reinforcement learning with double Q-learning](https://arxiv.org/abs/1509.06461). CoRR, abs/1509.06461 (2015)
* Z. Wang, N. de Freitas, and M. Lanctot.  [Dueling network architectures for deep reinforcement learning](https://arxiv.org/abs/1511.06581). arXiv preprint arXiv:1511.06581 (2015)
* T. Schaul, J. Quan, I. Antonoglou, and D. Silver.  [Prioritized experience replay](https://arxiv.org/abs/1511.05952). arXiv preprint arXiv:1511.05952 (2015)
* D. Silver, A. Huang, C. J. Maddison, et al. [Mastering the
game of Go with deep neural networks and tree search](https://vk.com/doc-44016343_437229031?dl=56ce06e325d42fbc72) (2016)

## Lecture 5: Advanced Policy Gradient Methods: Natural Gradient, TRPO, and More

Schulman: [Video](https://www.youtube.com/watch?v=_t5fpZuuf-4&index=15&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec5.pdf)

Achiam: [Video](https://www.youtube.com/watch?v=ycCtmp4hcUs&list=PLkFD6_40KJIznC9CDbVTjAF2oyt8_VAe3&index=14)
| [Slides](http://rll.berkeley.edu/deeprlcourse/f17docs/lecture_13_advanced_pg.pdf)

* S. Kakade.  [A Natural Policy Gradient](https://papers.nips.cc/paper/2073-a-natural-policy-gradient.pdf) NIPS. 2001
* S. Kakade and J. Langford. [Approximately optimal approximate reinforcement learning](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa09/readings/KakadeLangford-icml2002.pdf). ICML. 2002.
* J. Peters and S. Schaal.  [Natural actor-critic](https://homes.cs.washington.edu/~todorov/courses/amath579/reading/NaturalActorCritic.pdf). Neurocomputing
(2008)
* J. Schulman, S. Levine, P. Moritz, M. I. Jordan, and P. Abbeel.  [Trust Region Policy Optimization](https://arxiv.org/abs/1502.05477). ICML (2015)
* Joshua Achiam, David Held, Aviv Tamar, Pieter Abbeel [Constrained Policy Optimization](https://arxiv.org/abs/1705.10528) (2017)
* John Schulman, Filip Wolski, Prafulla Dhariwal, et al. [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347) (2017)
* Y. Duan, X. Chen, R. Houthooft, J. Schulman, and P. Abbeel. [Benchmarking Deep Reinforcement Learning for Continuous Control](https://arxiv.org/abs/1604.06778). ICML (2016)
* J. Martens and I. Sutskever.  [Training deep and recurrent networks with Hessian-free optimization](http://www.cs.utoronto.ca/~jmartens/docs/HF_book_chapter.pdf).
* Neural Networks:  Tricks of the Trade. Springer, 2012 (book)
* S. Amari and S. C. Douglas [Why Natural Gradient?](http://www.yaroslavvb.com/papers/amari-why.pdf) (1998)
* Jan Peters, Stefan Schaal [Reinforcement learning of motor skills with policy gradients](http://www.kyb.mpg.de/fileadmin/user_upload/files/publications/attachments/Neural-Netw-2008-21-682_4867%5b0%5d.pdf) (2008)
* Nicolas Heess, Dhruva TB, Srinivasan Sriram, et al. [Emergence of Locomotion Behaviours in Rich Environments](https://arxiv.org/abs/1707.02286) (2017)
* Yuhuai Wu, Elman Mansimov, Shun Liao, et al. [Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation](https://arxiv.org/abs/1708.05144) (2017)

## Lecture 6: Variance Reduction for Policy Gradient Methods

[Video](https://www.youtube.com/watch?v=Fauwwkiy-bo&index=16&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec6.pdf)

* A. Y. Ng, D. Harada, and S. Russell. [Policy invariance under reward transformations: Theory and application to reward shaping](http://www.robotics.stanford.edu/~ang/papers/shaping-icml99.pdf). ICML. 1999.
* (Example) I. Mordatch, E. Todorov, and Z. Popović. [Discovery of complex behaviors through contact-invariant optimization](https://homes.cs.washington.edu/~todorov/papers/MordatchSIGGRAPH12.pdf). ACM Transactions on Graphics (TOG) 31.4 (2012), p. 43
* (Example) Y. Tassa, T. Erez, and E. Todorov.  [Synthesis and stabilization of complex behaviors through online trajectory optimization](https://homes.cs.washington.edu/~todorov/papers/TassaIROS12.pdf) Intelligent Robots and Systems (IROS), 2012 IEEE/RSJ International Conference on.  IEEE. 2012, pp. 4906–4913
* J. Schulman, P. Moritz, S. Levine, M. Jordan, and P. Abbeel. [High-dimensional continuous control using generalized advantage estimation](https://arxiv.org/abs/1506.02438) (2015)
* H. Kimura and S. Kobayashi. [An Analysis of Actor/Critic Algorithms Using Eligibility Traces: Reinforcement Learning with Imperfect Value Function](http://www.umiacs.umd.edu/~hal/courses/2016F_RL/Kimura98.pdf) ICML. 1998
* A. Y. Ng and M. Jordan. [PEGASUS: A policy search method for large MDPs and POMDPs](http://www.robotics.stanford.edu/~ang/papers/uai00-pegasus.pdf) (2000)

## Lecture 7: Policy Gradient Methods: Pathwise Derivative Methods and Wrap-up

[Video](https://www.youtube.com/watch?v=IDSA2wAACr0&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX&index=17)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/lec7.pdf)

* T. P. Lillicrap, J. J. Hunt, A. Pritzel, N. Heess, T. Erez, et al. [Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971). arXiv preprint arXiv:1509.02971 (2015)
* (Example) S. Gu, T. Lillicrap, I. Sutskever, and S. Levine.  [Continuous deep Q-learning with model-based acceleration](https://arxiv.org/abs/1603.00748) (2016)
* B. O’Donoghue, R. Munos, K. Kavukcuoglu, and V. Mnih.  [PGQ: Combining policy gradient and Q-learning](https://arxiv.org/abs/1611.01626) (2016)
* Z. Wang, V. Bapst, N. Heess, V. Mnih, R. Munos, et al. [Sample Efficient Actor-Critic with Experience Replay](https://arxiv.org/abs/1611.01224) (2016)
* A. Harutyunyan, M. G. Bellemare, T. Stepleton, and R. Munos.  [Q(λ) with Off-Policy Corrections](https://arxiv.org/abs/1602.04951) 2016
* N. Jiang and L. Li. [Doubly robust off-policy value evaluation for reinforcement learning](https://arxiv.org/abs/1511.03722) 2016
* O. Nachum, M. Norouzi, K. Xu, and D. Schuurmans.  [Bridging the Gap Between Value and Policy Based Reinforcement Learning](https://arxiv.org/abs/1702.08892) (2017)
* T. Haarnoja, H. Tang, P. Abbeel, and S. Levine.  [Reinforcement Learning with Deep Energy-Based Policies](https://arxiv.org/abs/1702.08165) (2017)

## Lecture 8: Exploration

[Video](https://www.youtube.com/watch?v=SfCa1HQMkuw&index=18&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX)
| [Slides](http://rll.berkeley.edu/deeprlcoursesp17/docs/2017.03.20.Exploration.pdf)

* Bubeck, Sébastien, and Nicolo Cesa-Bianchi. [Regret analysis of stochastic and nonstochastic multi-armed bandit problems](https://arxiv.org/abs/1204.5721) arXiv preprint arXiv:1204.5721 (2012).
* Peter Auer, Nicolò Cesa-Bianchi and Paul Fischer, [Finite-Time Analysis of the Multi-Armed Bandit Problem](https://d2925a48-a-62cb3a1a-s-sites.googlegroups.com/site/anrexplora/bibliography/fta-2002.pdf), Mach. Learn., 47 (2002), 235–256
* Daniel Russo, Benjamin Van Roy (2014) [Learning to Optimize via Posterior Sampling](https://arxiv.org/abs/1301.2609). Mathematics of Operations Research
* Chapelle O. and Li, L. [An Empirical Evaluation of Thompson Sampling](https://papers.nips.cc/paper/4321-an-empirical-evaluation-of-thompson-sampling.pdf). NIPS, 2011
* Daniel Russo, Benjamin Van Roy (2014) [Learning to Optimize via Information-Directed Sampling](https://arxiv.org/abs/1403.5556). NIPS
* Kearns & Singh, [Near-Optimal Reinforcement Learning in Polynomial Time](https://www.cis.upenn.edu/~mkearns/papers/KearnsSinghE3.pdf) (1999) 
* Kakade, [On the sample complexity of reinforcement learning](https://homes.cs.washington.edu/~sham/papers/thesis/sham_thesis.pdf) (thesis) (2003)
* Szita, István, and András Lőrincz. [The many faces of optimism: a unifying approach](http://icml2008.cs.helsinki.fi/papers/490.pdf) ICML 2008.
* Moldovan, Teodor Mihai, and Pieter Abbeel. [Safe exploration in 
markov decision processes](https://arxiv.org/abs/1205.4810) arXiv preprint arXiv:1205.4810 (2012).
* Strehl, [PROBABLY APPROXIMATELY CORRECT (PAC) EXPLORATION IN REINFORCEMENT LEARNING](http://cs.brown.edu/~mlittman/theses/strehl.pdf), 2007
* Osband, Ian, and Benjamin Van Roy. [Bootstrapped Thompson Sampling and Deep Exploration](https://arxiv.org/abs/1507.00300) (2015)
* I. Osband, C. Blundell, A. Pritzel, and B. Van Roy [Deep Exploration via Bootstrapped DQN](https://arxiv.org/abs/1602.04621) (2016)
* Yarin Gal, and Zoubin Ghahramani. [Dropout as a Bayesian approximation: Representing model uncertainty in deep learning](https://arxiv.org/abs/1506.02142) (2015).
* Zachary Lipton et al., [Efficient Exploration for Dialogue Policy Learning with BBQ Networks & Replay Buffer Spiking](https://arxiv.org/abs/1608.05081) (2016) 
* Stadie et al., [Incentivizing Exploration In Reinforcement Learning With Deep Predictive Models](https://arxiv.org/abs/1507.00814) (2015) 
* Bellemare et al., [Unifying Count-Based Exploration and Intrinsic Motivation](https://arxiv.org/abs/1606.01868) (2016) 
* Ostrovski et al., [Count-Based Exploration with Neural Density Models](https://arxiv.org/abs/1703.01310) (2017)
* Meire Fortunato, Mohammad Gheshlaghi Azar, et al. [Noisy Networks for Exploration](https://arxiv.org/abs/1706.10295) (2017)
* Houthooft et al., [Variational information maximizing exploration](https://arxiv.org/abs/1605.09674) (2016).
* Duan et al., [RL^2: Fast Reinforcement Learning via Slow Reinforcement Learning](https://arxiv.org/abs/1611.02779) (2017) 
* Wang et al., [Learning to Reinforcement Learn](https://arxiv.org/abs/1611.05763) (2017) 
* Singh, S. P., Barto, A. G., and Chentanez, N. [Intrinsically motivated reinforcement learning](https://papers.nips.cc/paper/2552-intrinsically-motivated-reinforcement-learning.pdf) In NIPS, 2005.
* Oudeyer, Pierre-Yves, and Frederic Kaplan. [How can we define intrinsic motivation?](http://www.pyoudeyer.com/epirob08OudeyerKaplan.pdf) 2008.
* Shakir Mohamed and Danilo J. Rezende, [Variational Information Maximisation for Intrinsically Motivated Reinforcement Learning](https://arxiv.org/abs/1509.08731), ArXiv 2015. (Includes discussion of *common random numbers*)

## Scalability

* Tim Salimans, Jonathan Ho, Xi Chen, Ilya Sutskever [Evolution Strategies as a Scalable Alternative to Reinforcement Learning](https://arxiv.org/abs/1703.03864) (2017)
* Alfredo V. Clemente, Humberto N. Castejón, Arjun Chandra [Efficient Parallel Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1705.04862) (2017)

## Frontiers

* Piotr Mirowski, Razvan Pascanu, Fabio Viola, et al. [Learning to Navigate in Complex Environments](https://arxiv.org/abs/1611.03673) (2017)
* Alexander Sasha Vezhnevets, Simon Osindero, et al. [FeUdal Networks for Hierarchical Reinforcement Learning](https://arxiv.org/abs/1703.01161) (2017)
* Nicolas Heess, Greg Wayne, Yuval Tassa, et al. [Learning and Transfer of Modulated Locomotor Controllers](https://arxiv.org/abs/1610.05182) (2016)
* Théophane Weber, Sébastien Racanière, et al. [Imagination-Augmented Agents for Deep Reinforcement Learning](https://arxiv.org/abs/1707.06203) (2017)
* S. Levine, C. Finn, T. Darrell, and P. Abbeel. [End-to-end training of deep visuomotor policies](https://arxiv.org/abs/1504.00702) (2016)
* Haoran Tang and Tuomas Haarnoja [Learning Diverse Skills via Maximum Entropy Deep Reinforcement Learning](http://bair.berkeley.edu/blog/2017/10/06/soft-q-learning/) (2017)
* Matteo Hessel, Joseph Modayil, et al. [Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298) (2017)
* Max Jaderberg, Volodymyr Mnih, et al. [Reinforcement Learning with Unsupervised Auxiliary Tasks](https://arxiv.org/abs/1611.05397) (2016)
* Aravind Rajeswaran, Vikash Kumar, et al. [Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations](https://arxiv.org/abs/1709.10087) (2017)

## Optimization

* Kerby Shedden [Optimization in statistics](http://dept.stat.lsa.umich.edu/~kshedden/Courses/Stat606/Notes/optim.pdf)
    - It contains a nice section about the *Fisher Information* and its relation to the *Hessian* of the log-likelihood.
    - It also contains a section about *Conjugate-Gradient Methods*.
* Andrew Gibiansky [Conjugate Gradient (article)](http://andrew.gibiansky.com/blog/machine-learning/conjugate-gradient/) (2014)
* Andrew Gibiansky [Hessian Free Optimization (article)](http://andrew.gibiansky.com/blog/machine-learning/hessian-free-optimization/) (2014)
* Andrew Gibiansky [Fully Connected Neural Network Algorithms (article)](http://andrew.gibiansky.com/blog/machine-learning/fully-connected-neural-networks/) (2014)
* Andrew Gibiansky [Gauss Newton Matrix (article)](http://andrew.gibiansky.com/blog/machine-learning/gauss-newton-matrix/) (2014)

## Useful knowledge

* Art B. Owen [Monte Carlo theory, methods and examples](http://statweb.stanford.edu/~owen/mc/) (2013)
    - Useful for learning about **variance reduction**)
