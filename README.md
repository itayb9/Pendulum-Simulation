# Pendulum Simulations
In this project, we will simulate the classical pendulum as well as the double pendulum, in order to visualize their motions and the physics behind them!

## Simulation 1: Basic Pendulum

### Goal
Build a simple simulation of a single pendulum and visualize its motion.

### Physical Model
Our model will be a point mass attached to a massless string. The motion takes place in a vertical plane, and we will also neglect air resistance.

### Equation of Motion
Using Newton's second law along the tangential direction:

$$
F_\theta = ma_\theta
$$

For a pendulum of length \(L\), the tangential acceleration is:

$$
a_\theta = L\ddot{\theta}
$$

In our model, the only force that applies on the point mass in the tangential direction is gravity. The tangential component of gravity is:

$$
F_\theta = -mg\sin\theta
$$

Therefore:

$$
-mg\sin\theta = mL\ddot{\theta}
$$

And the general equation of motion is:

$$
\ddot{\theta} + \frac{g}{L}\sin\theta = 0
$$

In this simulation, we will use the small angle approximation

$$
\sin\theta \approx \theta 
$$ 

and therfore our final equation of motion for our problem will be:

$$
\ddot{\theta} + \frac{g}{L}\theta = 0