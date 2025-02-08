# solar-system
A simple interactive simulation of the solar system, showcasing the orbits and movements of planets around the Sun. This project demonstrates basic concepts of astronomy and can be expanded with additional features like planet details using python
This project is a basic simulation of the solar system using Python’s turtle graphics library. It models the movement of planets orbiting around the Sun by simulating gravitational forces and updating their positions over time.

Key Components:
SolarSystem Class:
This class represents the entire solar system and manages the Sun and planets.
It provides methods to add planets, display planet information, and animate their movements based on gravitational forces.
Sun Class:
Represents the Sun, with properties such as its name, radius, mass, and temperature.
The Sun is positioned at the center of the system with a fixed position.
Planet Class:
Represents individual planets, each with properties such as name, radius, mass, distance from the Sun, velocity, and color.
The planets are displayed using turtle graphics and move in elliptical orbits around the Sun based on simple physics.
Features:
Real-time simulation of planet orbits.
Each planet's velocity is updated based on gravitational attraction from the Sun.
The simulation continues for a predefined number of time periods and displays the orbits dynamically.
Usage:
The createSSandAnimate() function initializes the solar system, adds the Sun and several planets, and animates their orbits.
The system updates the planets' positions at each time step using basic physics equations for gravity and motion.
Technologies Used:
Python with the turtle module for graphical rendering.
Example of Planets:
Mercury: Closest planet to the Sun with a small orbit.
Earth: Our home planet with a moderate orbit and velocity.
Jupiter: The largest planet in the solar system, with a slower orbit.
Pluto and Asteroids: Other celestial objects with unique orbital characteristics.
Running the Code:
Clone the repository and run the script to see the animation of the solar system in action.

