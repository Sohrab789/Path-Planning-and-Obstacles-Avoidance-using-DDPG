# Topic: Path Planning for Maritime Vessels in Current-Affected Waters
README
# Overview
This project focuses on the development of a path planning algorithm for maritime vessels that enables them to navigate towards a designated goal while avoiding obstacles. These obstacles can include other vessels, underwater structures, and challenging environmental conditions such as currents. The goal is to compute the shortest and safest path that minimizes travel time while ensuring collision avoidance.

# Objectives
Shortest Path Calculation: Utilize efficient algorithms (like A*, Dijkstra’s, or RRT) to determine the optimal route from the ship's current position to its target destination.
Obstacle Detection: Implement real-time detection of obstacles, including both static (e.g., islands, buoys) and dynamic (e.g., other ships) entities within the maritime environment.
Current Effects: Incorporate environmental data to account for currents that can affect vessel speed and direction. The path planning algorithm should adjust routes based on current predictions to optimize travel time and fuel efficiency.
Simulation and Testing: Use simulation tools to visualize the path planning in action, demonstrating the algorithm's effectiveness in navigating through various obstacle configurations and current scenarios.
Features
Dynamic Path Adjustment: The algorithm will adapt to real-time changes in the environment, such as new obstacles or variations in current strength and direction.
User Interface: Develop a graphical user interface (GUI) to visualize the vessel's route, current effects, and obstacle locations, allowing for easy interpretation of the path planning results.
Technologies Used
Programming Languages: Python (for algorithm implementation and simulation)
Libraries and Frameworks:
NumPy and SciPy for numerical computations
Matplotlib for data visualization
Pygame or a similar library for developing the GUI
Simulation Tools: Use existing maritime simulation environments or develop custom simulations to test the path planning algorithm under various conditions.
