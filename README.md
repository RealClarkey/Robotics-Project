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

# Project 4 - Decision Tree Logic Maze Solver.

This workshop focuses on programming the dr20 robot to autonomously navigate a short maze with a curvy path using a behaviour tree architecture. The dr20 robot is equipped with an advanced sensor suite, including 4 ultrasonic sensors (left and right), a front-facing laser sensor, and a front-facing camera.

The goal is to interface with the provided robot API and develop code that pilots the robot out of the maze by interpreting sensor data and implementing autonomous behaviours. Since the maze exit is not explicitly defined, detecting changes in sensor readings to infer the exit is part of the challenge.

Key concepts covered:

- Robot control via Python and the CoppeliaSim (V-REP) simulation environment
- Behaviour tree design and implementation for robot decision-making
- Sensor data interpretation and obstacle avoidance strategies

[![Watch the video](https://img.youtube.com/vi/DXpRNWCIFkE/maxresdefault.jpg)](https://www.youtube.com/watch?v=DXpRNWCIFkE)
*Click the image above to watch the video.*

# Project 5 - Autonomous Maze Navigation with image recognition.

In this workshop, I developed code to interface with the DR20 robot within a complex maze environment simulated in CoppeliaSim (formerly V-REP). The goal was to autonomously pilot the robot through a maze featuring straight paths and signposts, utilising the robot’s sensors, including its front-facing camera. At each junction, the robot was programmed to capture photos of signposts, which will be used for future training of a neural network to improve maze-solving capabilities.

Key tasks included:

- Setting up the simulation environment with the 02_Maze_scene_vrep.ttt file and necessary API libraries.
- Implementing image capture and processing routines to obtain and save camera images at maze junctions.
- Developing autonomous robot behaviour logic based on sensor data to navigate the maze without predefined turn sequences.
- Testing connection and communication with the simulator, handling sensor input, and managing robot motion commands.
- This task served as a foundational exercise in robot sensing, image acquisition, and autonomous decision-making in robotics simulation.

[![Robot Programming Workshop Demo](https://img.youtube.com/vi/Rev1abmeXKU/0.jpg)](https://www.youtube.com/watch?v=Rev1abmeXKU&t=22s&ab_channel=LeighClarke)
*Click the image above to watch the video.*
