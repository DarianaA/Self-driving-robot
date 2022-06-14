# Self-driving-robot

The project uses the Turtlebot Waffle Pi architecture integrated within ROS modules, to create the prototype of an individual self-driving robot in the Gazebo simulator.

There are two subprojects: self-driving robot, able to read a line and move along it, detect and circumvent an obstacle;
and self-driving robot, able to self-localise on a patterned line, plan a path to a goal location taking
into consideration the presence of two obstacles, and navigate in and out a parking space.

The two parts were broken into sensor integration, colour detection, obstacle detection,
obstacle avoidance, self localisation on a 1D grid, offline mapping / A* implementation, entering
a parking spot and leaving the parking spot.

