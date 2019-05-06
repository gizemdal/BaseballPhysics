## Baseball Physics
Python-based computational physics project that explores the physics behind the trajectory of a flying baseball

## Background Information

• The most simplified model of any flying object in Earth is called Projectile Motion in Vacuum where the object is only subject to gravity along the y-axis and no other forces are observed.

• A more complicated approach to visualize the trajectory of an object in projectile motion is by including air drag force which acts in the opposite direction to the velocity of the object.

• A secondary complexity could be added by taking the Magnus force into account. So, what is this Magnus force exactly? Basically, the flying object’s (in our case, the baseball’s) rotation around itself causes a pressure difference between its two opposite sides which causes a force “lifting” the object towards low pressure, which is called the Magnus force.

## Techniques

The physics behind calculating the trajectory of the baseball involved solving a second-order differential equation to find the changes in acceleration, velocity and position using the Runge-Kutta method as well as graphing these results with respect to time.

## Results and Conclusion

It is quite clear to see that the Magnus force has a visible impact on the trajectory and the control of the sports balls, including baseball.

• When backspin is provided, the maximum height that the ball reaches becomes higher than the other trajectory models and the ball stays in the air for a longer time. However, this is only true when the x-component of the initial velocity is greater than its y-component.

• When the y-component of the initial velocity is greater than its x-component, we observe similar time of flight to projectile motion yet the ball travels a much shorter distance due to the Magnus force and the air resistance. The same effect can be seen when the ball is provided a topspin rather than a backspin.

• With topspin provided, we also observe much shorter flight time as the lift on the ball is now downwards (which actually deaccelerates the baseball). This also causes a shorter maximum height than all other cases as well as a much shorter distance traveled.

Professional sportsmen use spins on their balls to gain control over the trajectory of the ball for their advantage. This could be seen in golf where players hit backspins to have better control over how far the ball will go and bounce, while baseball players use spins on the z axis to mislead the batter thinking the ball would go one way or another. This simulation agrees with these control techniques as spins provide a greater range of distance and time of flight.

## Resources

http://www.math.union.edu/~wangj/courses/previous/math238w13/Golf%20Ball%20Flight%20Dynamics2.pdf

https://www.seas.upenn.edu/~meam211/slides/aero.pdf

Textbook: Computational Physics by Mark Newman
