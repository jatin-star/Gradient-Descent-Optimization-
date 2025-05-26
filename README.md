Gradeint Descent Optimization Algorithms ---------------
1. SGD - simple gradient descent
2. Momentum - Added momentum to escape local minima
3. Nestrov momentum - Controlling momentum (regularize) from exploding gradients
4. Adagrad - Adapt learning rate for parameters
5. Rmsprop - Improve adagrad, Adagrad becomes slow when finishes flat region and reaching minima.
6. Adam - Combine Adaptive learning rate + momentum, It also improves bias in momentum and adagrad which occurs when hyperparameters are high at start.
7. Nadam - Added nestrov momentum (lookahead), slight better in convergence.
8. Adabelief (Best) - Improves Adam, faster convergence. Core Idea - Instead of tracking the magnitude of the gradient, track how much the current gradient deviates from its historical mean.
9. Lion - Sign based optimizer, simplest optimizer, added sign over momentum. Takes only direction leaving magnitude. Move with fixed steps. Computationally efficient (only one momentum with sign). 

10. Lion & Adabelief provide extensive performance.

11. ![](https://github.com/Your_Repository_Name/Your_GIF_Name.gif)

