# Commit History Overview:
- a259469 Refactor insights on Normal Distribution for clarity and coherence (ktanguy, 2025-02-23)
- 8f8f351 Normal Distribution comparisons and alternative contexts (nitekar, 2025-02-23)
- 8da5f25 insights on Normal Distribution comparisons and alternative contexts (nitekar, 2025-02-23)
- a2aaf4b uncommented the for loop for better understanding of the insights (Dennis Mwai Kimiri, 2025-02-23)
- c28e7df Finished the insights (Dennis Mwai Kimiri, 2025-02-23)
- 0305b33 wrote the insights (Dennis Mwai Kimiri, 2025-02-23)
- 05d0caa Created using Colab (Dennis Mwai Kimiri, 2025-02-23)
- c70148d chore: add empty markdown cells to add  normal.ipynb for future documentations (ktanguy, 2025-02-23)
- 6923dd9 normal distribution (ktanguy, 2025-02-23)
- 51c7130 Gradient Descent using for loop, scipy, and statsmodels (Dennis Mwai Kimiri, 2025-02-23)
- 7e821a0 Normal distribution (nitekar, 2025-02-23)
- 6b58da0 feat:bayesian (Keza, 2025-02-23)
- fb68c56 setting up probability data and importing numpy package (buwituze, 2025-02-23)
- 8308092 Initial commit (Keza, 2025-02-23)

Insights Gained:
-Tanguy Kwizera

Throughout this task, I enhanced my comprehension of Normal Distribution, discovering how the mean and standard deviation influence the curve. I also acquired knowledge of Bayesian Probability, observing how evidence modifies earlier assumptions. Executing Gradient Descent illuminated the process of optimizing model parameters across iterations. Working with my group improved my collaboration and ability to solve problems. In general, this experience successfully linked theoretical concepts with hands-on coding. 😊🚀 

Insights Gained:
-Dennis Mwai


I tried using a for loop initially to understand the computation of the gradient descent and visualize the variation in the parameters after the subsequent iterations. It took me down a rabbit hole to understand convergence and divergence. I tried the various solutions offered when the values of m and b are so large that an overflow error occurs. It included reducing the learning rate which allowed it to get close to the 1.5 value computed by the ols and scipy as a fixed learning rate makes the for loop diverge. From my research, scipy is encouraged because it is a more stabilized optimization technique. Scipy adjusts the learning rate automatically preventing overshooting or a too slow convergence. Scipy also utilizes better algorithms such as the BFGS to compute- it is more stable. It also incorporates momentum like Adam and RMS Prop, in its computations. Momentum is a technique that smooths out updates in gradient descent by incorporating previous gradients into the current update. This prevents oscillations and improves convergence, especially in cases where gradients vary significantly which ties to the visualization in this notebook significantly as there were sharp changes in gradient.

Insights Gained:
-Joan Keza
when doing this task I explored normal distribution and its connection to Bayesian inference. Many natural phenomena, such as height, test scores, and errors in measurements, follow a normal distribution. Understanding this helped in visualizing probability updates when applying Bayes’ theorem to normally distributed data. The connection between gradient descent and Bayesian inference became clear when I realized that Scipy optimizations adjust learning rates automatically, much like how Bayesian updates refine probabilities based on incoming data. Through research, I found that Bayesian inference is preferred because it systematically refines probabilities rather than making static assumptions. This also helped me gain a lot because my group members were able to explain everything which made it easy and understandable

