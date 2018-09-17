# Week 3

* Chapter 6 - Hidden Markov and Maximum Entropy Models:
	* Read Intro (RU), 6.1 (RU), 6.2 (RU), 6.3 (RU), 6.4 (RU), 6.5 (R),  6.6 (intro+6.6.1 RU; 6.6.2+6.6.3 R), 6.7 (R), 6.8 (RU), Summary (RU) , Notes (R)

* Introduction to Machine Learning
	* General:  https://en.wikipedia.org/wiki/Machine_learning
		* Read Intro (RU), 1 (RU), 2 (R), 3 (RU), 4 (RU), 5 (RU)
	* Decision Trees: Powerpoint Lewicki, see attachment	
		* Read completely (RU)
	* Naive Bayes: https://en.wikipedia.org/wiki/Naive_Bayes_classifier
		* Read Intro (RU), 1 (RU), 2 (RU), 5 (R)
	* Kernel methods: http://www.eric-kim.net/eric-kim-net/posts/1/kernel_trick.html	
		* Read Completely (RU, but I don't expect you to reproduce the mathematics)
	* Nearest Neigbour: http://www.math.le.ac.uk/people/ag153/homepage/KNN/OliverKNN_Talk.pdf
		* Read completely (RU)
	* Clustering: https://en.wikipedia.org/wiki/Cluster_analysis
		* Read Intro (RU), 1 (RU), 2 (R), 4 (R)
	* Deep Learning: https://en.wikipedia.org/wiki/Deep_learning
				* Read Intro (RU), 1 (RU), 2 (R), 3 (R), 4 (R), 5 (RU), 8 (RU)										



## Exercises

* If we look at the Viterbi algorithm, we see that the probability of a state at a given position is calculated on the basis of the preceding n states. However, it is claimed that the algorithm takes into account the whole sequence. Explain in your own words (at most 100) how the probability is influenced by the rest of the sequence, i.e. both the positions more than n back and the following positions.
	* **Answer:** The probability of a state at a given position is a cumulative probability based on the n previous states called the previous viterbi path probability. The next path-step is based on how high the incoming probability of the previous paths is. All other paths are discarded accordingly. The whole sequence comes into play at the last step when multiple paths through all time steps have been found. The winning path is then the one with the highest probability which can be found by following the backtrack pointers.
* Explain in your own words (at most 50) how the EM algorithm works. I don’t mean the mathematics, but the underlying concept.
	* **Answer:** The EM (Expectation-Maximization) algorithm is used for maximum likelihood estimation of model parameters. If you are given a dataset, the EM algorithm tries to answer the question which model parameters have the highest likelihood of producing a certain probability distribution given the dataset. The first step of the algorithm is the expectation step (e-step). The expectation step does not incroporate any data but makes a random guess for the parameter values and creates a probability distribution. The maximization step (m-step) then incorporates part of the data and tweaks the parameter values in order to fit the initial distribution. This m-step is repeated until it converges towards a stable distribution and the parameters with the highest likelihood are found.
* Do the Machine Learning exercise.