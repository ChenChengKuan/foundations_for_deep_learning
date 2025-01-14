# foundations for deep learning:
1. I emphasize mathematical/conceptual foundations because implementations of ideas(ex. Torch, Tensorflow)
   will keep evolving but the underlying theory must be sound. Anybody with an interest in deep learning 
   can and should try to understand why things work. 
2. I include neuroscience as a useful conceptual foundation for two reasons. First, it may provide inspiration
   for future models and algorithms. Second, the success of deep learning can contribute to useful hypotheses
   and models for computational neuroscience. 
3. Information Theory is also a very useful foundation as there's a strong connection between data compression
and statistical prediction. In fact, data compressors and machine learning models approximate Kolmogorov Complexity
which is the ultimate data compressor. 

You might notice that I haven't emphasized the latest benchmark-beating paper. My reason for this is that a good
theory ought to be scalable which means that it should be capable of explaining why deep models generalise and we
should be able to bootstrap these explanations for more complex models(ex. sequences of deep models(aka RNNs)).
This is how all good science is done. 

### For an excellent historical overview of deep learning, I would recommend reading [Deep Learning in Neural Networks](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/history_of_deep_learning/deep_learning_in_neural_networks.pdf) as well as R. Salakhutdinov's [Deep Learning Tutorials](https://www.youtube.com/watch?v=-SY4-GkDM8g&t=4s). 

