# Assignment1: Enhanced Dynamic Robot Movement Simulation
Develop a simulation for a robot moving through a grid-based environment considering task optimization strategies and safety to ensure efficient travel, collision avoidance, and effective energy management. The simulation should manage the robot's energy levels and battery status, incorporating the necessity of recharging.

**File**

[EnhancedDynamicRobot.ipynb](EnhancedDynamicRobot.ipynb)

**Report**

We have used the Uniform CostSearch (UCS) and A* (A Star) algorithm.
Here we have made changes in agent  class.
the function battery Manager shows that after each step the Battery charge will decrease by 10%. It will recharge again after the battery level is left only 10%.

