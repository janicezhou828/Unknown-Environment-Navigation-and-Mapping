# Unknown-Environment-Navigation-and-Mapping

[image1]: ./Images/map.jpg "map"
[image2]: ./Images/Simulation.JPG "Simulation"
[image3]: ./Images/Trial.JPG "Trial"


The goal of the this project is to develop a program in ROS that drive the TurtleBot autonomously around an unknown environment while dynamically creating a map using sensory information from the Kinect sensor within the time limit.

Since the layout of the environment is not revealed until the contest, having a flexible strategy with high consistency is critical. Our team designed and implemented an algorithm that allowed us to efficiently traverse and map the entire environment with clear key geographic features.

We tested our algorithm using simulations in RVIZ. Here are some pictures and videos of both the simulations and actual trial.

Simulation:
![alt text][image2]
Here's a [link to a video](./Images/Simulation.mp4)

Actual Trial:
![alt text][image3]
Here's a [link to a video](./Images/Trial.mp4)

Actual Trial Mapping Result:
![alt text][image1]

