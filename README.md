# Robotics-Project
5 Tasks from year 2 robotics module. Using python to control robots and learn robotic principles.
Each task is fully working and scored 100/100.

# Project 1 - Line Following Robot
This task focused on object-oriented programming and practical robot control using the CoppeliaSim simulation environment. I developed a wrapper class for a line-tracing robot, enabling Python-based control via the CoppeliaSim API. The class was completed with methods for motor control and sensor reading, and I used this structure to design and implement a basic line-following algorithm.

The robot successfully navigated a predefined track by interpreting data from three vision sensors (left, middle, right). The algorithm allowed the robot to detect and follow a black line by dynamically adjusting its movement based on sensor input. This workshop reinforced core skills in robotics programming, Python OOP, and simulation-based algorithm development and testing.

[![Watch the demo](https://img.youtube.com/vi/EP7bghfdNMs/0.jpg)](https://www.youtube.com/watch?v=EP7bghfdNMs)

*Click the image above to watch the video.*

# Project 2 - Maze Solving Robot

In this project, I developed a maze-solving robot using the CoppeliaSim environment, building upon the previous line-following implementation. The robot was programmed to detect various types of junctions—such as T-junctions, crossroads, and dead ends—by interpreting signals from its three vision sensors. Based on these readings, the robot made directional decisions to navigate the maze autonomously.

A wrapper class was used to control the robot’s movement and sensor input, and the maze-solving behaviour was implemented using the Left-Hand Rule. This approach ensured the robot followed a consistent strategy to explore and reach the end of the maze efficiently. The completed implementation successfully demonstrated the robot's ability to adapt to different maze layouts and terminate correctly upon reaching the goal.

[![Watch the demo](https://img.youtube.com/vi/16XntRdqn2I/0.jpg)](https://www.youtube.com/watch?v=16XntRdqn2I)

*Click the image above to watch the video.*

# Project 3 - Autonomous Maze Solving with 5 Sensor Inputs on the dr20 Robot 

This project involves programming the DR20 robot to autonomously navigate a short curvy maze environment simulated in CoppeliaSim (formerly V-REP). The DR20 robot is equipped with multiple sensors—including ultrasonic, infrared proximity sensors, a laser, and a camera—which are interfaced through a custom Python wrapper class.

The core task was to implement and improve the robot’s behaviour to pilot it out of the maze using sensor inputs. A Braitenberg algorithm was initially provided as a baseline, but the main focus was on developing an effective obstacle avoidance and navigation strategy by overriding the robotBehaviour() method.

Key features:

- Object-oriented design with sensor and actuator interfacing
- Use of multiple proximity sensors for environment awareness
- Dynamic motor velocity adjustments based on sensor readings
- Integration with CoppeliaSim remote API for simulation control
- Sensor data visualization toggle for debugging

[![dr20 Robot Maze Navigation Demo](https://img.youtube.com/vi/WjxOS5W1JM8/0.jpg)](https://www.youtube.com/watch?v=WjxOS5W1JM8&ab_channel=LeighClarke)

*Click the image above to watch the video.*