## Deep Learning:
1. History:
	* [Deep Learning in Neural Networks: An Overview (J. Schmidhuber. 2015. Neural Networks.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/history_of_deep_learning/deep_learning_in_neural_networks.pdf)
2. Optimisation:
	* [Learning Internal Representations by Error Propagation(D. Rumelhart et al. 1996. MIT Press )](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/learning_internal_representations_by_error_propagation.pdf) 
	* [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift(S. Ioffe. 2015. ICML.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/batch_normalization.pdf)
	* [Weight Normalization (Salimans 2016. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/weight_normalization.pdf)
	* [Bayesian Back-Propagation (W. Buntine & A. Weigend 1991.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/bayesian_backpropagation.pdf)
	* [Credit Assignment through Time: Alternatives to Backpropagation (Y. Bengio. 1993. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/alternatives_to_backprop.pdf)
	* [Adam: A method for Stochastic Optimization (D. Kingma 2015. ICLR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/adam_optimizer.pdf)
	* [Understanding Synthetic Gradients and Decoupled Neural Interfaces(W. Czarnecki 2017. CoRR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/optimisation/synthetic_gradients.pdf)
3. Regularisation:
	* [Dropout: A Simple Way to Prevent Neural Networks from Overfitting (N. Srivastava et al. 2014. Journal of Machine Learning Research.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/regularisation/Dropout_original_paper.pdf)
	* [Why Does Unsupervised Pre-training Help Deep Learning? (D. Erhan et al. 2010. Journal of Machine Learning Research.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/regularisation/unsupervised_pretraining.pdf)
	* [Semi-Supervised Learning with Ladder Networks (A. Rassmus et al. 2015. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/regularisation/ladder_networks.pdf)
4. Inference:
	* [Uncertainty in Deep Learning(Yarin Gal. 2017. University of Cambridge.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/uncertainty_in_deep_learning.pdf)
	* [Mixture Density Networks (Bishop 1994)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/mixture_density_networks.pdf)
	* [Dropout as a Bayesian Approximation(Yarin Gal. 2016. ICML. )](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/dropout_bayesian_approximation.pdf)
	* [Markov Chain Monte Carlo and Variational Inference: Bridging the Gap (Salimans. 2015. ICML.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/MCMC_and_VI.pdf)
	* [Auto-Encoding Variational Bayes (D. Kingma & M. Welling. 2014. ICLR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/auto_encoding_variational_bayes.pdf)
	* [Variational Dropout and the Local Reparameterization Trick (D. Kingma, T. Salimans & M. Welling. 2015. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/variational_dropout.pdf)
	* [Improved Variational Inference with Inverse Autoregressive Flow (D. Kingma, T. Salimans et al. 2017. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/improved_VI_inverse_autoregressive_flows.pdf)
	* [Avoiding pathologies in very deep networks (D. Duvenaud et al. 2014. AISTATS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/avoiding_pathologies_in_very_deep_networks.pdf)
	* [Stochastic Gradient Hamiltonian Monte Carlo (T. Chen. 2014. ICML.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/stochastic_gradient_HMC.pdf)
	* [On Sparse Variational Methods and the Kullback-Leibler Divergence between Stochastic Processes(A. Matthews et al. 2016. AISTATS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/inference/sparse_variational_methods_KL_divergence.pdf)
5. Representation Learning:
	* [Representation Learning: A Review and New Perspectives (Y. Bengio et al. 2013. IEEE Transactions on Pattern Analysis and Machine Intelligence.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/representation_learning/representation_learning_review.pdf)
	* [Deep Learning of Representations for Unsupervised and Transfer Learning (Y. Bengio. 2012. ICML.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/representation_learning/Deep%20Learning_of_Representations_for_Unsupervised_and_Transfer_Learning.pdf)
	* [Learning Invariant Feature Hierarchies (Y. Lecun. 2012. ECCV Workshops.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/representation_learning/learning_invariant_feature_hierarchies.pdf)
5. Deep Generative Models:
	* [Learning Deep Generative Models(Salakhutdinov. 2015. Annual Review of Statistics and Its Application.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/deep_generative_models/deep_generative_models.pdf)
	* [Learning Disentangled Representations with Semi-Supervised Deep Generative Models (N. Siddarth et al. 2017.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/deep_generative_models/learning_disentangled_representations.pdf)
	* [Generative Adversarial Nets (I. Goodfellow et al. 2014. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/deep_generative_models/generative_adversarial_networks.pdf)
6. Continual Learning:
	* [Long Short-Term Memory (S. Hochreiter & J. Schmidhuber. 1997. Neural Computation.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/continual_learning/long_short_term_memory.pdf)
	* [Overcoming catastrophic forgetting in neural networks (J. Kirkpatrick et al. 2017. PNAS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/continual_learning/overcoming_catastrophic_forgetting.pdf)
7. Hyperparameter Optimization:
	* [Taking the Human Out of the Loop: A Review of Bayesian Optimization (B. Shahriari et al. 2016. Proceedings of the IEEE.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/hyperparameter_optimization/taking_humans_out_of_the_loop.pdf)
	* [Convolution by Evolution (C. Fernando et al. 2016. GECCO.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/hyperparameter_optimization/convolution_by_evolution.pdf)

## Mathematics:
1. Optimisation:
	* [Simple Explanation of the No-Free-Lunch Theorem and Its Implications (Y. Ho. 2002. Journal of optimization theory and applications.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/No_Free_Lunch.pdf)
	* [The Loss Surfaces of Multilayer Networks(Y LeCun et al. 2015. AISTATS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/loss_surfaces_of_multilayer_networks.pdf)
	* [The loss surface of deep and wide neural networks(Q. Nguyen 2017)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/loss_surfaces_of_deep_neural_networks.pdf)
	* [Qualitatively Characterizing Neural Network Optimization Problems (I. Goodfellow et al. 2015. ICLR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/qualitatively_characterizing_loss_surfaces.pdf)
	* [The Physical Systems behind Optimization (L. Yang et al. 2017.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/physical_systems_behind_optimization.pdf)
	* [A Differential Equation for Modeling Nesterov’s Accelerated Gradient Method(W. Su 2016. Journal of Machine Learning Research.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/nesterov_differential_equation.pdf)
	* [Electron-Proton dynamics in deep learning(Zhang 2017. CoRR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/electron_proton_dynamics.pdf)
	* [Sharp Minima Can Generalize for Deep Nets (L. Dinh et al. 2017. ICML.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/optimisation/sharp_minima_can_generalize.pdf)

2. Representation Learning:
	* [A mathematical theory of Deep Convolutional Neural Networks for Feature Extraction(Wiatowski 2016. CoRR.)]()
	* [Spectral Representations for Convolutional Neural Networks(Rippl 2015. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/representation_learning/spectral_representations_CNN.pdf)

3. Learning theory:
	* [Distribution-Specific Hardness of Learning Neural Networks(Shamir 2017. CoRR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/distribution_specific_hardness_of_learning.pdf)
	* [Lessons from the Rademacher Complexity for Deep Learning(Sokolic 2016.ICLR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/rademacher_complexity_for_deep_networks.pdf)
	* [On the ability of neural nets to express distributions (H. Lee et al. 2017.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/the_ability_of_neural_nets_to_express_distributions.pdf)
	* [Empirical Risk Minimization for Learning Theory(Vapnik 1991. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/empirical_risk_minimization.pdf)
	* [Dataset Shift(Storkey 2013)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/dataset_shift.pdf)
	* [On the ability of neural nets to express distributions （H. Lee, R. Ge, T. Ma, A. Risteski & S. Arora, 2017)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/the_ability_of_neural_nets_to_express_distributions.pdf)
	* [Probably Approximately Correct Learning (R. Schapire. COS 511: Foundations of Machine Learning. 2006.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/pac_learning.pdf)
	* [Rademacher Complexity (M. Balcan. CS 8803 - Machine Learning Theory. 2011.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_theory/rademacher_complexity.pdf)

4. Learning behaviour:
	* [Exact solutions to the nonlinear dynamics of learning in deep linear neural networks (A. Saxe et al. CoRR. 2013)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/mathematics/learning_behaviour/linear_NN_learning_dynamics.pdf)


## Information Theory:
1. [Shannon Information and Kolmogorov Complexity (Grunwald 2010)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/information_theory/shannon_information_kolmogorov_complexity.pdf)
2. [Discovering Neural Nets with Low Kolmogorov Complexity(Schmidhuber 1997. Neural Networks.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/information_theory/discovering_nets_with_low_complexity.pdf)
3. [Opening the black box of Deep Neural Networks via Information (Schwartz-Ziv 2017.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/information_theory/dnn_black_box_information.pdf)                                   

## Neuroscience:
1. [Towards an integration of deep learning and neuroscience(Marblestone 2016. Frontiers in Computational Neuroscience.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/deep_learning_and_neuroscience.pdf)
2. [Equilibrium Propagation(Scellier 2016. Frontiers in Computational Neuroscience.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/equilibrium_propagation.pdf)
3. [Towards Biologically plausible deep learning(Bengio 2015. CoRR.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/biologically_plausible_deeplearning.pdf)
4. [Random synaptic feedback weights support error backpropagation for deep learning(Lillicrap 2016. Nature communications.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/random_synaptic_feedback_backprop.pdf)
5. [Towards deep learning with spiking neurons(Mesnard 2016. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/deep_learning_spiking_neurons.pdf)
6. [Towards deep learning with segregated dendrites(Guergiuev 2017)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/deep_learning_segregated_dendrites.pdf)
7. [Variational learning for recurrent spiking networks(Rezende 2011. NIPS.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/variational_learning_for_recurrent_spiking_networks.pdf)
8. [A view of Neural Networks as dynamical systems(Cessac 2009. I. J. Bifurcation and Chaos)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/neural_nets_as_dynamical_systems.pdf)
9. [Convolutional network layers map the function of the human visual system (M. Eickenberg. 2016. NeuroImage Elsevier.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/Convolutional_network_layers_map_the_function_of_the_human_visual_system.pdf)
10. [Cortical Algorithms for Perceptual Grouping (P. Roelfsema. 2006. Annual Review of Neuroscience.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/neuroscience/cortical_algorithms_for_perceptual_grouping.pdf)

## Statistical Physics:
1. [Phase Transitions of Neural Networks (W. Kinzel. 1997. Universitat Weiburg.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/statistical_physics/phase_transitions_neural_networks.pdf)
2. [Convolutional Neural Networks Arise From Ising Models and Restricted Boltzmann Machines (S. Pai)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/statistical_physics/ising_models.pdf)
3. [Non-equilibrium statistical mechanics: From a paradigmatic model to biological transport (T. Chou et al. 2011.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/statistical_physics/non_equilibrium_physics.pdf)
4. [Replica Theory and Spin Glasses (F. Morone et al. 2014.)](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/statistical_physics/replica_theory_spin_glasses.pdf)

**Note 1:** There are many who love quoting Richard Feynman and Albert Einstein whenever it suits their purpose. However, Feynman's popular quote: 
'What I cannot create, I do not understand' has been taken out of context by many AI researchers. There are many things we can build
that we can't understand and many things we can't build that we understand very well. Take any non-constructive proof in mathematical physics
for example. From this it follows that it's important to create, but it's essential to understand. In fact, I think it makes more sense to 
consider the perspective of Marie Curie: "Nothing in life is to be feared, it is only to be understood. Now is the time to understand more, 
so that we may fear less." 

**Note 2:** This is a work in progress. I have more papers to add. 

