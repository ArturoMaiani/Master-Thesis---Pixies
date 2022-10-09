## - Master thesis about deep reinforcement learning

This thesis proposes a Deep Reinforcement Learning based method aimed at finding
a trajectory for the unicycle model in order for the robot to visit some regions of
interest on the map in an optimal way and in presence of obstacles. This regions
are given a-priori and represent places where presence of litter has been statistically
detected. Instead of planning a trajectory which connects two points at a time,
for instance using Artificial Potential Fields, this work proposes a global trajectory
connecting all points of interest, allowing the learning algorithm to choose the best
visiting order.
This problem could also be considered as to find an empirical solution for the
Traveling Salesman Problem (TSP) in the case of Unicycle model and presence of
obstacles.
For simplicity reasons, the unicycle model moves according to Dubin’s curves, i.e. either straight left or right with fixed linear speed and angular velocity equal to ±ωmax.
In addition to the task of finding an optimal trajectory, this work focuses on the
effect that the reward function has on the learning problem, in particular analyzing
the fact that the use of negative rewards when hitting obstacles leads to the policy
remaining stuck in some local minima, preventing exploration. In addition to that,
the effects of some key features of the learning algorithm are investigated.
The obtained trajectory must be considered as an approximate guideline for the
robot, but does not take into account the actual presence of litter around the robot.
This obliges to switch to a subroutine when the robot finds itself in the proximity
of litter, which in a real-world scenario could be detected and classifies through
Computer Vision techniques. The proposed subroutine is an heuristic method based
on the combination of a Traveling Salesman Problem and a cubic interpolation task.


![episodio22](https://user-images.githubusercontent.com/100837287/194731622-f052bd87-313e-4160-86bf-ca4113f274f6.jpg)


https://user-images.githubusercontent.com/100837287/194731634-97513d2d-0fd7-40f1-92b4-41d638fe8ab4.mp4

