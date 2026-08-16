# 🐭 Micromouse

A beginner-friendly research project on building and understanding Micromouse robots — autonomous robots that solve a maze on their own, as fast as possible.

<p align="center">
  <a href="https://madheshiyaraj562-cmyk.github.io/Micromouse/simulation_for_MicroMouse_map.html"><strong>🌐 A* + PID Simulator</strong></a>
  &nbsp;•&nbsp;
  <a href="https://madheshiyaraj562-cmyk.github.io/Micromouse/floodfill_simulation.html"><strong>🌐 Flood-Fill Simulator</strong></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/madheshiyaraj562-cmyk/Micromouse/raw/main/MicroMouse_Research_paper.pdf"><strong>📄 Research Paper (PDF)</strong></a>
</p>

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-in%20progress-orange">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
  <img alt="Made by" src="https://img.shields.io/badge/made%20by-Raj%20Madheshiya-informational">
</p>

---

## About

A beginner's guide to designing, building, and understanding a Micromouse robot — covering batteries, motors, motor drivers, encoders, PID control, sensors, maze-solving algorithms (Flood Fill, A*, DFS/BFS), mechanical design, PCB design, and testing/calibration.

> 🚧 The research paper is still a work in progress and will keep being updated.

## Contents

| File | Description |
|---|---|
| [`MicroMouse_Research_paper.pdf`](./MicroMouse_Research_paper.pdf) | The full write-up (70 pages): competition rules, history, hardware (motors, batteries, voltage regulators, motor drivers, encoders), PID control theory and tuning, sensors (IR, ToF, IMU), Flood Fill / A* / DFS algorithms, mechanical design, and PCB design. |
| [`floodfill_simulation.html`](./floodfill_simulation.html) | An interactive game — drive a mouse through a maze yourself, then reveal how the Flood Fill algorithm would have solved it, with an efficiency score. |
| [`simulation_for_MicroMouse_map.html`](./simulation_for_MicroMouse_map.html) | An autonomous A* + PID simulator — the mouse plans a path with A* and drives it with a tunable PID heading controller, replanning live if you draw new walls. |

## Topics covered in the paper

- Micromouse competition rules & history
- Batteries (LiPo, NiMH, lead-acid) and voltage regulation
- Motors (BLDC vs brushed DC) and motor drivers (H-Bridge, TB6612FNG)
- Wheel encoders & Hall effect sensors
- PID control theory, tuning, and common problems (overshoot, oscillation, integral windup)
- Wall detection: IR, ToF, and IMU sensors
- Maze-solving algorithms: Flood Fill, Weighted Flood Fill, DFS, BFS, A*, Dijkstra
- Mechanical design: chassis, wheel material, center of gravity, caster vs skid
- PCB design and soldering basics

## License

MIT License — © 2026 Raj Madheshiya
