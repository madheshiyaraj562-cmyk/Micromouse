# Micromouse
A beginner-friendly research project on building and understanding Micromouse robots.
Masterpiece on Micromouse

A beginner's guide to building a Micromouse robot — covering batteries, motors, motor drivers, encoders, PID control, sensors, algorithms (Flood Fill, A*, DFS/BFS), mechanical design, PCB design, and testing/calibration.

Made by Raj Madheshiya, 2026

🚧 The research paper is still a work in progress and will keep being updated.

Contents
MicroMouse_Research_paper.pdf — the full write-up (70 pages): rules, history, hardware (motors, batteries, voltage regulators, motor drivers, encoders), PID control theory and tuning, sensors (IR, ToF, IMU), Flood Fill / A* / DFS algorithms, mechanical design, and PCB design.
floodfill_simulation.html — an interactive game where you drive a mouse through a maze yourself, then reveal how the Flood Fill algorithm would have solved it, with an efficiency score.
simulation_for_MicroMouse_map.html — an autonomous A* + PID simulator: the mouse plans a path with A* and drives it with a tunable PID heading controller, replanning live if you draw new walls.
