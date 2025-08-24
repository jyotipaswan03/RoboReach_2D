# RoboReach_2D
This project showcases a 2D robotic pick-and-place task where a manipulator picks a brick from one position and places it at another using ROS for communication and control and SciPy for trajectory planning. The primary objective is to design smooth, collision-free, and dynamically feasible trajectories that allow the manipulator to execute the task with accuracy and stability.

At the core of this project lies the trajectory optimization framework built with SciPy, which is responsible for computing efficient and reliable motion paths. By leveraging numerical solvers and spline-based methods, the planner ensures that the generated trajectories are both mathematically valid and practically executable by the robot. These trajectories are then integrated into the ROS ecosystem, where different nodes handle motion commands, control execution, and system coordination, making the workflow modular and scalable.

The simulation demonstrates a typical pick-and-place scenario where the robot identifies the brick, computes an optimized path, executes the movement, and successfully transfers the brick to the target position
