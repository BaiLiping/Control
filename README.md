![1](/Control_Map.png)
Control/feedback is more of a perspective than does a set of techniques.
[Karl Johan Åström. The fascinating history and success of feedback control](https://www.youtube.com/watch?v=R-h66PrQ808)
When the system has feedback dynamics, you need to study its stability. That is the origin of this subject.
![1](/distributions.jpeg)

## Resources
- [Florian Dorfler, Distributed and Networked Control:](https://moodle-app2.let.ethz.ch/course/view.php?id=16968) guest password:atic2022
- [Russ Tedrake, Underactuated Robotics:](http://underactuated.mit.edu/index.html)
- [Jean-Jacques Slotine, Nonlinear System:](http://web.mit.edu/nsl/www/videos/lectures.html)

## Phase Portrait
- [The ODE Project](http://faculty.sfasu.edu/judsontw/ode/html-20180819/nonlinear02.html)
- [GeoGebra Visualization](https://www.geogebra.org/m/fYxXgbsU)

### Linear System
For 2D Homogeneous system, the stationary point would be (0,0). For non-homogeneous system, the stationary point would be somewhere else.
#### Sink
![1](/pics/sink.png)
#### Source
![1](/pics/source.png)
#### Saddle
![1](/pics/saddle.png)
#### Repeated Root
![1](/pics/repeat.png)
#### Center
![1](/pics/center.png)
#### Spiral Sink
![1](/pics/spiral_sink.png)
#### Spiral Source
![1](/pics/spiral_source.png)
#### Stability
![1](/pics/stability.png)

### Nonlinear System
![1](/pics/nonlinear1.png)
![1](/pics/nonlinear2.png)
![1](/pics/nonlinear3.png)

## Lyapunov for Reachability Analysis
- [Lyapunov Analysis](http://underactuated.mit.edu/lyapunov.html)
#### Time Varying Lyapunov Function
![1](/pics/reachability1.png)
#### Time Invariant Set
![1](/pics/reachability2.png)

### Control Lyapunov
So long as u can't battle the dynamics of the system, as approximated by the derivative of the Lyapunov function, the system is stable. 
![1](/pics/controllyapunov.png)

## Robust MPC
![1](/mpc.png)