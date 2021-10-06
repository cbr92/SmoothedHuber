# SmoothedHuber
This repository provides a modification to the Huber loss function proposed in (reference to Huber 1964). This is motivated by a desire for the second derivative of the Huber loss to decay smoothly from 1 to zero over an interval of length "h". This smoothing of the second derivative is achieved by piecewise interpolation with a cubic polynomial. This cubic polynomial is unique given the constraint that the resulting function be continuously differentiable.

The corresponding first derivative and loss function itself are also uniquely determined by the requirement that both be continuously differentiable.
